# PlusPlusOneGmbH/TD_UvManagedPrefab

**Stars:** 6 | **URL:** https://github.com/PlusPlusOneGmbH/TD_UvManagedPrefab | **Language:** Python

## Overview

UV-managed project prefab/template for TouchDesigner projects. Demonstrates using UV as the project- and dependency-manager for TD with a JIT package mount hack to avoid race conditions.

## What's Inside

- `pyproject.toml` + `uv.lock` — UV-managed dependencies
- `.python-version` — Python version pinning
- `.touchdesigner-version` — TD version pinning
- JIT package folder mounting via `.packagefolder`

## Python Usage

Pure Python project structure. Integrates MonkeyBrain (`uv run mb edit`) for automated TD launching. Can serve as base for TD Python packages publishable to PyPI.

## Relevance

Reference implementation for modern UV-based TD project workflows. Archived but the concepts remain applicable.
