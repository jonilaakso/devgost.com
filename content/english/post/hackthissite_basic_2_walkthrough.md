+++
title = 'HackThisSite Basic Mission 2 walkthrough'
date = 2024-02-26T22:16:31+02:00
draft = false
tags = ["ethical hacking", "hackthissite", "hacking"]
+++

This is a walkthrough of the basic challenge 2. 
<!--more-->

<iframe width="560" height="315" src="https://www.youtube.com/embed/xbmw37v6Wr0?si=a1DSP0hS6o2tXU1E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

 The voice-over for these videos is done by MicMonster AI TTS. 

## Basic 2 - Mission Briefing 

When started the mission, we had a hint:
![Hackthissite Basic 2 briefing](/images/hts-basic2-walkthrough/hts-basic2-mission-briefing.png "Basic mission 2 briefing")

This time our Security-hero "Sam" made some improvements and set up a password protection script. He made it to load the real password from an unencrypted text file and compare it to the password we as an user enter. And of course, he forgot to upload the file...

## Solution

If you think about it, he had a script that compares user password to the unencrypted text file.So if there  is no file, what happens? There is nothing to compare the password to. 

Solution here is to just leave the password field empty and press submit. 


## My thoughts about this challenge?

The challenge was a walk in a park, but I think that it teaches a good lesson - sometimes simple way is the right way.   