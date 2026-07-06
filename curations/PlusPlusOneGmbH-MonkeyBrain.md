# PlusPlusOneGmbH/MonkeyBrain

**Stars:** 1 | **URL:** https://github.com/PlusPlusOneGmbH/MonkeyBrain | **Language:** Python

## Overview

Command-line utility for managing TouchDesigner from UV. Automated TD launcher with version detection and project configuration via `pyproject.toml`. Windows only.

## What's Inside

- CLI commands: `mb edit` (launch TD), `mb designer` (production mode), `mb player` (TouchPlayer), `mb init` (project setup)
- Auto-detects best installed TD version
- `.env` file mounting before TD starts
- VS Code integration setup (`mb init.code`)

## Python Usage

Pure Python CLI tool using UV's task runner. Configures TD Python environment paths and TDPyEnvManager context automatically.

## Relevance

Essential companion for UV-based TD projects. Simplifies TD version management and project launching from the command line.
