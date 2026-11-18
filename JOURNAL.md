---
title: ledscreen
github: avycado13/ledscreen
description: A screen made from a matrix of leds
created_at: 2026-11-14T00:00:00-08:00
---

# 17 Nov: Made LED Matrix
I came up with my Idea for holiday hardware swap. I will make a board of leds that can function as a display.
Then, I made the LED matrix in KiCad. I chose to go with a 16x8 matrix of 3x3 leds. This should hopefully fit inside the 100mm restrictions of JLC and leave headroom for my xiao and other ICs I need to control it. I will use 3 shift registers coupled together so that when data flows into one, the overflow goes into the next and so on.

*Total Time Spent: 3H*
![LED Matrix subsheet](https://cdn.hackclub.com/01a1ed70-4cba-7dd6-9263-9a010a0ebd16/Screenshot%202026-11-17%20at%2022.55.18.png)
