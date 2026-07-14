---
layout: default
title: "How Live Crypto Order Flow Drives Six 3D Battlefields"
description: "Explore how BTC War maps live crypto prices, aggregate trades, market depth, and BUY/SELL pressure into six interactive WebGL battle scenes."
author: blibli
date: 2026-07-14 11:00:00 +0000
permalink: /crypto-order-flow-six-3d-battlefields/
categories: [crypto, data-visualization]
tags: [crypto-order-flow, bitcoin, market-depth, webgl]
image: /assets/screenshots/space.webp
---

# How Live Crypto Order Flow Drives Six 3D Battlefields

Market data is often presented as a chart, a table, or a stream of numbers. BTC War uses a different visual vocabulary: recent trades and order-book pressure become opposing BUY and SELL forces inside a real-time 3D battle simulation.

The visualization currently supports BTC, ETH, BNB, SOL, XRP, TRON, DOGE, ZEC, and ADA spot markets against USDT. The selected market supplies the live price, aggregate trades, and depth data. Those inputs influence army balance, the central objective, reinforcements, and large-order events; they are descriptive signals, not price predictions.

## BTC War: the live order-flow frontline

![Live crypto order flow rendered as the BTC War battlefield]({{ '/assets/screenshots/modern.webp' | relative_url }})

The original BTC War scene translates market pressure into a broad modern battlefield with infantry, armor, aircraft, explosions, and a central BUY or SELL objective. A live killfeed exposes the aggregate trades driving the simulation, while the force bar makes the current imbalance readable at a glance.

## Voxel Siege: block-world armies and dinosaurs

![Voxel Siege with block soldiers, archers, dinosaurs and faction yurts]({{ '/assets/screenshots/voxel.webp' | relative_url }})

Voxel Siege gives the same order flow a block-world interpretation. Melee troops, elevated archers, dinosaurs, yurts, watchtowers, and a fixed central flag create a wide battlefield. The dominant market side controls the flag, while large orders can trigger a travelling thunderstorm led by a glowing high priest.

## Arcane War: swords, crystal magic, and beasts

![Arcane War with swordsmen, mages, crystal magic and opposing castles]({{ '/assets/screenshots/fantasy.webp' | relative_url }})

Arcane War separates close-range swordsmen from ranged mages. Crystal attacks follow visible arcs, multiple mages can merge into a larger caster, and large-order events release illuminated lions or tigers from the faction headquarters. The central crystal marks whether BUY or SELL pressure is leading.

## Medieval Siege: fortresses, cavalry, and catapults

![Medieval Siege with infantry, archers, cavalry, catapults and fortresses]({{ '/assets/screenshots/siege.webp' | relative_url }})

Medieval Siege stages larger armies between walled headquarters. Infantry and cavalry advance through open gates, archers take elevated positions, and catapults respond to major market events. Fortress walls can take damage and recover, so the scene reads as an ongoing siege rather than a static formation.

## Space War: three-dimensional fleet combat

![Space War with bright fleets, planets, shielded bases, lasers and missiles]({{ '/assets/screenshots/space.webp' | relative_url }})

Space War expands the signal into layered fleet combat. Fighters, cruisers, and flagships cross multiple altitude lanes between planet-backed headquarters. Ships exchange narrow laser fire and missiles, some raid hostile territory, damaged craft can return for maintenance, and a charged headquarters tower can produce a chain reaction after a large order.

## Champion Duel: BUY versus SELL

![Champion Duel with BUY and SELL fighters, health bars, combos and finishers]({{ '/assets/screenshots/duel.webp' | relative_url }})

Champion Duel compresses the market conflict into a continuous one-on-one fight. The BUY champion wears green, the SELL champion wears red, and both cycle through combos, blocks, special attacks, and finishers. Health bars recover after a knockout before the next exchange begins.

## One market model, six visual explanations

The battlefields are deliberately different, but the underlying interpretation stays consistent:

1. The latest exchange ticker supplies the displayed market price.
2. Aggregate trades populate the live feed and identify buyer- or seller-initiated executions.
3. Order-book depth contributes to the relative BUY and SELL force.
4. The leading side controls the objective color and label.
5. Unusually large orders can trigger scene-specific events.

This separation matters. Executed order flow describes recent transactions, while market depth describes resting liquidity. Neither guarantees the next price move.

[Browse the canonical six-battlefield gallery](https://btcwar.net/battlefields?utm_source=github-pages&utm_medium=guide&utm_campaign=six-battlefields), or [open BTC War](https://btcwar.net/?utm_source=github-pages&utm_medium=guide&utm_campaign=six-battlefields) to switch scenes with the **BATTLEFIELD** control. For a compact explanation of price, spread, depth, and trade flow, read the [Bitcoin market-data glossary](https://vibewhip.github.io/btc-war/bitcoin-price-market-depth-order-flow/).

BTC War is descriptive and educational. It does not execute trades, provide trading signals, predict prices, or offer financial advice.

— blibli
