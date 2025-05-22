---
title: "Technology & Current Projects"
date: 2025-05-21T22:03:02-05:00
draft: false
description: "sdlfjl"
---

### Object-gine
We are developing a framework for scripting multiplayer interactive fiction inspired by Renpy. This framework and its accompanying scripting language can be used to easily develop interactive fiction games for mobile and other platforms.

<video controls style="max-width:75%;">
  <source src="/example_engine2.mp4" type="video/mp4" >
  Your browser does not support the video tag.
</video>

```
# Intro
narrator "Here we are, at the boss' office."
enter(Boss,interactive=true,options=[look,talk]);setPosition(Boss,0.5,0.65)
Boss "So you're wondering why I called you in tonight." 
Boss "This is a real important case.{a} I don't know if you knew this about Gonzalez but she was colonel on the police force before making a big career in politics."
...
Boss "Mess up, and you'll be on the K9-unit clean-up detail."
@AP "<i>Uh oh.{a} They won't even let the robots do that kind of work. If it came to it, I would rather be fired.</i>"
@AP "<i>I think my Boss is watching out for me, but it's hard to tell sometimes.</i>"
Boss "And before you leave, one more thing..."
Boss "Kirke fixed up the...{a} whatchamacallit{a} <b><color=red>EMP scanner</color></b> thing, make sure to drop by the lab and take that with you." addKeyword(emp_scanner)
jump(Explore)
```


[DEV LOG HERE](https://docs.google.com/document/d/1eqjGHiL9UlSgFJ7AQlC8XVqqODP9ANND7Dhm50MLwaY/edit?usp=sharing)

#### City of Cohoba
We are completing pre-production for an upcoming game using our scripting framework. 

**The City of Cohoba** is a narrative-driven mystery adventure game set in a vibrant Caribbean metropolis, where players step into the role of a junior investigator unraveling a web of conspiracy within a corrupt police force. With a focus on non-linear storytelling and consequence-driven gameplay, players solve crimes using a unique keyword-based dialogue system and can shape the outcome of a multi-act plot across three possible endings. Features include full character customization, optional co-op multiplayer, interactive side mysteries, and tense sniper missions tied directly to the story. Inspired by classics like Snatcher and Ace Attorney, we are looking to blend investigative gameplay with meaningful player choice, dynamic relationships, and a novel multiplayer approach to the visual novel genre.

[READ UP MORE HERE!](https://docs.google.com/document/d/1YUor5qzPXIvl9-4bS0zGfmxLjv7Z0xND/edit?usp=sharing&ouid=101203322244548721399&rtpof=true&sd=true)
