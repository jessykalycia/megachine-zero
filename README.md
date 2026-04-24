# Megachine Zero

> **Built with [Sophia Forge](https://sophiaforge.com), for [Sophia Forge](https://sophiaforge.com).**
> A [Sophia Foundry](https://sophiafoundry.com) production.

A Mega Man X1-inspired side-scrolling platformer built for Gamejam.js — and a showcase project for the Sophia Forge authoring suite.

Play as **Zero** through MMX-style action: dash, wall-slide, wall-kick, and a 3-tier charge buster.

## Stack

- **Phaser 3** — runtime
- **Tiled** — level data (loaded via `tilemapTiledJSON` + `make.tilemap` + `addTilesetImage`)
- **Sophia Forge** — project authoring (sprites, state machines, levels, items)

## Enemies

- **Walker** — walks in spawn direction
- **Spray Shooter** — stationary, fires on a timer
- **Sentry** — fixed, player-aware
- **Boss** — central `Decide` state routing to melee / ranged / special attacks
