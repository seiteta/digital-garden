---
title: Metrics and counter-metrics
tags:
  - seedling
  - product management
---

If it's true that "when a measure becomes a target, it ceases to be a good measure", how we can use North Star Metrics (NSM)?

## Short memory

To aligned Scaleway's AI Tribe in 2026, I choose one NSM for each of our squads.
The first meeting I shared those NSMs, a lead engineer cleverly mentions [Goodhart’s law](adages#goodharts-law).
I've collected it in my [[adages]] list like last week, but totally forgot it when I was designing my super smart metrics.

This led me to this question:
> Can North Star Metrics still be useful if we remember Goodhart’s law?

aka

> Can a measure becomes a target and still be a good measure?

## Counter-metrics

In essence, Goodhart's law is about the human tendency to game the system when we have an incentive to do so.

Let says your NSM is usage.
Like "how many time users did X".
There are so many ways to make X goes up. So many bad ways in particular.
You could do a 90% discount or add a CTA everywhere.
Pay for a national billboard campaign.
Remove every feature except X.
You get the idea.

For a target to be a good measure, it should have counter-metrics.
Counter-metrics exist to make NSM hard to game.
By keeping an eye on margin, reliability and retention to your usage NSM, you start to have a strong metrics, aligned with your long-term goals.
And there are no bad ways to grow like this.
