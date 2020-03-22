---
layout: project
title: Syncthing
description: Open Source Continuous File Synchronization (open source contribution)
project: syncthing
show_tile: true
repository_url: https://github.com/syncthing/syncthing/
doc_url: https://docs.syncthing.net/
---
## Description
Syncthing is a continuous file synchronization program. It synchronizes files between two or more computers in real time, safely protected from prying eyes. Your data is your data alone and you deserve to choose where it is stored, whether it is shared with some third party, and how it's transmitted over the internet.

## What I've contributed
### Push notifications for web interface
Syncthing provides a web interface to manage the instance and visualize sync status for folders and devices. Some sync event are important like folder sync completion, sync errors new device/folder sharing invite.  
Based on an issue ([#5329](https://github.com/syncthing/syncthing/issues/5329)) I've implemented basic web push notifications to notify user about these important events.  
For now the [PR (#6244)](https://github.com/syncthing/syncthing/pull/6244) is always in work-in-progress state.

## Technologies used
* golang
* AngularJS