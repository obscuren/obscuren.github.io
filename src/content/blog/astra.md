---
title: "ASTRA — A Sci-Fi Roguelike in the Terminal"
date: 2026-03-16
excerpt: "I built a roguelike dungeon crawler that runs in your terminal. ASCII graphics, procedural maps, and a sci-fi setting. Written in C++ together with Claude."
tag: "Side Project"
---

Sometimes I just need to build something for fun. No roadmap, no stakeholders, no sprint planning. Just me and the compiler. That's ASTRA.

![ASTRA — talking to Tessa the Station Keeper](/images/astra.png)

## What is it?

ASTRA is a sci-fi roguelike dungeon crawler written in C++ that runs directly in your terminal. ASCII graphics, procedural map generation, field-of-view, and a HUD that would feel at home in an 80s space sim. You play as a commander docked at a space station called The Heavens Above, orbiting Jupiter, on a journey to Sagittarius A*.

This project went from zero to a playable demo in a couple of days.

## Why ASCII?

There's something deeply satisfying about building a game where `@` is your character, `.` is the floor, and `#` is a wall. It strips away everything except the mechanics. No shaders to debug, no asset pipeline, no textures. Just characters on a grid.

It's also a constraint that forces creativity. When your entire visual palette is the ASCII table, every character choice matters. The starfield backdrop uses different characters at varying densities — deterministic and infinite, so no matter where you go, the stars are always there.

## How it plays

You navigate with WASD, arrow keys or vim keys (of course). The map reveals itself as you move — step through a doorway and the whole room lights up. Explored areas fade to blue when you move away. Everything you haven't seen yet is just the void of space.

The HUD is dense in the best way. Stats, HP/XP bars, a tabbed side panel for messages, inventory, equipment, and ship status. It's the kind of information density that roguelike players live for. Everything you need, nothing you don't.

There's also a dialog system — NPCs can talk to you, offer quests, give directions. It's early, but the bones are there.

## Why build this?

I run a game studio. I spend my days thinking about game design, player systems, and what makes things fun. ASTRA is where I get to test ideas without any stakes. Want to try a new hunger mechanic? Throw it in. Curious about how FOV should feel in a space station? Build it and see.

It's also just a good time. There's a purity to building games in the terminal that takes me back to when I first started programming. Before engines, before frameworks — just output to a screen and see what happens.

## What's next

ASTRA is a side project and will stay that way — something I hack on when the mood strikes. But there's plenty I want to add: combat, NPCs with real dialogue trees, an inventory system, ship mechanics, and procedural station layouts.

The source is up on [GitHub](https://github.com/obscuren/astra) if you want to poke around or build it yourself.
