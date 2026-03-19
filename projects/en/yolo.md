# yolo

## One-Line Summary

A cross-platform launcher that provides one entry point for Claude Code, Codex, Gemini, and other AI coding CLIs.

## Problem

When several AI CLIs are used in parallel, the friction usually comes from everything around the model rather than the model itself. Each tool has its own startup flow, authentication path, environment assumptions, and update behavior. None of those differences looks large on its own. Together they make daily switching feel fragmented.

That kind of problem is irritating because it rarely causes a full outage. It just keeps taxing attention. After a while, people spend too much energy getting the tool ready and not enough using it.

## Why This Direction

The easiest move is to wrap each CLI with its own alias or helper script. That works in the short term. Over time, as the tool set grows and environments change, those local patches drift apart.

So I did not continue with "fix each tool a little." I unified the entry layer instead. The goal is not to make every tool identical. The goal is to pull startup and authentication behavior into one stable boundary so the user does not have to remember a separate operating model for every CLI.

## Quality Bar / What I Care About

I care most about consistent cross-platform behavior, smooth authentication flow, and low startup friction.

A good launcher should not require users to keep several different mental models alive at once. It should stabilize the common path and make switching lighter.

## Engineering Judgment

This project reflects a judgment I return to often: many visible tool problems are actually entry-point problems, state inconsistency problems, and cognitive load problems.

Once the entry layer is stable, the surrounding tool ecosystem has a much better chance of feeling coherent.

## Technical Keywords

`Shell` `Python` `CLI launcher` `authentication` `cross-platform`
