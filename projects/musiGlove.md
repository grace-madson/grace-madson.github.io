---
layout: project
type: project
image: img/cotton/cotton-square.png
title: "MusiGlove"
date: 2023
published: true
labels:
  - Pic24 Microcontroller
  - C
  - ASM
summary: "A musical glove game project developed for Introduction to Microcontrollers at UMN-TC (EE 2361)."
---

MusiGlove is an ear training game played by bending your fingers! Each finger corresponds to a note, and the
player's task is to listen to the speaker play a sequence of notes and replicate the pattern with by bending
the correct fingers in the correct order.

The project itself consists of short flex sensors attached to a glove. Using ADC, the pic24 microcontroller is
able to sense if a finger is bent past a certain threshold (corresponding to a musical note). The levels would
play through a speaker attached to an amplifer. Other compontents included a 3D printed box, LCD screen, 
and breadboard with all necessary passive electrical components.

My contributions for this project were general organization of the project structure (main program logic
organization), but mostly the speaker/song programming. After each level, a jingle would play 
through the speaker which I programmed. 

