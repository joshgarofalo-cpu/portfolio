# Orbit

A personal life management web app that turns habits, goals, and tasks into a Destiny 2-style character sheet, themed with real game assets from the Bungie API.

**Live:** [orbit-kappa-five.vercel.app](https://orbit-kappa-five.vercel.app)

## The problem

<!-- Josh: in a sentence or two, why did you want this? What wasn't working about ordinary to-do lists or habit trackers? -->

Orbit started as my 15-hour personal project in FIN 411 Advanced Financial Modeling at BYU-Idaho.

## What I built

- **Six life attributes** tracked like RPG stats, shown on a character sheet with a radar chart
- **Bounties** (tasks), **Rituals** (recurring habits with streaks), and **Quests** (multi-step goals)
- **Triumphs and Seals:** achievements that unlock titles you can equip
- **The Tower:** a reward shop where earned currency buys rewards I define for myself
- **Destiny 2 integration:** the app pulls my in-game emblem to theme the page, and shows live in-game milestones
- **Cross-device sync:** works offline first, then syncs between phone and desktop with sign-in by email link

Every completed task is recorded in an append-only log, and all progress (XP, streaks, achievements) is calculated from that log, much like a ledger.

## Tools

Claude Code (AI-assisted development), React, TypeScript, Tailwind CSS, Supabase (database, sign-in, and sync), Bungie API, Vercel (hosting)

## Results

- Scored 100/100 on the FIN 411 personal project
- Deployed and live at [orbit-kappa-five.vercel.app](https://orbit-kappa-five.vercel.app)

## What I learned

<!-- Josh: two or three things this taught you. For example, working with an outside API, directing an AI coding tool, or designing a system before building it. -->

## How to run it or view it

Open the [live site](https://orbit-kappa-five.vercel.app). The source code is private for now.

<!-- Screenshots go in images/ and are linked here. -->
