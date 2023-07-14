+++
title = "Getting Started with Julia"
hascode = true
date = Date(2023, 7, 14)
rss = "Getting started with Julia"

tags = ["guide", "julia", "installation"]
+++

# Getting Started

\tableofcontents

## Installation

\note{For Linux users: the Julia maintainers do not recommend installation via your OS package manager (e.g. `apt-get`, `dnf`, `pacman`, etc). As of 2023, these Julia packages remain unofficial, community maintained, and they can be prone to bugs caused by challenges with packaging and linking for all of the correct upstream requirements.}

### The Easy Way (juliaup)

The official **`juliaup`** utility ([GitHub](https://github.com/JuliaLang/juliaup)) is the most user-friendly way to install and maintain your Julia installation. This tool will automatically check for updates to Julia itself and can be used to manage installations of multiple versions of Julia on the same computer, if desired.

This tool can be installed on a **Windows** computer via the Windows Store ([here](https://www.microsoft.com/store/apps/9NJNWW8PVKMN)). Alternatively, it can be installed using Microsoft's [`winget` tool](https://learn.microsoft.com/en-us/windows/package-manager/winget/) by executing
```plaintext
winget install julia -s msstore
```

## The REPL

### Package Manager

### Documentation Browser

