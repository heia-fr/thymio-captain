TODO: badges

# thymio-captain
Thymio Captain is a complete system offering an easy drag-and-drop web interface (optimized for tablets) to execute programs wirelessly on [Thymio](https://www.thymio.org/home-en:home) robots. 

## Context

TODO: authors 

This system was developed for the "Portes Ouvertes" of the HEIA-Fr on March 2016, in order for the kids to quickly and effortlessly have a feel of how great programming a robot is. Tabletts were at the kids' disposal, as well as four Thymio. 

We created a course made of black lines (the road) and obstacles that the robots should follow/avoid in order to grab a basket of candies and make their way back. Upon success, kids would win the candies.

## Features

The thymio captain is a complete system consisting of the following parts:

* web frontend: 
   - each session/window associated with a unique id from a qr-code
   - compatible with tablets
   - made of predefined and configurable blocks that can be drag-and-dropped and reordered to create a program
   - "undo/redo", "save to the cloud" and "upload" buttons
   - possibility to annotate a program
   - admin interface to manage the Thymios
   
 * API backend:
   - JSON Rest API
   - in charge of linking the web application with the robots
 
 * Thymio backend:
   - running on a Raspberry Pi mounted on the Thymio
   - able to receive an aseba program, compile it and execute it on the tymio
   - ping, start and stop commands available
   
## Overview in action

__Interface__:

![interface gif](http://i.imgur.com/rVLsVdd.gif)

__Round__:

TODO

# Technical overview

## Frontend

Lucy: technos 

## API

Jacques: cards, security, db

## Thymio

Damien: folders in repo, install and limitations

# Status and futur works

(reference on issues)
