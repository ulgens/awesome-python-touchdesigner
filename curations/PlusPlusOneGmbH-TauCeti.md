# PlusPlusOneGmbH/TauCeti

**Stars:** 29 | **URL:** https://github.com/PlusPlusOneGmbH/TauCeti | **Language:** Python

## Overview

Highly customisable, setup-agnostic preset management and tweening system for TouchDesigner. Includes Tweener engine, PresetManager, Cuelist, ChopMapper, and TweenCHOP wrapper.

## What's Inside

- **Tweener** — Programmatic creation and management of tweens (AbsoluteTween, RelativeTween, CreateTween). Supports fade, start-snap, end-snap modes, async await via `.Resolve()`, pause/resume/stop/reset/reverse.
- **PresetManager** — Store/recall arbitrary parameter states. DataRepository for separation of data and logic. Fademodes (startsnap, endsnap, fade), preloading, push, extensive Python API.
- **Cuelist** — Structured cue recalling
- **ChopMapper** — Map CHOP channels to preset recalls
- **TweenCHOP** — Wrapper around Tweener for channel generation

## Python Usage

100% Python. PIP-installable (`pip install tdpTauCeti`). Type-safe with `TYPE_CHECKING` typing exports. Module exposes `ToxFile` members for referencing `.tox` files. Uses SemVer.

## Relevance

Production-ready preset system for TD performance and installation workflows. Active development (209 commits, v5.1.13).
