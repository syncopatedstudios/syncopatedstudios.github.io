---
layout: page
title: soundbot
subtitle: a gem of code
permalink: /soundbot/
---

# Open Source Audio
#### complicated, then simplified, then complicated again, etc

Soundbot. Not so much one thing, as colascence of ideas....

Meant to the modular. (e.g. taking several lowend machines from the dumpster, and having them create sound that seems like it's produced by equipment you pay for...)



## Another one?

Yeah.

I'm most likely going to try and see this set of ideas through (as long as it makes sense). Having said that, waht I'm trying to express here is more to do with how you look and think about Open Source Audio as opposed to continuing focus on system specifics.

One of my biggest hurdles in getting to the whole LAU scene, was parsing through resources scattered all of the web, half the time out of date by the time you get there...so part of this will a document repo, containing links and pdfs related to linux and/or audio that I've collected over the years.

## Based on arch?
why?

    z. community packaging and probably the best techincal wiki I have personally used.

If you're getting into Open Source Audio, and aren't familar, the Arch Linux support community is one of the best. Well organized, thoughtfully laid out so information on just about any aspect of Linux can be sought, processed and applied.

At the pace at which audio software is being produced, it helps to have access to the newest build tools, which Arch faithfully provides. To me at least, Arch has proven to be a perfect blend between stability and "cutting edge".


## How will this magic work?

* using the idea from arcolinux, an installer, that can just install a arch system like you normally would...with choice of desktopmanager/ui with calamares configured to install Professional Audio related applications.

* system pretty as is,
  * with "soundbot art" and a collection of finger-picked software
  * ansible playbooks to optionally further config stuff (if ya want)
  *

## rest in peace (as infomation is abundious)

## handy local search util using some cool linux tools....

# deadsampler
a sound collection manager using version control to assist in collaboration.
Primarily written in ruby, is mostly a wrapper around stable versions of common unix
applications designed specifically to do one thing and one thing well. using deadbeef as
a graphical frontend...ideally connected to sonic-pi....

support for huge collections
using redis and ohm

support for wav,flac,etc
sf2/gig
sfz

search by types, select and generate normalized "stems"

_generate midi_maps for linuxsampler_





## a long list of fairly even manic'd idears
#### operating system
- [ ] logo, system color scheme
- [ ] gather list of packages to be used
- [ ] live iso
- [ ] screencast workflows

#### deadsampler
- [ ] design db schema
- [ ] decide on categories/labels


- [ ] parse files
- [ ] audiofiles themselves(tags, filenames, sox info, etc analysis tools)


- [ ] cli
- [ ] api


- [ ] add an autocomplete to load instruments into qsampler[1]
- [ ] autocomplete deadsampler "playlists" in sonic-pi


[1]https://gist.github.com/Jell/c06a7b254fdb3aaeb6ce
