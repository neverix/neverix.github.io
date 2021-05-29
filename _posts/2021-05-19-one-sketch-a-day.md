---
layout: post
excerpt: One sketch a day challenge
---

Starting from today, the 19th of May (Wednesday), I will implement one algorithm per day, visual or other, and share the source code.

# Day 1
[Atom Visualisation](https://editor.p5js.org/neverik/sketches/ZKPIINchE).

# Day 2
[Spinning Cube](https://editor.p5js.org/neverik/sketches/2sLZg6jZ-). I couldn't figure out how to make the box spin vertically so the result looks weird.

# Day 3
[Bouncing Balls](https://editor.p5js.org/neverik/sketches/NWuNKn2sc).

I started with one ball with simple acceleration and collision physics and then added more balls and wind. The hardest part was writing the collision resolution between balls, and I'm still not confident that it's 100% right.

# Day 4
[Attracting Balls](https://editor.p5js.org/neverik/sketches/-ffGOE3k9).

This started as an attempt to add attraction between the balls to the previous day's sketch. Then I started experimenting with repulsion and alternating between the two. The behaviour became more and more complex as groups of balls and unattached singletons appeared. The end result reminded me of biological simulations, so I colored the balls green.

# Day 5
[Chains](https://editor.p5js.org/neverik/sketches/Ito9IVcgF).

This is an experiment for a project involving cloth simulation. For this sketch I did the simplest thing possible: a simulation of a chain made up of little links. There are no feedback effects to take care of, and each element is only connected to its immediate neighbours.

# Day 6
[Waves](https://editor.p5js.org/neverik/sketches/CaKPfJscXw).

First, I created a 2D wave simulation. Then I started adding interactivity and this slowly turned into a game.
This is a 3D experiment, and there weren't any problems except for making mouse interactions work with boxes. I had to add an external library to handle them.

# Day 7
[Cloth](https://editor.p5js.org/neverik/sketches/2_ndMduuf).

I really like how this turned out, but the simulation is sometimes unstable. Instead of hard constraints, the sketch uses spring forces to mimic rubbery cloth. The simulation noise eventually builds up.

# Day 8
[Sines](https://editor.p5js.org/neverik/sketches/lbCT9EcL3).

Simple sketch this time. I experimented with better random generation and color encoding this time.

# Day 9
[Life](https://editor.p5js.org/neverik/sketches/4abWy46OJ).

This one is pretty basic too. This is a simple implementation of Conway's Game of Life. I experminted with manipulating pixel arrays directly and changing pixel density. There might be some bugs around the edges of the map, but the simulaiton still works well. I like the gradual expansion and it even produces gliders. 

# Day 10
[Insets](https://editor.p5js.org/neverik/sketches/BiYOSCN1c).

This time I experimented with procedural animation. The result is barebones because I was in a rush, but I learned a lot about circle math and P5's drawing transforms.

# Day 11
[Spirals](https://editor.p5js.org/neverik/sketches/uBQyuleP0).

Another simple sketch. This time I didn't erase stuff on the canvas, only adding to it. I think that takes a hit on performance. However, it makes drawing easier.
