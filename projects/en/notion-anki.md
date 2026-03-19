# notion-anki

## One-Line Summary

A bidirectional sync tool between Notion notes and Anki flashcards.

## Problem

A common learning flow starts in Notion and ends in Anki. The issue is that once both sides keep changing, manual copying distorts structure very quickly. The note system and the review system still appear connected, but they have already started drifting apart.

At first that feels like sync overhead. Over time it becomes knowledge drift. Eventually it gets hard to tell whether a card still corresponds to the current source material at all.

## Why This Direction

The simplest option is one-way export. That keeps the barrier low. But as soon as both systems are in real use, one-way export runs into inconsistency, overwrites, and conflict handling.

So I did not stop at export. I focused on bidirectional sync and the edge cases around it. The goal is not just to move content across. It is to preserve a relationship between both sides that remains understandable and recoverable over time.

## Quality Bar / What I Care About

I care most about preserving structure, having a clear strategy when both sides change, and being able to explain what happened before and after each sync.

A good sync system should not hide anomalies. It should make it clear what changed, why it changed, and how recovery works when something goes wrong.

## Engineering Judgment

This project reflects a judgment I hold about sync tools in general: the hard part is never just connecting two APIs. The hard part is keeping consistency, recoverability, and interpretability at the edges.

Sync is not only about moving data. It is about protecting relationships.

## Technical Keywords

`Python` `Notion API` `AnkiConnect` `bidirectional sync` `conflict resolution`
