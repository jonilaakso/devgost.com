+++
title = 'HackThisSite Basic Mission 3 walkthrough'
date = 2024-02-29T19:46:37+02:00
draft = false
tags = ["ethical hacking", "hackthissite", "hacking"]
+++

This is a walkthrough of the basic challenge 3. 

<!--more-->

<iframe width="560" height="315" src="https://www.youtube.com/embed/eNK9-Nn5yQ4?si=HCJQIHKgmQ0Dy9ju" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

The voice-over for these videos is done by MicMonster AI TTS. 


## Basic 3 - Mission Briefing 
On this mission the briefing described that this time Sam remembered to upload the password file, but there were deeper problems than that.

This time submit button did not sign us in. 

## Solution
To solve this challenge, I had to look in to the source code. 

** Steps to get the password: **
1. Right-click on the password-field and select inspect
2. There is a hidden-input field that has value "password.php"
`<input type="hidden" name="file" value="password.php">`
3. Copy the "password.php and paste it in the end of page url. 
`https://www.hackthissite.org/missions/basic/3/password.php`
4. Press enter. You get redirected to the password.php -page and you should see the password.
5. Copy the password and paste it to the password field. Press submit. 


## My thoughts about this challenge?

This challenge was easy, but it shows that sometimes the source code can reveal information about your app that you would not want to show. Remember that anyone could view the source code. Better to make sure that there is not something we don't want people to see.