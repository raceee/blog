---
title: "WoW II: A Techinical Love Letter and a New Era of the Genre"
date: 2021-10-21T01:20:13-06:00
draft: false
---
## Introduction

In this post we will be discussing the MMORPG (Massive Multiplayer Online Role Playing Game) specifically we will be revamping World of Warcraft (WoW) published by Activision-Blizzard (market cap $75B). Recently, the development team for World of Warcraft and Activision-Blizzard as a whole have been servered multiple court cases on the grounds of substantiated sexual assault and harrassment of female employees. This, and years of mounting frustration with gameplay, has inspired a four month blitzkrieg-esque retreat from WoW to MMORPG’s published by Square Enix and Amazon Games Studios, demoting World of Warcraft from the most played MMORPG for the first time since 2004. The change in power plunged Activision-Blizzard’s stock price 16%.
Entertainment comes and goes, but the World of Warcraft community has lost the place where their group of friends all over the world come to spend time together. Understandably, lots of lingering players are talking about how to bring it back, and so will we. 
 
### Thesis 
WoW  is a “static” game that gives players the freedom to choose how they want to play the game. In 2004 this was a great feature. Over time, the combination of freedom of choice, easily obtainable information/guides through the internet and game static-ness has bred these issues:
Static MMORPG’s have outdated business models which force developers to nickel and dime players, and force developers to create monetizable content and not solve inundated problems.
Static MMORPG’s emphasize the inequalities between player choices and drive competitive players to optimize the fun out of the game.
Static MMORPG’s must have inconvenient systems in the game to extend play time resulting in a fragile suspension of disbelief towards the game generally.
The evolution for WoW (and MMORPG’s generally) must come by changing the game from static to dynamic.  Which we will do using machine learning. Changing to a dynamic system also propagates changes to gameplay that we will discuss as well.

# Methodology
Our goal with the methodology is to use the entire game as a whole and not change anything about the map, game engine, or do any major redesign of any of the classes. We will also want to recycle all of the unused content that has been introduced to the game for the last 18 years in a meaningful way, really putting the “world” back into ”World” of Warcraft.

## Non wow player crash course
Picture of the starting screen so they get the concept of the player choice thing
Maybe a quick run through of the typical gameplay loop

## A Creative Reintroduction
Atop of the stats that gear gives you[image of a piece of gear], we will introduce what we will call a “Elemental Stat Line”. This “Elemental Stat Line” will act as the vector space that our dynamic game will look at to determine how to evolve and kill the community. The elements represented in this vector space should be familiar to players they are:
Fire
Ice
Holy
Shadow
Elemental (yea i know fire and ice are elements but this is more like lightning damage, nature damage, poison damage)
Physical
Ranged
Class specifications and gear now have buffs in these areas. If you collect only fire gear you will do more fire damage. You get gear from all previous dungeons, raids, and questlines retrofitted with modern difficulty.

“LATEX MATH”

In our simulation we represent each player as a vector and the summation of vectors as a raid. For our simulation we give half of the raids a bias to a specific element in this vector space trying to represent some type of “meta”.


## Machine Learning

Here is a visualization of the raids and their bias’.

[picture of the graph]

The goal here is to try to get the boss to recognize that there is a large meta going on and take on a defense that would make it win. We do this with the KMeans clustering algorithm, we calculate the centroids of each group and then come up with a “concentration” score that takes into account how many of the raids were in each group and how far away they were from their centroid.

When the boss develops defense according to the meta the boss wins more often. Great! The boss is now intelligent, it studies the players much like how the players have studied it. The game is now in motion and the meta is being defeated. Now players don’t have to worry about what classes are the best at their specific roles, instead players must make sure that they have gear that counters the bosses current meta. To mean, maybe a specific warrior class does not have good ice damage, but this warrior can still go out to cold areas of the world and gather gear from those areas and obtain good ice damage stat. With the boss fitting to the meta every week, or day, the game rewards players that make efforts to beat the boss by adventuring throughout the world, crafting legendary items, and completing quest chains, not engineering the fun out of the game by doing meta analysis. Maybe shaman is not good for today’s boss, but maybe the AI that controls the boss's stat distribution favors the shaman tomorrow, so choosing to be a shaman is a decision you can be confident is valuable. With this hypothetical, we also see that this boss can relieve the stress of meticulous class balance. Developers can shoot for a neighborhood of performance between classes and know that the boss will eventually validate all classes.

## Dynamic Implications
*For this section and onward machine learning is not talked about but the consequences our machine learning algorithm are talked about*

Now that the boss is learning to beat you, a raid team or dungeon group must prepare quickly to make a good attempt to kill the bosses.  Admittedly, this means that players will have to put forth more effort in order to progress. This can be a problem and highlights a main issue that static MMORPG’s had that is emphasized in dynamic MMORPG’s:

MMORPG’s take a lot of time to play. 

The opportunity cost of the time can break the players suspension of disbelief and make the game unenjoyable.







