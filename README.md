# Awesome Python + TouchDesigner [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of Python-focused resources for [TouchDesigner](https://derivative.ca) — resources that bring Python and TouchDesigner together - either extending TD with Python scripts, integrating external Python projects into TD, or bridging both worlds.

> [!IMPORTANT]
> The Python ecosystem is ever-evolving. TouchDesigner's Python environment often lags significantly behind the broader Python ecosystem — not just in CPython version, but also in library compatibility, tooling, and modern best practices. If you're working on Python-intensive projects, we recommend also consulting modern Python resources to stay aware of current best practices and available tooling.

> [!TIP]
> Do you need help with Python + TouchDesigner projects?
> I can help with the design and implementation of your project. Project analysis, infrastructure design, automation, quality assurance, packaging and everything in between. [Contact me on LinkedIn](https://www.linkedin.com/in/ulgens/)

## Contents

- [References](#references)
- [Guides & Articles](#guides--articles)
- [Courses & Workshops](#courses--workshops)
- [Environment & Package Management](#environment--package-management)
- [Libraries & Tools](#libraries--tools)
- [AI Tools](#ai-tools)
- [MCP Tools](#mcp-tools)
- [Contributing](#contributing)

---

## References

- [Official Wiki - Python](https://docs.derivative.ca/Python) - The official top level reference for Python & TouchDesigner integration
- [Official Wiki - Python Classes and Modules](https://docs.derivative.ca/Python_Classes_and_Modules) - List of important Python classes and modules, roughly grouped together by subject

> [!IMPORTANT]
> Note that while docs.derivative.ca is the official reference, details about TD's Python integration may be outdated, as it isn't open for community contributions. Cross-referencing with other sources is recommended.

## Guides & Articles

- [Official Wiki - Introduction to Python Tutorial](https://docs.derivative.ca/Introduction_to_Python_Tutorial) - General introduction to using Python in TouchDesigner
- [Official Wiki - Python Tips](https://docs.derivative.ca/Python_Tips) - How to do some common actions in Python
- [Derivative - TouchDesigner Python Examples (Curriculum)](https://learn.derivative.ca/courses/100-fundamentals/lessons/108-resources/topic/touchdesigner-python-examples/) - Official fundamentals course page with a downloadable .tox file containing 100+ Python usage examples.
- [Akira Nakayasu - TouchDesigner + Python Lectures](https://lecture.nakayasu.com/en/docs/touchdesigner/python/) - Fundamentals of Python integration in TouchDesigner, covering both Windows and macOS
- [Interactive & Immersive HQ - Python Cheat Sheet for TD Developers](https://interactiveimmersive.io/blog/python/python-cheat-sheet-for-touchdesigner-developers) - Python basics cheat sheet of tricks and tips that are useful for TouchDesigner developers to know, including several that are built into Python itself, as well as a large number that are specific to the TouchDesigner environment
- [Interactive & Immersive HQ - Useful Python Libraries for TD](https://interactiveimmersive.io/blog/python/useful-python-libraries-for-touchdesigner-beginners/) - Curated list of Python libraries useful in TD projects
- [Matthew Ragan - Python in TouchDesigner](https://matthewragan.com/teaching-resources/touchdesigner/python-in-touchdesigner/) - Series of examples will look at basic python concepts through the lens of the TouchDesigner programmer
- [rvirmoors - Creative Coding for Interactive Art: TD & Python](https://rvirmoors.github.io/ccia/touchdesigner-and-python) - A practical introduction to processing data and logic in TD using Python
- [SudoMagic - Python in TD Style Guide](https://td-style.guide/docs/SM-guide/python-in-td) - How SudoMagic has standardized its Python practice for work with TouchDesigner

## Courses & Workshops

- [Interactive & Immersive HQ - Pro TouchDesigner Python & Extension Architecture](https://pro.interactiveimmersive.io/courses/pro-touchdesigner-python-extension-architecture/) - Advanced course by Noah Norman on Python extensions, state machines, Pydantic validation, IDE automation, Git workflows, and virtual environments. (Paid)
- [Music Hackspace - Getting Started With Python in TouchDesigner](https://musichackspace.org/courses/getting-started-with-python-in-touchdesigner/) - Python scripting inside TouchDesigner, from data types and expressions to referencing operators, with hands-on exercises to drive and automate your networks programmatically (Paid)
- [The NODE Institute - Python in TouchDesigner (Refactored)](https://thenodeinstitute.org/product/ss25-td-pro-python-in-touchdesigner-refactored/) - Led by Daniel Molnar (aka Function Store), designed for both beginners and experienced TouchDesigner users looking to expand their scripting skills (Paid)

## Environment & Package Management

- [TDPyEnvManager](https://docs.derivative.ca/Palette:tdPyEnvManager) - The official custom component that helps manage Python environments as well as Conda environments
- [TD PIP](https://olib.amb-service.net/component/td-pip) - Component that installs PIP directly in to a TouchDesigner project and dynamically downloads and import the libraries in
- [TD_PyPaIn](https://github.com/PlusPlusOneGmbH/TD_PyPaIn) - [Deprecated] A collection of components to handle virtual environments and external python packages from within TouchDesigner with a hands-off approach (includes TD_PIP)

## Libraries & Tools

- [cuda-link](https://github.com/forkni/cuda-link) - Zero-copy GPU texture transfer between TouchDesigner and Python processes using CUDA IPC.
- [graph_explorer](https://github.com/fughilli/graph_explorer) - Python-based tool for programmatically creating and manipulating node networks in TouchDesigner
- [td-completes-me](https://github.com/picturesbyrobots/td-completes-me) - A combo TOX/VSCode extension that leverages the Language Server protocol to send a list of context-sensitive auto-completion items to Microsoft's Visual Studio Code.
- [TD_Github](https://github.com/eusebijucgla/TD_Github) - Component for Touch Designer to clone and pull a GitHub repository in your working directory.
- [TD-State-Machine](https://github.com/InfoMusCP/TD-State-Machine) - A robust, table-driven Finite State Machine component for TouchDesigner
- [TouchPy](https://pypi.org/project/touchpy/) - High-performance Python toolset for working with TouchDesigner components headlessly via the TouchEngine SDK. It provides GPU-accelerated data exchange (CUDA/Vulkan) for TOPs, CHOPs, DATs, and parameters.
- [NDIForPython](https://github.com/UnveilStudio/NDIForPython) - Unofficial Python bindings for NDI® — send video frames over the network from Python to TouchDesigner, OBS, Resolume, vMix, and any NDI-aware app. ctypes wrapper around the NDI Runtime
- [TopArray](https://github.com/IntentDev/TopArray) - Python module designed to facilitate the interaction between Python/PyTorch tensor operations and TouchDesigner TOPs. It provides a workflow for referencing CUDA memory from TOPs as tensors and for copying a tensor's data to a scriptTOP efficiently.

> [!CAUTION]
> Modern AI tools are known for their overconfident but misleading results and tremendous negative environmental impact.
>
> Use them responsively.

## AI Tools

- [ComfyUI-TD](https://github.com/JiSenHua/ComfyUI-TD) - ComfyUI to TouchDesigner custom node for real-time streaming of generated data. It supports sending images, videos, point clouds (traditional PLY / Gaussian Splatting PLY), and audio from ComfyUI into TouchDesigner.
- [LOPs (Language Operators)](https://docs.dotsimulate.com/getting-started/) - Native operator family for TouchDesigner — agents, tools, speech, retrieval, generative workflows, stateful automation, and authorable systems, built directly into your TD project.
- [td-snapshot](https://github.com/rootnotez/td-snapshot) - TouchDesigner .tox plugin to extract patch info into text for input to LLMs
- [td-gemini-toolkit](https://github.com/SudoMagicCode/td-gemini-toolkit) - Collection of custom TouchDesigner Components that use the Google Gemini API. Focused on an library independent workflow, this set of components is a batteries included collection that requires no additional libraries or dependencies to get working.
- [TDDepthAnything](https://github.com/olegchomp/TDDepthAnything) - TouchDesigner implementation for Depth Anything and Depth Anything v2 with TensorRT monocular depth estimation.
- [TD-ONNX-EX](https://github.com/yeataro/TD-ONNX-EX) - Examples of using onnxruntime in TouchDesigner
- [TouchDiffusion](https://github.com/olegchomp/TouchDiffusion) - TouchDesigner implementation for real-time Stable Diffusion interactive generation with StreamDiffusion.

## MCP Tools

> [!TIP]
> MCP (Model Context Protocol) is an open-source standard for connecting AI applications to external systems.
>
> Using MCP, AI applications like Claude or ChatGPT can connect to data sources (e.g. local files, databases), tools (e.g. search engines, calculators) and workflows (e.g. specialized prompts)—enabling them to access key information and perform tasks.
>
> Think of MCP like a USB-C port for AI applications. Just as USB-C provides a standardized way to connect electronic devices, MCP provides a standardized way to connect AI applications to external systems.
>
> _https://modelcontextprotocol.io/docs/getting-started/intro_

- [Embody](https://github.com/dylanroscover/Embody) - MCP server for TouchDesigner — build, wire, and debug networks with AI. Plus git-diffable externalization.
- [TD_Builder_alpha](https://github.com/TrueFiasco/TD_Builder_alpha) - Key-free MCP servers that let LLMs build real TouchDesigner networks: local knowledge base (no API keys), offline .toe/.tox generation, live TD editing. Eval-gated - 636/636 build-token-exact.
- [td-mcp](https://github.com/DazaiStudio/td-mcp) - TouchDesigner MCP server with node CRUD, Python execution, and planned extensions for viewport capture, GLSL authoring, and scene scaffolding. Fork of 8beeeaaat/touchdesigner-mcp. Maintained by NYU Media Commons.
- [TDPilot](https://github.com/dreamrec/TDPilot) - TouchDesigner AI assistant (112 MCP tools, correctness-first brain: plan -> execute -> validate -> rollback, 656 operator cards, sync diagnostics, read-only cockpit UI)
- [touch-mcp](https://github.com/benoitliard/touch-mcp) - High-performance MCP server for TouchDesigner — live control via WebSocket with 29 tools (nodes, parameters, connections, CHOP/TOP/SOP/DAT data, timeline, render, layout, batch). Python + FastMCP
- [touchdesigner-mcp](https://github.com/8beeeaaat/touchdesigner-mcp) -  MCP server for TouchDesigner

---

## Contributing

> [!NOTE]
> This list is a work in progress and may contain inaccuracies or miss important resources. Contributions are welcome — open a PR if you see anything to improve.

Please make sure that a PR only adds - updates - deletes a single resource.

The ordering in the sections are not exact, but loosely following:
* Derivative resources first
* Other resources sorted alphabetically (case-insensitive)
