---
title: Arduino Experiment - Percussion Lock
date: 2025-04-27 20:00:00 +1000
categories: [Life]
tags: [circuit, arduino, robotics]
---

Recently picked up interest in electronic circuit, and got an Arduino starter kit to play with.

The book that comes with the kit is well structured and informative.

Now coming to project 12, I've decied not to follow the idea in the book. Instead of just looking for number of knocks, a correct percussion is needed to unlock. Let's call it Percussion Lock. 

See video below for the idea:

[![Arduino Uno Experiment - Percussion Secret](https://img.youtube.com/vi/VU5ztTpm1ms/0.jpg)](https://www.youtube.com/shorts/VU5ztTpm1ms)

- Any percussion can be used as the secret
- When the right percussion is input, it'll unlock. At this point the green LED will be ON and the servo motor will turn
- When unlocked, you can reset the secret by long-press a switch
- The yellow LED will flash to indicate a beat has been received, either during setting the secret or during unlocking

For code (sketch) and circuit, see [Github](https://github.com/totrit/arduino-experiments/tree/031ffe74e3a13da6dda0823ba5721b0fdae9291a/percussion-lock)