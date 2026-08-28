# Herz

> What is Herz?

Herz is a package and build system for modifying multi-version Eaglercraft/Minecraft projects.

It provides a common architecture/core APIs for building client modifications across different versions and compilation targets while giving packages access to features such as bytecode transformation, generated stubs, package composition, platform APIs, and TeaVM tooling (like WebGUI).

Herz is designed so that packages can be developed without directly bundling Minecraft source code. Instead, platform-specific build projects and generated stubs provide the interfaces needed for compilation and transformation.

The goal is to make developing complex Eaglercraft/Minecraft clients less dependent on a specific source tree, game version, or runtime target.

It also allows developers to make specific parts of the Eaglercraft client, and be able to use other's packages to customize their clients as much as they want. 

> How are the repositories structured?

Herz is split in specific modules, as seen in the several repositories in the Admanatine org.

* [Herz-Core](https://github.com/Admanatine/Herz-Core) — Core APIs and common package functionality

* [Herz-Compile](https://github.com/Admanatine/Herz-Compile) — Package composition (basically taping them together) and build tooling

* [Herz-WebGUI](https://github.com/Admanatine/Herz-WebGUI) — Web GUI API extension

* [Herz-1_8-Build](https://github.com/Admanatine/Herz-1_8-Build) — Eaglercraft 1.8 platform and compilation target

Additional repositories contain supporting tools such as stub generation and compile-time APIs.

> Project Status

Herz is currently on hold while I work on other projects.

The existing repositories remain available for usage, but the project is not currently considered production-ready and documentation is incomplete.

When I get back to this project, the next goal is to make readable docs and finish many loose ends that were left. 

 
