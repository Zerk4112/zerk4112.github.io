---
layout: post
title: Memory Matching Madness
tags: pico-8 lua games arcade
categories: arcade pico-8
image:
  path: /assets/images/arcade/memory-matching-madness/memory-matching-madness-logo.gif
---

Welcome to "Memory Matching Madness," a captivating memory matching card game that will test your memory and perception. Immerse yourself in this classic game with a twist, featuring smooth animations and dynamic gameplay.

<!--more-->

<!-- ## [Click here to play!](/assets/pico-8/memory-matching-madness/mmm.html){: style="color:gray; font-size: 80%; text-align: center;"} -->

<h1> <p style="text-align: center;"><a href="/assets/pico-8/memory-matching-madness/mmm.html">Click here to play!</a></p> </h1>

---

## Blog Post

For this project I wanted to create a game multiple purposes:

- Learning GitHub Copilot
- Finish a project to a polished product
- Create a repository of common libraries that myself and others could utilize in future projects

### Github Copilot

In the tech industry, AI is quickly becoming a powerful tool for developers to utilize for so many purposes. I was tasked with learning how GitHub Copilot could assist my fellow developers with their projects and how it could be used within our enterprise.

My experience with GitHub Copilot has been very exciting. It has a lot of uses, and helped me go from written design to working prototype within four hours!

While Copilot helped immensely, there were multiple hiccups that i encountered along the way. Primarily the issue of: its easy to let it let you be lazy. While it can most certainly write you functions that perform almost exactly what you want.. it perhaps doesn't do it in the most efficient manner.

AI can be a very valuable *tool*, but it is not a *solution*. It can *help* you reach a conclusion, but to use it as the conclusion can lead to eventual if not immediate madness.

With that mindset I feel that i was somewhat successful optimizing tokens, however there is certainly room for improvement. In an effort to get the game finished quickly, there were corners cut for sure which lead to token-bloat. At one point I actually ran out of character space! The error it produced made me chuckle.

### Finish a project to a polished product

I have made numerous little PICO-8 carts of various degrees. Primarily tool carts to learn the API, but i have made multiple demos that never went anywhere. These unfinished projects have been weighing on me, so I wanted to put extra effort towards finishing a project.

With this goal in mind, I picked a game that I felt would be easy to implement: A card matching game. During brain storming I thought of the Super Mario Bros. 3 card matching mini game, and wondered what game mechanics could be implemented alongside the normal matching.

I thought of Tetris and how everything 'shifts' down, so I went with the idea that when you finish matching 2 cards in the game, all cards above these matches would 'shift' down. This eventually evolved into the configurable shifting you see in the final game, where cards can not shift at all, shift down, shift in random directions, or the most difficult behavior: Random shifting with the ability to shift the furthest card first, acting almost like a blender effect.

### PICO-8 Common Libraries Repository

There are many times I end up copy/pasta'ing my code from one cart to another because.. well, I'm lazy.

This needed to stop. This had to end. So, I created a repository to store all of these commonly used functions. One of my most treasured libraries is my coroutine library.

I tend to use a lot of coroutines to handle update and drawing functions for objects and UI elements. For this projects, I made heavy use of coroutines for the animations that you see. Whether the card is moving or flipping, a coroutine is handling this action.

## Features

- Engaging Gameplay: Challenge your memory as you match pairs of cards and earn new shapes to match.
- Dynamic Grid: Watch as matched cards disappear, causing the remaining ones to shuffle in random directions, creating a fresh challenge with each move.
- Pico-8 Engine: Crafted using the powerful Pico-8 game engine for a retro-inspired aesthetic

## Controls

- Controller support by default
- Mouse supported in PICO-8 Menu
- Touch support in PICO-8 Menu

## How to Play

Playing "Memory Matching Madness" is simple:

1. Click on two cards to reveal them.
2. Match pairs of cards to make them disappear.
3. Keep matching until you've cleared the entire grid.

## Status: *Complete*

---

### Links

- [**Lexaloffle**](https://www.lexaloffle.com/bbs/?tid=53807)
- [**Itch.io**](https://zerkdev.itch.io/memory-matching-madness)
