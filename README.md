<!--lint disable awesome-github-->

# Awesome Python + TouchDesigner [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of Python-focused resources for [TouchDesigner](https://derivative.ca), the node-based visual programming environment for real-time interactive multimedia.

Resources that bring Python and TouchDesigner together - whether extending TD with Python scripts, driving TD from Python externally, or bridging both worlds.

> **Early stage notice:** This list was initially compiled with the help of LLM models. It's far from comprehensive and may contain inaccuracies. Contributions are welcome - open a PR if you see anything to improve.

## Contents

- [Official Resources](#official-resources)
- [Learning Python in TouchDesigner](#learning-python-in-touchdesigner)
  - [Courses](#courses)
  - [Tutorials & Articles](#tutorials--articles)
  - [Cheat Sheets & References](#cheat-sheets--references)
  - [YouTube Channels & Educators](#youtube-channels--educators)
- [Python Libraries, Plugins & Tools](#python-libraries-plugins--tools)
   - [MCP Servers](#mcp-servers)
   - [Headless & Engine Integration](#headless--engine-integration)
   - [Machine Learning & AI](#machine-learning--ai)
   - [VJ & Performance](#vj--performance)
   - [Utilities & Workflow](#utilities--workflow)
- [Community](#community)
- [Books](#books)
- [Other Similar Lists](#other-similar-lists)

---

## Official Resources

- [TouchDesigner Python API Documentation](https://docs.derivative.ca/Python) - Official reference for all Python classes, methods, and members in TD.
- [Python Environment Manager (TDPyEnvManager)](https://derivative.ca/community-post/tutorial/touchdesigner-python-environment-manager-basics/73693) - New tool for managing Python environments inside TD (2025+).
- [Custom Operators (C++/Python)](https://docs.derivative.ca/Custom_Operators) - Guide for writing custom operators with Python bindings.

## Learning Python in TouchDesigner

### Courses

- [The NODE Institute - Python in TouchDesigner](https://thenodeinstitute.org/courses/ss25-td-python-in-touchdesigner/) - Professional course by Daniel Molnar covering Python fundamentals through TD scripting, expressions, automation, and external libraries.
- [Interactive & Immersive HQ - Python 101 for TouchDesigner](https://interactiveimmersive.io) - Dedicated Python course for TD beginners (part of HQ PRO subscription).
- [Music Hackspace - TouchDesigner Courses](https://musichackspace.org/touchdesigner) - 46 courses covering audio-reactive visuals, sensors, TDAbleton, and more with Python-driven workflows.

### Tutorials & Articles

- [Matthew Ragan - Python in TouchDesigner](https://matthewragan.com/teaching-resources/touchdesigner/python-in-touchdesigner/) - Comprehensive multi-part series covering printing, variables, logic, data structures, classes, loops, modules, and extensions.
- [Interactive & Immersive HQ - Useful Python Libraries for TD](https://interactiveimmersive.io/blog/python/useful-python-libraries-for-touchdesigner-beginners/) - Guide to leveraging Python's standard library and third-party packages inside TD.
- [Akira Nakayasu - TouchDesigner + Python Lectures](https://lecture.nakayasu.com/en/docs/touchdesigner/python/) - Fundamentals of Python integration in TD for Windows and macOS.
- [rvirmoors - Creative Coding: TouchDesigner and Python](https://rvirmoors.github.io/ccia/touchdesigner-and-python/) - Practical intro to processing data and logic with Python exec DATs.
- [SudoMagic - Python in TD Style Guide](https://td-style.guide/docs/SM-guide/python-in-td) - Standardized practices for modules, extensions, auto-complete, and doc strings.
- [Matthew Ragan - Python and the Subprocess Module](https://matthewragan.com/2019/08/14/touchdesigner-python-and-the-subprocess-module/) - Running external processes from TD with Python.

### Cheat Sheets & References

- [Interactive & Immersive HQ - TD Python Cheat Sheet](https://interactiveimmersive.io/blog/python/python-cheat-sheet-for-touchdesigner-developers/) - Curated TD-specific Python tricks, tips, and methods.
- [Aalto New Media - TouchDesigner Tutorials](https://learn.newmedia.dog/tutorials/touchdesigner/) - Audio analysis, Kinect Azure, and text formatting with Python examples.

### YouTube Channels & Educators

- [bileam tschepe (elekktronaut)](https://www.youtube.com/@elekktronaut) - 66K+ subscribers. Beginner courses, audio-reactive tutorials, TDAbleton integration. Heavy Python/expression usage.
- [Matthew Ragan](https://www.youtube.com/@raganmd) - 14.5K subscribers. In-depth Python scripting, instancing, and component building.
- [Function Store (Daniel Molnar)](https://www.youtube.com/@FunctionStore) - 6.5K subscribers. Python tools, POPs, workflow hacks. Patreon: [function_store](https://www.patreon.com/c/function_store/posts).
- [exsstas](https://www.youtube.com/@exsstas/videos) - Glitch, pixel sorting, data moshing tutorials with Python-driven effects.
- [Interactive & Immersive HQ](https://www.youtube.com/@InteractiveImmersiveHQ) - Official channel with Python-centric tutorials and cheat sheets.

## Python Libraries, Plugins & Tools

### MCP Servers

- [touchdesigner-mcp](https://github.com/8beeeaaat/touchdesigner-mcp) (368 ★) - Most popular MCP server for TD. Bridges AI agents with TD via Model Context Protocol. Create/delete nodes, wire connections, set parameters, execute Python scripts. Node.js/TypeScript.
- [touchdesigner-mcp](https://github.com/mrinalghosh/touchdesigner-mcp) - Pure Python MCP server using `uv`. Architecture: Claude → stdio → Python MCP → HTTP POST → Web Server DAT → `td.run()`. Ships as `.mcpb` bundle for Claude Desktop.
- [touch-mcp](https://github.com/benoitliard/touch-mcp) (3 ★) - Python WebSocket bridge for live TD control. Persistent connection with tools for nodes, parameters, connections, scripting, and rendering.
- [touchdesigner-mcp-server](https://github.com/bottobot/touchdesigner-mcp-server) (67 ★) - Comprehensive TD documentation MCP server. 661 operators, 14 tutorials, 214 Python API classes, 21 MCP tools. Version-aware search. Node.js. `npm install -g @bottobot/td-mcp`.

### Headless & Engine Integration

- [TouchPy](https://pypi.org/project/touchpy/) - High-performance Python toolset for working with TouchDesigner components headlessly via the TouchEngine SDK. GPU-accelerated data exchange (CUDA/Vulkan) for TOPs, CHOPs, DATs, and parameters. Windows only.
- [TouchEngine-UE](https://github.com/TouchDesigner/TouchEngine-UE) - Load TD components inside Unreal Engine. Python-driven API for real-time data exchange.

### Machine Learning & AI

- [mediapipe-touchdesigner](https://github.com/torinmb/mediapipe-touchdesigner) - GPU-accelerated MediaPipe plugin (2.4K ★). Hand/face/pose tracking with Python-friendly output.
- [TDDepthAnything](https://github.com/TouchDesigner/TDDepthAnything) - Depth Anything V2 via Hugging Face + TD's Thread Manager and Python Environment Manager.
- [TDNeuron](https://github.com/akashmistry/TDNeuron) - Neural network inference inside TD. Python-driven ML model loading and execution.
- [TDYolo](https://github.com/akashmistry/TDYolo) - YOLO object detection integrated into TouchDesigner using Python.
- [StreamDiffusionTD](https://github.com/StreamDiffusionTD/StreamDiffusionTD) - Real-time stable diffusion within TD using Python.
- [TouchDiffusion](https://github.com/Christopher-McGinnis/TouchDiffusion) - Stable Diffusion image generation with Python control in TD.

<!--lint disable double-link-->

### VJ & Performance

- [ok-vj/okVJ-Shared](https://github.com/ok-vj/okVJ-Shared) - Modular VJ control surface (67 ★). Python expression-based control system with knobs, XY pads, step sequencer, audio analysis, MIDI mapping.
- [TDAbleton](https://docs.derivative.ca/TDAbleton) - Link Ableton Live and TD. Python-driven clip triggering, parameter mapping, transport control.
- [dylanroscover/TDComponents](https://github.com/dylanroscover/TDComponents) - Polished reusable .tox components (98 ★). Chop Recorder, Color Curves, Optimeister, Masker, Playback, all Python-driven.

### Utilities & Workflow

- [FunctionStore_tools](https://github.com/function-store/FunctionStore_tools) - Collection of TD workflow hacks and utilities by Daniel Molnar. Seamlessly integrates with TD UX. Python-based.
- [Richard-Burns/Palette-Tools](https://github.com/Richard-Burns/Palette-Tools) - Palette-ready utilities (34 ★): BlockGlitch, SimpleBloom, UIKit, etc. Python-backed UI and logic.
- [td-completes-me](https://github.com/picturesbyrobots/td-completes-me) - VS Code autocomplete extension for TD Python API.
- [raganmd/touchdesigner-roboCopy](https://github.com/raganmd/touchdesigner-roboCopy) - Python helper for syncing media files between machines.
- [SudoMagicCode/td-manual-release-builder-template](https://github.com/SudoMagicCode/td-manual-release-builder-template) - Template for sharing TD components with Python-based build/release automation.
- [Gianluca-Colia/CustomFamilies](https://github.com/Gianluca-Colia/CustomFamilies) - TD plugin to create/manage/save/export custom operator families. Python-based.
- [TouchDesigner/CustomOperatorSamples](https://github.com/TouchDesigner/CustomOperatorSamples) - Official C++ custom operator samples (120 ★). Python bindings for CHOPs, SOPs, TOPs, DATs.
- [j19950310/TouchDesignerNodeAgentSkills](https://github.com/j19950310/TouchDesignerNodeAgentSkills) - AI agent skill for TD that queries Python API docs and class references.
- [PlusPlusOneGmbH/MonkeyBrain](https://github.com/PlusPlusOneGmbH/MonkeyBrain) (1 ★) - Automated TD launcher CLI via UV. Commands for edit/player/production modes. Windows only. Pairs with TD_UvManagedPrefab.
- [PlusPlusOneGmbH/TauCeti](https://github.com/PlusPlusOneGmbH/TauCeti) (29 ★) - Production-ready preset management and tweening system. Tweener engine, PresetManager, Cuelist, ChopMapper. PIP-installable (`tdpTauCeti`).
- [PlusPlusOneGmbH/TD_UvManagedPrefab](https://github.com/PlusPlusOneGmbH/TD_UvManagedPrefab) (6 ★) - UV-managed project prefab for TD with pyproject.toml, uv.lock, and JIT package folder mounting.
- [blob-cc/touchdesigner-starter](https://github.com/blob-cc/touchdesigner-starter) - Starter template for TD projects with Python project structure.

## Community

- [TouchDesigner Forum](https://forum.derivative.ca) - Official community with active Python scripting section.
- [TouchDesigner Discord](https://discord.gg/touchdesigner) - Real-time chat, Python help, project sharing.
- [/r/TouchDesigner](https://www.reddit.com/r/TouchDesigner/) - Reddit community for TD discussion and support.
- [TD Python Scripting Group](https://www.facebook.com/groups/TouchDesignerPython/) - Facebook group focused on Python scripting in TD.
- [Interactive & Immersive HQ PRO](https://interactiveimmersive.io/lp/hq-pro-full-trial/) - Subscription with 200+ hours of training, custom tools, and private community.

## Books

- [*Generative Design: Visualize, Program, and Create with Processing*](https://generative-gestaltung.de) - Benedikt Groß, Julia Laub, Claudius Lazzeroni. TD port available at [TouchDesigner/GenerativeDesign](https://github.com/TouchDesigner/GenerativeDesign). Heavy Python usage.
- [*Introduction to TouchDesigner*](https://matthewragan.com/teaching-resources/touchdesigner/) - Matthew Ragan's extensive online textbook. Python-focused chapters throughout.

## Other Similar Lists

Detailed summaries of each collection at [curations/](curations/).

- [TouchDesigner/GenerativeDesign](https://github.com/TouchDesigner/GenerativeDesign) (190 ★) - *Generative Design* book examples ported to TD. Python-heavy.
- [monkeymonk/awesome-touchdesigner](https://github.com/monkeymonk/awesome-touchdesigner) (149 ★) - Most comprehensive TD resource list. Includes Python cheat sheets.
- [TouchDesigner/CustomOperatorSamples](https://github.com/TouchDesigner/CustomOperatorSamples) (120 ★) - Official C++ custom operator samples. Python bindings.
- [dylanroscover/TDComponents](https://github.com/dylanroscover/TDComponents) (98 ★) - Reusable Python-driven components.
- [riebschlager/touchdesigner-playground](https://github.com/riebschlager/touchdesigner-playground) (90 ★) - Learning sketches with minimal Python.
- [ok-vj/okVJ-Shared](https://github.com/ok-vj/okVJ-Shared) (67 ★) - VJ control surface with Python expression system.
- [L05/TouchDesigner](https://github.com/L05/TouchDesigner) (65 ★) - Teaching examples with minimal Python.
- [Richard-Burns/Palette-Tools](https://github.com/Richard-Burns/Palette-Tools) (34 ★) - Palette utilities with some Python.
- [danielsamson/awesome-touchdesigner](https://github.com/danielsamson/awesome-touchdesigner) (22 ★) - Early curated list. No Python focus.

<!--lint enable double-link-->
