---
layout: post
author: SteelPh0enix
title: Guide index
categories: setup-guide raylib homepage
---

## Description

On this page, you'll find multiple guides about Raylib configuration in various C and C++ environments, with various toolchains and build systems.
I'm hoping to create the most comprehensive setup wiki for Raylib.

If you have suggestions, or you want your favourite OS/toolchain/build system featured here, please let me know, or make a PR for this repository (link is on the top of page)

My Discord handle: SteelPh0enix#6969
Raylib's Discord server: <https://discord.gg/raylib>
Raylib's homepage: <https://www.raylib.com/>

## Featured software

If you are new to C/C++ environment, here's the list of some commonly used pieces of software, with descriptions:

### IDEs (Integrated Development Environment) and editors

IDE is a program used to create applications, it's usually composed of an editor and some tools that help writing and analyzing the code, for example syntax colouring, refactoring (renaming) tools, debugger support, and so on

Suggested IDEs and editors:

* **Microsoft Visual Studio 2019** - free, but very big and limited to Windows only. A good choice for a beginner, as it requires very litte configuration to get going.
* **IntelliJ CLion** - paid IDE, unless you can get academic license. It's lighter than Visual Studio, and it has very good refactoring and analyzing tools. Also a good choice for beginner, a bit harder to setup than Visual Studio.
* **Visual Studio Code** - free and very powerful editor with thousands of plugins, making it very suitable tool for any language.

### Toolchains (compilers)

There are few commonly used toolchain that works with Raylib without major issues

* **MinGW/GCC** - GNU Compiler Collection, very popular and simple to use toolchain. **Recommended for beginners**
* **Microsoft Visual C/C++** - Microsoft's toolchain, Windows-only. Also good for beginners, if used with Visual Studio
* **Clang** - a frontend for LLVM project. Not recommended for beginner Windows users.

### Build systems

Build system is a tool that tells the toolchain (compiler) how to create the application from source and configuration files. There are two types of build tools: *normal build systems*, which run the toolchain commands directly, and *meta-build systems* which generate some other build system files, which are then used to build the program. Meta-build systems are usually easier to use, and more flexible than normal build systems.

Commonly used build systems:

* **make** - default build system for MinGW and GCC toolchains
* **ninja** - small build system which works with multiple toolchains
* **MSBuild** - Microsoft's build system for Microsoft Visual C and C++

Commonly used meta-build systems:

* **CMake** - an industry standard C/C++ meta-build system, extremely popular. Decent for beginners.
* **Premake** - very simple, Lua-based meta-build system. Very good for beginners.

## Guides

Pick a guide from list below.

### General guides

* **How does C/C++ toolchain create the application?** - 101 app building for C/C++ newbies. **Strongly suggested read, if you're new to C/C++ environment!**
* **Common issues with Raylib building/linking** - if you have issues with existing setup, go here

### Visual Studio

* **Setting up Raylib project with Visual Studio 2019** - that's the easiest way to get going with fully featured and free environment. **Warning**: Visual Studio is a pretty big program, so if you prefer to have lighter setup (and you don't mind some tweaking and manual configuration), you can try other guides.
* **Setting up Raylib project with CMake and Visual Studio 2019** - alternative way for Visual Studio setup, instead of using it's own build system, we'll use CMake
* **Setting up Raylib project with Premake and Visual Studio 2019** - another alternative way for Visual Studio setup

### Visual Studio Code

* **Setting up Raylib project with CMake and Visual Studio Code** - simplest version of the setup, including VSCode configuration for C++ development
* **Setting up Raylib project with Premake and Visual Studio Code** - alternative guide, with premake instead of CMake (and a bit more VSCode configuration)

### CLion

* **Setting up Raylib project with CLion and CMake** - if you have CMake license, read this
