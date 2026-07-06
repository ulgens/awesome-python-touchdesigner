# Awesome Python + TouchDesigner [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of Python-focused resources for [TouchDesigner](https://derivative.ca) — resources that bring Python and TouchDesigner together - either extending TD with Python scripts, integrating external Python projects into TD, or bridging both worlds.

> The Python ecosystem is ever-evolving. TouchDesigner's Python environment often lags significantly behind the broader Python ecosystem — not just in CPython version, but also in library compatibility, tooling, and modern best practices. If you're working on Python-intensive projects, we recommend also consulting modern Python resources to stay aware of current best practices and available tooling.

## Contents

- [References](#references)
- [Guides & Articles](#guides--articles)
- [Courses & Workshops](#courses--workshops)
- [Environment & Package Management](#environment--package-management)
- [Libraries & Tools](#libraries--tools)
- [Contributing](#contributing)

---

## References

- [Official Wiki - Python](https://docs.derivative.ca/Python) - The official top level reference for Python & TouchDesigner integration
- [Official Wiki - Python Classes and Modules](https://docs.derivative.ca/Python_Classes_and_Modules) - List of important Python classes and modules, roughly grouped together by subject

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

---

## Contributing

> **Early stage notice:** This list is a work in progress and may contain inaccuracies or miss important resources. Contributions are welcome — open a PR if you see anything to improve.

Contributions are welcome! While you are creating a PR, please make sure that PR only adds - updates - deletes a single resource.

The ordering in the sections are not exact, but loosely following:
* Derivative resources first
* Other resources sorted alphabetically (case-insensitive)
