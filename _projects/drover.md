---
layout: post
title: Drover
# description: ![title card](/portfolio/assets/images/d-title.png) 
description: Remain resilient while you herd a lone sheep back to its flock 
# description: <img src="/portfolio/assets/images/d-title.png" alt="a">
---

![title card](/portfolio/assets/images/d-title.png)

Drover - Academic Project
------- 

### What is [Drover](https://milosneptune.itch.io/drover){:target="_blank"}? ###

Drover is a 2.5D adventure puzzle game, taking place in the isolating wilderness of the mountains. Will you remain resilient and be able to herd a lone sheep back to its flock? Or will you succumb to nature's twisting paths, unable to find the light? 

Drover was an academic project made for the course, IGME-320, Game Design & Development II. Our team was made up of five people. 

![screenshot of the game](/portfolio/assets/images/d-ss1.png)

#### Role: Game Designer
  * Co-operated cross-functional team of five, handling production processes, scheduled stand-ups and meetings, planned sprint milestones and goals, ensuring production ran smoothly
  * Crafted high-level game pitch, composing of key design pillars and emotional arc, created engagement beat and progression maps and plotted level layout
  * Analyzed level layouts through iterative internal play-testing in Unity Engine, tracking time and quantitative metrics to identify navigation issues and improve player navigation

**Tools:** Github, Unity Engine, Visual Studio, Clip Studio Paint

**Team Size:** Five people

#### Design
 
The level design of Drover was a challenge, that I have not quite refined. This section focuses on the iterative design process regarding my map and level design.
The diagrams below showcase what I had designed for our minimum viable interaction:

![Visual of mvi map](/portfolio/assets/images/d-MVI_map.png)
![Visual of greyboxed idea to show devs](/portfolio/assets/images/d-greyboxed_idea.png)


Our first map was essentially a straight line, with 3D objects scattered around the scene, aimed at testing the player's ability to move and herd the sheepdog. Once we had moved on from using a straight line with 3D objects scattered around to simply test player movement at the base level, it was time to produce a finalized map.

When sketching the layout, I referenced hiking trails, and kept in mind our core design pillar, which is the isolating wilderness. Therefore, my objective while designing this map was to make the path ways feel long, twisting, and isolating with numerous dead ends and loops back to the main path, attempting to catch that maze-like feeling and capture the "I'm lost" realization. I had drawn this as a "finalized version" of our map.

![Visual of first map](/portfolio/assets/images/d-map1.png)
![Visual of first map, with marked puzzle/enemy locations](/portfolio/assets/images/d-map_enemy_puzzle_locations.png){: width="395" }
![Visual of first map, with environment notes](/portfolio/assets/images/d-map_environment.png){: width="397" }


Looking back at it now, I can easily realize that this was far too complex of a map for our scope. Seeing the map be implemented in Unity, it rapidly became clear to me that our development team was struggling in realizing what my vision was--that problem did not lay solely on their end, but a failure for me as well for not being able to communicate exactly what I had intended. The map was implemented at a far larger scale than I had envisioned.

To resolve this difference in our team's visions, we internally tested the map with the developers.

I firstly started by drawing the main "route" the player would have to take from the start to the end, my intention was to refine this core path before adjusting it to incorporate more branching trails and loops.

![Visual of second map](/portfolio/assets/images/d-map2.png)

I asked one of our developers to simply run through the path, as an image placed flatly on the ground. There were no walls or assets or environment or even a sheep to herd, just follow the path on the ground, and that I would be recording their time on a stopwatch and noting it down.

We intended our game to only be 5-10 minutes long in gameplay, therefore, it made the most sense to me that this type of run should only last 1-2 minutes, preferably the lesser the better.

The first run we recorded was almost six minutes. Six minutes to run through the map, no stopping, no distractions like the sheep or enemies or the environment or the forks in the trail, six minutes. The addition of all these components would surely increase the time drastically. As yoou can guess, this is way too long!

Thankfully, our first run was before we updated the player and sheep movement. Once we ran the same test again, provided with the current movement speeds, our result was around the 3-4 minute mark. Slightly better, but there's still a lot of room for improvement.

The next few runs involved squashing the map from the right, without keeping it's aspect ratio, and paying attention to which sections of the map felt too "linear." We would readjust, rinse, and repeat.

Our time was getting a bit better, step by step. At some point, I realized that an indicator halfway was needed in order to compare the two halves of "difficulty." The first half should be slightly easier to navigate than the second half.

By our 5th map iteration, we had finally settled into a good time: one minute and 52 seconds. Now, we had to test this working with the player herding the sheep.

![Visual of third map](/portfolio/assets/images/d-map3.png)

Some constraints of this run, we attempted herding on-top the map without any walls in place. The sheep's logic causes it to avoid any walls, so without the walls in place, our method of testing was limited. Our time was two minutes, 30 seconds. Okay, not bad? Except the sheep completely skipped over some of the bends in the map, and would move off the path quite frequently.

More constraints due to the way we tested this--now, our paths were walled, but the actual pathway itself was quite thin. Two minutes, 29 seconds--a very similar time to the run previous.

After more testing, we solidified a suitable version of the map and ended with a time of two minutes and 29 seconds. Afterwards, I went back and adjusted the map to add some varying dead ends and loops to capture the wilderness feeling, making it appear more like a hiking trail.

This is the map layout we concluded on.

![Visual of final map](/portfolio/assets/images/d-map4.png)

Again, we ran through the map while herding the sheep, and having placeholder walls, reaching a time of two minutes and 50 seconds. This was a much more desirable time than lengthy and boring maps we had given to our play-testers, but also keeping in mind that we had only tested this internally on someone who knew what the map layout was.

Still, this isn't completely finalized. There is much I learned from this process, and there's still more I can learn. Going forward, I watched how players react to the map carefully, and evaluating whether or not this iteration is the most successful so far and where we can improve.

#### Related Links:
* [Repo](https://github.com/IGME320TheHerd/SheepProtector){:target="_blank"} 
* [Website](https://igme320theherd.github.io/SheepDev/about/){:target="_blank"} 
* [Itch](https://milosneptune.itch.io/drover){:target="_blank"} 
