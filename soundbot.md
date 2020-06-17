---
layout: page
title: soundbot
subtitle: a gem of code
permalink: /soundbot/
---

# for what now?

a sound collection manager using version control to assist in collaboration.
Primarily written in ruby, is mostly a wrapper around stable versions of common unix
applications designed specifically to do one thing and one thing well.

support for huge collections
using redis and ohm

support for wav,flac,etc
sf2/gig
sfz

search by types, select and generate normalized "stems"

_generate midi_maps for linuxsampler_
_using git_
  * I think git-annex might be too much of an admin hassle. Since this isn't meant
    for pushing to github, using git just to keep track is fine.




## roadmap

[] design db schema
  [] decide on categories/labels

[] parse files
  [] audiofiles themselves
    * tags, filenames, sox info, etc analysis tools


[] gather list of packages to be used


[] cli
  [] menu logic

[] api


[] non-unixy frontend


* add an autocomplete to load instruments into qsampler[1]


[1]https://gist.github.com/Jell/c06a7b254fdb3aaeb6ce
