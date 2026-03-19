# timing-entries-sync

## One-Line Summary

A CLI tool that keeps Timing App records in sync with Google Calendar.

## Problem

Automatic time tracking can capture a lot of useful data. But if those records never make it into calendar and planning systems, they remain a log of what happened instead of becoming part of reflection and scheduling.

The hard part also does not begin with the first import. It begins with long-term sync: handling duplicates, detecting updates, recovering from errors, and keeping the data trustworthy as time goes on.

## Why This Direction

The most direct path is a one-off script that pushes records across and stops there. That solves connectivity. It does not solve long-term order. Once you use the system for real, duplicate writes, change propagation, and recovery all start to matter.

So I did not leave it at one-time transfer. I turned it into an installable, schedulable, traceable sync tool. The premise that matters most is whether it can keep running cleanly over time. Without that, the sync itself is not worth much.

## Quality Bar / What I Care About

I care most about idempotency, change detection, and long-term stability.

A good sync tool should not require regular manual repair. The ideal state is simple: after it has been running for a long time, the data is still trustworthy instead of gradually turning into a mess.

## Engineering Judgment

This project reflects a judgment I have about sync systems in general: connecting two systems is usually the easy part. The hard part is preserving trust in the data once the time horizon gets long.

Many sync problems are not connectivity problems. They are long-term order problems.

## Technical Keywords

`Python` `Google Calendar` `SQLite` `CLI` `sync` `automation`
