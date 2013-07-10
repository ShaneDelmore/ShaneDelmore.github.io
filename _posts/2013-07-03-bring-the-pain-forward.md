---
layout: post
title: "Bring the Pain Forward"
description: ""
category: articles
tags: [Ergonomics, Hardware]
image:
  feature: ergodox.jpg
---
<!--- {% include JB/setup %} -->
I have had a few people ask me to do a writeup on building my keyboard after seeing
me using it at some of the local programming meetups.  I was all set to take on the task but 
decided to do a quick google before I started only to find that
[massdrop](https://www.massdrop.com/ext/ergodox/assembly.php) has already done a much
better job than I could of documenting the process.  

So I'll switch gears and touch on why I built it instead of how, throwing in some notes on a few gotchas I ran into. 
   

I have tried my hand at soldering a few times over the years and always been disappointed
with the outcome.  I would need to solder a few wires for a light or some other trivial 
thing that only required making a few connections, enough to get frustrated but not 
enough to get good at it.  I tend to be always tinkering with something or reading 
a tech book and it just happened this time that while I was growing frustrated with my 
old keyboard I was also reading [Continuous Delivery](http://www.thoughtworks.com/continuous-delivery) 
by Jez Humble and David Farley.  There was a phrase in continuous delivery that I have 
heard over and over in the software game but this time it just resonated with me 
in a way it never had in the past.  Previously I was thinking of it as a good idea
at work but that day it just felt so obvious that I needed to apply this to soldering 
since I like to tinker and can't play with the hardware I want to work with unless I get better
with it.  The basic principle of the phrase "Bring the pain forward" is that if something
is hard (like software integration at the end of a development cycle) then instead of 
avoiding it and turning it into a huge project every two weeks, do it more often.
Break it down into smaller tasks, that you do repeatedly until you get so good at it
that it becomes easy.  

Building my ErgoDox keyboard was my attempt at bringing the pain forward.  
After soldering over 200 pins during the assembly process I finally feel comfortable
soldering, even those tiny surface mount chips that had intimidated me in the past.

A few things I learned in the process.  

I had read over and over that you should heat the pins and not apply the solder
directly to the soldering iron.  That isn't quite right.  You shouldn't apply the solder
only to the soldering iron but you should briefly touch the soldering iron to the solder
to start the heat flowing.  Without pictures handy the best way to describe it is that 
you should pinch the solder between the iron and the pins, then as the solder liquifies
move it around the pad/pin to get a good connection. 

Get a decent soldering iron.  You don't have to spend hundreds on it but I found 
I was struggling with consistency using a radio shack soldering iron I picked up
for $15.  Once I switched to a [Haako](http://www.hakko.com/english/products/hakko_fx888d.html) 
I had a much easier time getting consistent results.

If you are trying to assemble one of these and have problems check your connections.
The correct way to test is not to test at the pins of the key or diode, but at the pad 
to verify that you are actually getting current flowing all the way through to the 
board.  For keys you should see the resistance drop once a key is pressed.  
The diodes are directional, make sure you have a good connection and that they 
are soldered to the board in the correct direction.  I had messed up a few of my initial 
joints on both keys and diodes and was able to troubleshoot it using the 
instructions posted [here](http://www.allaboutcircuits.com/vol_3/chpt_3/2.html)
