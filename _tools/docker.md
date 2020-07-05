---
layout: default
shortname: Docker
name: Docker
type: Virtualization
category: Development
tags: docker, virtualization, dev, development, container,  
---

# Docker 

Docker

### Remove all images using powershell

$images = docker images -a -q
foreach ($image in $images) { docker image rm $image -f }