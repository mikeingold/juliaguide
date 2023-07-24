-repl+++
title = "Getting Started with Julia"
hascode = true
date = Date(2023, 7, 14)
rss = "Getting started with Julia"

tags = ["guide", "julia", "installation"]
+++

# Getting Started

\tableofcontents

## Installation

Linux note goes here.

### The Easy Way (juliaup)

The official **`juliaup`** utility ([GitHub](https://github.com/JuliaLang/juliaup)) is the most user-friendly way to install and maintain your Julia installation. This tool will automatically check for updates to Julia itself and can be used to manage installations of multiple versions of Julia on the same computer, if desired.

This tool can be installed on a **Windows** computer via the Windows Store ([here](https://www.microsoft.com/store/apps/9NJNWW8PVKMN)). Alternatively, it can be installed using Microsoft's [`winget` tool](https://learn.microsoft.com/en-us/windows/package-manager/winget/) by executing
```plaintext
winget install julia -s msstore
```

## The REPL

### Package Manager

There are two ways to interact with Julia's package manager: an interactive mode available inside the REPL, and via the native `Pkg` package.

To enter the interactive package manager, simply press the right-bracket key `]` from the Julia REPL.
```julia-repl
julia> ]
```

### Documentation Browser

Offline documentation for Julia functions and operators is available via an interactive mode within the REPL, similar to Matlab's `help` command.
```julia-repl
julia> ?
```
