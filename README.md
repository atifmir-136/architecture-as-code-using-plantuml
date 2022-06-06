
# Technical Architecture Diagrams
This repository contains the source code for diagrams generated using Plantuml
## C4 Architecture
The documentation here uses the [C4 model](https://c4model.com) by [Simon Brown](https://simonbrown.je/).
We use [C4-PlantUML](https://github.com/plantuml-stdlib/C4-PlantUML) to create C4 diagrams ; the link has good examples of creating architecture with C4-Plant UML

## Requirements

* [PlantUML](https://plantuml.com/): install (on macOS) from [homebrew](https://brew.sh) with `brew install plantuml`.
* Set up instructions for using Plant UML [Visual Studio Code](https://code.visualstudio.com/) are [here](https://github.com/plantuml-stdlib/C4-PlantUML#snippets-for-visual-studio-code)

## Repository layout

  * `src` contains the source PlantML code for all diagrams.
  * `png` directory contains rendered diagrams in PNG format.

## Usage

To render all diagrams, run `make`. PNG versions of all diagrams will be created in the `png` directory.

`make clean` will remove all rendered images, and `make rebuild` will automatically remove and re-render everything..


