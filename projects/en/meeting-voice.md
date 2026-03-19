# meeting-voice

## One-Line Summary

A real-time voice translation app for cross-language communication, designed for desktop and browser entry points.

## Problem

The most underestimated part of real-time translation is not whether the model can translate. It is whether the full chain holds up when it matters. Where does audio come from? How do devices switch? How do different meeting surfaces connect? Can latency stay low enough? How many actions does the user need before the system starts working?

Many products already look "real-time" in a demo. The moment they enter an actual meeting, background noise, device switching, and setup friction start pulling the experience apart.

## Why This Direction

You can wrap offline transcription or a single API and get a presentable prototype quickly. But that path usually leaves the hardest part to the user. The system handles translation. The user handles everything required to make translation usable.

So I did not focus only on model access. I built around the live audio chain, multiple entry points, and a consistent operating path. The first step is to stabilize the setting itself. Only then does translation quality become meaningful at product level.

## Quality Bar / What I Care About

I care most about low latency, stable device switching, natural entry paths, and a consistent experience across platforms.

A strong result is not "it works under controlled conditions." It is that once a meeting starts, users feel safe relying on it without wondering whether the chain will break a minute later.

## Engineering Judgment

This project reflects a view I have about real-time products: the hard part is not whether a feature exists. It is whether the full chain is stable enough for people to trust during critical moments.

In real-time systems, the limit is often not the model. It is whether the surrounding complexity has been absorbed.

## Technical Keywords

`TypeScript` `desktop app` `browser extension` `real-time translation` `audio routing`
