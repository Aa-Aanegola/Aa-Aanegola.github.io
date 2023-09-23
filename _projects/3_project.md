---
layout: page
title: Slamma - Automated Negotiation
description: An automated navigation agent for the Genius platform
img: assets/img/negotiation.jpeg
importance: 3
category: misc
---

I took a Multi-Agent Systems course thinking I'd get to explore swarm behaviour (I've always had this idea for optimal drone paths to gain maximal coverage over a complex landscape - straight out of a sci-fi movie but very realistic) but found myself solving constraint satisfaction problems, should've read the course description :\ 

We did get to build a negotiation agent and had a mini tournament where my agent placed 2nd! This agent swaps strategies based on the opponent and tries to maximize it's own reward using a heuristic curve which holds the expected reward high until the deadline is near (known as a 'boulware' negotiation strategy), and no it wasn't inspired by every college student's approach to assignments. 
[Here's](https://github.com/Aa-Aanegola/genius-negotiator) the code!