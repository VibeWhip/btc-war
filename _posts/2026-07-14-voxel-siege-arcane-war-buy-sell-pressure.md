---
layout: default
title: "Voxel Siege and Arcane War: Visualizing Live Buy and Sell Pressure"
description: "Compare two fantasy-style WebGL scenes that map live crypto price, aggregate trades and market depth into block-world and arcane combat."
author: blibli
date: 2026-07-14 12:05:00 +0000
permalink: /voxel-siege-arcane-war-buy-sell-pressure/
categories: [crypto, data-visualization]
tags: [buy-sell-pressure, voxel-siege, arcane-war, market-depth]
image: /assets/screenshots/fantasy.webp
---

# Voxel Siege and Arcane War: Visualizing Live Buy and Sell Pressure

Buy and sell pressure are abstract descriptions of current market activity. They combine information from completed trades and visible liquidity, but they do not tell a story by themselves. Voxel Siege and Arcane War use two different fantasy languages to make that changing balance easier to notice without presenting it as a price prediction.

Both scenes receive the same selected Binance Spot inputs used elsewhere in BTC War: a live ticker, recent aggregate trades, and order-book depth. The leading side can control the central marker, while reinforcement levels and major events respond to the current market state.

## Voxel Siege: block-world pressure and a fixed objective

![Voxel Siege with block soldiers, archers, dinosaurs, yurts and a central flag]({{ '/assets/screenshots/voxel.webp' | relative_url }})

Voxel Siege places red and green armies between distant yurt-style headquarters. The central flag never moves. Its color and BUY or SELL label show which side currently has the advantage, and a soldier from that faction remains beside the pole.

Different professions use distinct silhouettes. Melee troops carry close-range weapons, archers fire higher cinematic arcs, and their smaller profession markers make roles readable without overwhelming the characters. Soldiers can advance through the center or use flanking paths instead of forming one permanent pile.

Dinosaurs add an independent threat layer. They can pursue soldiers or attack one another, but their chase logic is bounded: if a target escapes for long enough, the dinosaur selects another target. The population is capped so the scene remains readable. A soldier being chased can retreat directly away rather than waiting passively for contact.

When a sufficiently large market event occurs, a glowing high priest can leave the headquarters. The priest's storm travels visibly toward the opposing camp, remains active for a limited interval, and disappears before entering the headquarters itself. This makes the event's origin, path, and duration understandable.

## Arcane War: close combat and arcing crystal magic

![Arcane War with swordsmen, mages, crystal attacks and opposing headquarters]({{ '/assets/screenshots/fantasy.webp' | relative_url }})

Arcane War separates close-range and ranged behavior more sharply. Swordsmen move quickly toward enemies and resolve attacks at contact. Mages launch crystal projectiles from their own positions; the projectile rises first and then falls toward its target instead of appearing from the sky.

Some mages can take elevated positions. That improves their firing view but also makes them more exposed to enemy ranged units. Several mages may merge through a visible combination sequence into a larger archmage. The archmage has stronger attacks but a strict three-attack limit, keeping the special form temporary.

The middle crystal acts as the dominance marker. It displays BUY or SELL, changes faction color, emits light, and carries electrical activity. Large market events can release a glowing lion or tiger from the headquarters. The beast crosses the battlefield, attacks hostile units, uses a roar skill, and returns after its assault instead of remaining indefinitely.

## What the scenes preserve

Despite their different styles, both scenes follow the same interpretation rules:

- attacks originate from visible actors;
- current advantage changes the central objective;
- ordinary combat continues without inventing a forecast;
- major events require stronger market input;
- faction color stays consistent between BUY and SELL;
- pressure describes present conditions, not future price direction.

That last boundary matters. Visible bids and asks can be cancelled, and recent aggressive trades can be followed by activity in the opposite direction. The scenes help a viewer notice change; they do not remove market uncertainty.

[Open BTC War](https://btcwar.net/?utm_source=github-pages&utm_medium=guide&utm_campaign=voxel-arcane) to compare Voxel Siege and Arcane War with live data. Read [how all six battlefields use one market model](https://vibewhip.github.io/btc-war/crypto-order-flow-six-3d-battlefields/) for the wider design.

BTC War is descriptive and educational. It does not provide trading signals, execute trades, or offer financial advice.

— blibli
