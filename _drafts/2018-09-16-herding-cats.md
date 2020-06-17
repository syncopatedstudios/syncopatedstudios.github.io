---
layout: post
title:  "Herding Cats"
subtitle: ""
date:   2018-09-16
categories: [linux-audio]
---

For a while I've been using jalv.select to launch plugins. It's minimal and doesn't tend to crash. Then after a night of adderall and furious internet reseach I stumbled upon Ingen. It allows you to build modules "pads" with lv2 plugnis and save them for repeated use.

A little note on the mono-to-stereo spilter. after reading this it seemed like a good idea to put tis one in spots where a mono signal was going to be split.


"But what happens if you apply a mono plugin to a stereo track (or put it in a chain of plugins after a plugin with stereo outputs)? In this case, actually two instances are created of the same plugin, and the two input channels are processed by these two separate plugins to get two output channels. The two instances are binded to the same GUI controls, so you see and adjust only one plugin GUI. But keep in mind that it's actually two plugins running in the background, consuming twice as much memory and CPU power as one single plugin would cost." [1]



[1]: http://tap-plugins.sourceforge.net/ladspa/general.html
