---
layout: project
title: SoundDrop
description: Multiroom audio system (very early stage)
project: sounddrop
---
## Description
Sound Drop is a golang software to play music in multiple rooms at the same time. It's designed to run on multiple devices and allows them to discover themselves automatically on the local network. User can after create group of devices to share sound between them.

## Motivation
Some softwares already exists and do this well. However they use client-server architecture.  
I wanted to know if it was possible to do  not use this architecture and then allow a device to be client or server or even the two without restarting the software.  
So I've made sounddrop ;)

## Technologies used
* golang
* [suture](https://github.com/thejerf/suture): supervisor trees for Go
* [beep](https://github.com/faiface/beep): audio library for Go
