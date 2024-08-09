# Dread Runtime

**NOTE**
For now, this project is stand-alone build-able, however, it should primarily be built through the [dread](https://github.com/ArtOfSettling/dread) repo, where it is added as a git submodule. This will change in the future, when this package will ultimately be pushed to [crates.io](https://crates.io).

## Overview

This package represents the runtime component of the engine. This package utilizes the [dr-engine](https://github.com/ArtOfSettling/dr-engine) to load and execute a project. Once built, the project can be passed through command line arguments.

Example usage.
`d-runtime --project "path/to/project/to/load"`

## Prerequisites

1. Install CMake

## How to build

1. `cargo build` / `cargo build --release` {depending on the profile you want to build}