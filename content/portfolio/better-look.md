+++
showonlyimage = true
draft = false
image = "portfolio/assets/better-look/icon.png"
date = "2016-11-05T18:25:22+05:30"
title = "Better Looking Boy"
weight = 0
+++

BetterLook was a companion application for [The Lavender Scare][1]'s single 'Better Looking Boy'.
<!--more-->

[1]: http://thelavenderscaremusic.com

{{ $image := .Resources.GetMatch "better-look/icon.png" }}
{{ $image.RelPermalink }}