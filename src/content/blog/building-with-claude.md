---
title: "Building ASTRA with Claude"
date: 2026-03-19
excerpt: "What happens when you pair a game designer's vision with an AI that can actually write code? Total creative freedom."
tag: "Dev Log"
---

I built ASTRA — a sci-fi roguelike dungeon crawler — in a couple of days. Not because I'm that fast, but because I had help. I built it with Claude.

This isn't a sponsored post or a tutorial. It's a reflection on what it actually feels like to build software this way.

## The shift

I've been programming for a long time. I know what it's like to have an idea at 11pm, get excited, and then spend three hours fighting with boilerplate before you even get to the interesting part. By the time the scaffolding is done, the spark is gone.

With Claude, that friction disappears. I'd describe what I wanted — "add a dialog system where NPCs can present multiple choice responses" — and minutes later it was there. Working. Integrated. Ready to play with.

The loop changed from *think, implement, debug, implement, debug* to *think, describe, iterate*. That's a fundamentally different creative experience.

## Creative freedom

Here's what really stood out: I stopped worrying about implementation and started thinking purely about design. What should the hunger system feel like? How should rooms reveal themselves when you walk through a door? What information does the player actually need on screen?

These are the questions that matter when you're making a game. The implementation specifics — the data structures, the rendering logic, the input handling — those are important, but they're not where the magic happens. They're the cost of doing business.

Claude handles that cost. And that frees you up to be a designer, not just a programmer.

I'd have an idea, describe it, see it running, and immediately know whether it was fun or not. That feedback loop is incredibly tight. Ideas that would normally sit in a backlog for weeks got tested in minutes.

## What works

For my use case — a solo developer prototyping a game — this works brilliantly. The kind of code ASTRA needs is well-structured, self-contained, and iterative. Add a feature, test it, refine it, move on. Claude thrives in that environment.

The terminal renderer, the FOV system, the HUD layout, the dialog trees — all of these were collaborative. I'd describe the behavior I wanted, Claude would implement it, and then we'd go back and forth refining until it felt right.

It's not that different from working with another programmer, except this one never gets tired and has read every C++ reference manual ever written.

## The honest bit

This isn't magic. You still need to know what you want. You still need to understand the code well enough to guide the direction. Claude is a force multiplier, not a replacement for knowing what you're doing.

But if you do know what you're doing — if you have a clear vision and can articulate it — the speed at which you can bring ideas to life is something I haven't experienced before.

## What this means

I think we're at the beginning of a shift in how software gets built. Not the death of programming — that's a lazy take. More like the death of the gap between having an idea and seeing it run. The tools are getting out of the way.

For me, that means more time designing, more time playing, more time iterating on what makes a game actually fun. Less time fighting with syntax and boilerplate.

ASTRA exists because of that shift. And I'm just getting started.

Check out [ASTRA's website](https://jeff.lookingforteam.com/astra) or grab the [latest release (v0.2.0)](https://github.com/obscuren/astra/releases/tag/v0.2.0) on GitHub.
