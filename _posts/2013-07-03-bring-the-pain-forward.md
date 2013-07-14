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
I have had a few people ask me to do a write up about what went into building my ErgoDox keyboard after seeing me use it at some local programming meetups. However, a quick google brought up a masterful step-by-step assembly walkthrough that [**Massdrop**](https://www.massdrop.com/ext/ergodox/assembly.php) put together, detailing all tools and elements needed, instructions, and excellent visual aids. 

So I decided instead to touch on *why* I built it instead of *how*, throwing in some notes on a few gotchas I ran into.

I have tried my hand at soldering a few times over the years and have always been disappointed with the outcome. (I would need to solder a few wires for a light or some other minor home project that only required making a few connections – enough to get frustrated at my lack of skills, but not enough to actually get any good at it.)

I tend to be always tinkering with something or reading a tech book or some such, and it just happened this time that while I was growing increasingly frustrated with my old keyboard I was also reading [Continuous Delivery](http://www.thoughtworks.com/continuous-delivery) by Jez Humble and David Farley. There is a phrase in Continuous Delivery I’ve heard often in the software game, but this time it just resonated with me in a way it never had in the past. While I previously had considered this phrase solely in a programming context, this particular day it just felt so obvious that I needed to apply it to the art of soldering. Clearly, tinkering with the hardware I wanted to work with would remain impossible unless I did something to build up my soldering chops.

The basic principle of the phrase “Bring the pain forward” is that if something is hard (for example, software integration at the end of a development cycle) then instead of avoiding it and turning it into a huge project every two weeks, do it more often. Break it down into smaller tasks that you do repeatedly until you get so good at it that it becomes easy.

Building my ErgoDox keyboard was my attempt at bringing the pain forward. After soldering over 200 pins during the assembly process, I finally feel comfortable soldering – even when forced to work with those tiny surface mount chips that had intimidated me in the past.

A few things I learned in the process:

I had read over and over that you should heat the pins and not apply the solder directly to the soldering iron. That isn’t quite right. You shouldn’t apply the solder only to the soldering iron, but you should briefly touch the soldering iron to the solder to start the heat flowing. Without pictures handy the best way to describe it is that you should pinch the solder between the iron and the pins, then as the solder liquefies, move it around the pad/pin to get a good connection.

Get a decent soldering iron. You don’t have to spend hundreds on it, but I found I was struggling with consistency using a $15 model I picked up at Radio Shack. Once I switched to a [**Haako**](http://www.hakko.com/english/products/hakko_fx888d.html) I had a much easier time getting consistent results.

If you are trying to assemble one of these and have problems: check your connections. The correct way to test is not to test at the pins of the key or diode, but at the pad to verify that you are actually getting current flowing all the way through to the board. For keys, you should see the resistance drop once a key is pressed. The diodes are directional, so make sure you have a good connection and that they are soldered to the board in the correct direction. I had messed up a few of my initial joints on both keys and diodes and was able to troubleshoot it using the instructions posted [**HERE**](http://www.allaboutcircuits.com/vol_3/chpt_3/2.html).

Not only do I love my ErgoDox keyboard for the obvious reasons (separate boards, highly customizable key layouts, I made it myself!, etc.), but by applying the concept of bringing the pain forward to soldering, I was able to conquer what felt so frustratingly daunting for so long.

*Massdrop periodically runs group buys of the parts needed to assemble this keyboard.  Check back with them if you want to save some money on the parts needed for a whole keyboard, otherwise you can always source the parts individually with a little scouring online.  Shapeways can print the cases and the pcbs are open sourced.*