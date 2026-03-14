---
title: "Dev Log #001 — The Road So Far"
date: 2026-03-07
excerpt: "From a Unity prototype in 2019 to Unreal Engine 5 — the full timeline of how Grid Games got to where we are today."
tag: "Dev Log"
---

Building a game studio doesn't happen overnight. This is the story of how Grid Games went from a scrappy prototype to where we are today — told through the commits.

## The prototype — April 2019

It all started with GridOnline-Proto, our first Unity prototype. The second commit in the repo says it all:

> "Grid was born."

*April 3rd, 2019.* We were baking city scenes, pushing assets — wall and tower models, terrain work, lighting. It was rough, it was exciting, and it was the first time the idea felt real. Before that, Grid Games was just something Joey and I talked about. After that commit, it was something we were building.

## Going serious with Unity — October 2020

After the prototype proved the concept, we started fresh. October 20th, 2020 — the initial commit of GridOnline-Deux, our proper Unity project. Within days we were moving fast: refactoring classes, building login UI, implementing character creation and selection, organizing networking components. This was no longer a prototype. This was the real thing.

## Rolling our own networking — Nucleus

Early on we realized Unity's built-in networking wasn't going to cut it for what we had in mind. So we built Nucleus — our own networking layer in C#. The repo actually predates the prototype, going back to March 2019. We knew multiplayer was going to be the core of the experience, so we invested in getting the foundation right before anything else.

## 2020 and the uncertainty

Then COVID hit. We were a small team — just the two of us — and the uncertainty made it impossible to commit to hiring. We kept building, kept iterating, but we weren't ready to scale. In hindsight, that constraint forced us to stay lean and make every decision count. But it was a frustrating period. The ambition was there, the world wasn't cooperating.

## The move to Unreal Engine 5 — October 2022

By late 2022, we made the call: move to Unreal Engine 5. October 10th, 2022 — the first commit in the [Redacted Name] repository. [Redacted Name] Online. A fresh start on a new engine, with everything we'd learned from the Unity years.

The decision wasn't easy. We had years of work in Unity. But UE5 offered what we needed for the long term — the rendering pipeline, the tooling, the scalability. Sometimes you have to throw away working code to build something better.

Fast forward to today and [Redacted Name] has grown into a proper production: player systems, combat, team mechanics, minimaps, level progression. The commit history tells the story of a game that's actually taking shape.

## What's next

We're deep in development. The next dev logs will be more focused — specific systems, technical deep dives, design decisions. Less history, more building.

Stay tuned.
