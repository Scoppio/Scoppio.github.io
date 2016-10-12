---
published: true
title: I was challenged on Hearthstone
layout: post
tags: [data-analysis, hearthstone]
categories: [data-anaysis]
---
You could say that I [like playing games](https://steamcommunity.com/id/scoppio/games/?tab=all), and I also like data science, and games usually uses alot of data... you know where it is going.

This is the deal, my brother called me and said **- Lucas, I want to be great at Heartstone, and you can help me with it.**

So... what kind of informations I can come up with? First lets talk about the game and what are its features.

# Hearthstone

A few years back Blizzard created WoW TCG, it was their take on trading card games, and it was amazing! Unfortunatelly they could not compete in the same level as Magic the Gathering, so 3 years ago they released Hearthstone, developed on Unity engine, and it is basically the same game with simplified rules.

Hearthstone is a two players game, and each player has deck composed of 30 cards. Differently from other games, there are no **mana**, **energy** or **resources** cards, instead, the game adds one energy crystal for the player each turn, going from 1 in the first turn up to 10 at the tenth turn (and it stops in 10). Threre are 9 heroes and hundreds of cards, so you can build very different and decks to play with.

Unfortunatelly there is no API for the game, none, null, NA, a hearthstone developer said in august last year that they had plans for it, but nothing so far, so there is no information that I can capture from the company. So what do I do?

First I need to discover what is possible for me to get as information! Let me see:

-   I can try to extrapolate the main decks being used in each season on twitter and checking at the best sites for posting deck builds.
-   Added to it I can extract some information from the finals of the Hearthstone Coups.
-   And finally I can use something like Hearthstone deck tracker to build  weekly reports on his efficiency against each opponent and also extract some information from it.

### So thats the initial plan.

As you can see, most of it is going to be data minning and inferences, data presentation and interpretation, and using it to make better informed decisions, both in deck building as in game play.

I'll eventually post my advances on this project, until then, **keep coding.**