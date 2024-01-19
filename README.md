# Awesome CadQuery

A curated list of CadQuery code and resources. Inspired by other lists like [awesome-rust](https://github.com/rust-unofficial/awesome-rust).

If you want to contribute, please read [this](CONTRIBUTING.md).

## Editors and IDEs

* [CQ-editor](https://github.com/CadQuery/CQ-editor) - CadQuery GUI editor based on PyQT supports Linux, Windows and Mac. [![Build status](https://ci.appveyor.com/api/projects/status/g98rs7la393mgy91/branch/master?svg=true)](https://ci.appveyor.com/project/adam-urbanczyk/cq-editor/branch/master)
* [Jupyter-CadQuery](https://github.com/bernhard-42/jupyter-cadquery) - View CadQuery objects in JupyterLab or in a standalone viewer for any IDE.
* [VSCode CadQuery Extension](https://github.com/roipoussiere/cadquery-vscode) - Build parametric 2D/3D CAD models in VSCode with the CadQuery library.
* [freecad-cadquery2-workbench](https://github.com/jpmlt/freecad-cadquery2-workbench) - This is a FreeCAD Workbench to render CadQuery 2.x script in FreeCAD. Based on the original workbench that is only compatible with CadQuery 1.x.
* [cadquery-gui](https://github.com/jmwright/cadquery-gui) - A semi-maintained Electron-based CAD GUI built for CadQuery 1.x and 2.x.
* [BlendQuery](https://github.com/uki-dev/blendquery) - CadQuery integration for Blender.

## CLIs

* [cq-cli](https://github.com/CadQuery/cq-cli) - Command Line Interface for executing CadQuery scripts and converting their output to another format. [![tests](https://github.com/CadQuery/cq-cli/workflows/tests/badge.svg)](https://github.com/CadQuery/cq-cli/actions)

## Extensions and Plugins

* [cadquery-plugins](https://github.com/CadQuery/cadquery-plugins) - A collection of community contributed plugins that extend the functionality of CadQuery. ![Tests](https://github.com/CadQuery/cadquery-plugins/actions/workflows/tests-actions.yml/badge.svg?branch=main)
* [cq_warehouse](https://github.com/gumyr/cq_warehouse) - cq_warehouse augments CadQuery with parametric parts - generated on demand - and extensions to the core CadQuery capabilities.
* [cq-kit](https://github.com/michaelgale/cq-kit) - This repository contains utility classes and functions to extend the features and capabilities of the CadQuery python library. ![https://travis-ci.org/michaelgale/cq-kit](https://travis-ci.com/michaelgale/cq-kit.svg?branch=master)
* [cqMore](https://github.com/JustinSDK/cqMore) - cqMore aims to add more fundamental API to CadQuery.
* [sphinxcadquery](https://github.com/CadQuery/sphinxcadquery) - An extension to visualize CadQuery 3D files in your Sphinx documentation.
* [cq_gears](https://github.com/meadiode/cq_gears) - Gear generator for things like spur gears, helical gears, and planetary gear sets.
* [ocp-freecad-cam](https://github.com/voneiden/ocp-freecad-cam) CAM for CadQuery and Build123d by leveraging FreeCAD library. Visualizes in CQ-Editor and ocp-cad-viewer. Spiritual successor of [cq-cam](https://github.com/voneiden/cq-cam)
8 [freecad_import](https://github.com/CadQuery/cadquery-plugins/tree/main/plugins/freecad_import) - A plugin whhich allows users to import FreeCAD models into CadQuery, and will apply parameters to the model if they are provided and the model is a parametric one (contains a FreeCAD spreadsheet document)

## Part Libraries and Part Generators

* [CQ_Gears](https://github.com/meadiode/cq_gears) - CadQuery based involute profile gear generator.
* [cq-electronics](https://github.com/sethfischer/cq-electronics) - Pure CadQuery models of various electronic boards and components. ![build-status](https://github.com/sethfischer/cq-electronics/actions/workflows/build.yml/badge.svg)
* [KiCad Packages3D Generator](https://gitlab.com/kicad/libraries/kicad-packages3D-generator) - Python scripts for generating 3D electrical component models in STEP and VRML.
* [cq-gridfinity](https://github.com/michaelgale/cq-gridfinity) - A python package for making various Gridfinity compatible objects such as baseplates, boxes, rugged boxes, and drawer spacers. PyPI package available.
* [metric_threads](https://sourceforge.net/p/nl10/code/HEAD/tree/cq-code/common/metric_threads.py) - Module for generating internal and external metric threads.

## Miscellaneous

* [selector_synthesis](https://github.com/jmwright/selector_synthesis) - Collection of methods for synthesizing CadQuery selectors for faces, edges and vertices. ![Tests](https://github.com/jmwright/selector-synthesis/actions/workflows/run_tests.yml/badge.svg)
* [Nales](https://github.com/Jojain/Nales) - Nales is a GUI CAD application that aims to bring full interactivity to CadQuery. [![Build and checks Nales install](https://github.com/Jojain/Nales/actions/workflows/build_and_checks.yaml/badge.svg)](https://github.com/Jojain/Nales/actions/workflows/build_and_checks.yaml)
* [Semblage](https://github.com/7BIndustries/Semblage) - Semblage is an open source CAD GUI backed by a programmatic CAD API named CadQuery. [![tests](https://github.com/7BIndustries/Semblage/actions/workflows/tests.yml/badge.svg)](https://github.com/7BIndustries/Semblage/actions/workflows/tests.yml)
* [cq-flake](https://github.com/marcus7070/cq-flake) - A nix flake that allows you to reproduce a CadQuery and CQ-editor installation anywhere that has the nix package manager.
* [ocp-action](https://github.com/Yeicor/ocp-action/) - GitHub Action that builds OCP models (CadQuery/Build123d/...), renders them and sets up a model viewer on Github Pages. ![Tests](https://github.com/Yeicor/ocp-action/actions/workflows/ci.yml/badge.svg?branch=main)
* [cadquery-doc-translations](https://github.com/tkoyama010/cadquery-doc-translations) - A repository that holds Japanese translations of the CadQuery docs.

## Examples and Tutorials

* [cadquery-contrib](https://github.com/CadQuery/cadquery-contrib) - A place to share CadQuery scripts, modules, tutorials and projects.
* [fx-cad-notes](https://github.com/fx-bricks/fx-cad-notes) - Documentation showing how [FX-Bricks](https://shop.fxbricks.com/) uses CadQuery in their product development pipeline.
* [spindle-assy-example](https://github.com/marcus7070/spindle-assy-example) - An example assembly of the vacuum attachment for a Workbee CNC router.
* [cadquery-models](https://github.com/tanius/cadquery-models) - A bucket repository for CadQuery 3D models and experiments, except larger projects that deserver their own repo.
* [Eggbeater Antenna](https://github.com/jmwright/cadquery-projects/tree/master/eggbeater-antenna) - Example of a design that automatically adjusts to a design constraint. In this case the frequency drives the design.
* [Tetrakaidecahedron](https://github.com/bragostin/CadQuery-Examples/blob/main/Tetrakaidecahedron.py) - An example of how to create a tetrakaidecahedron.

## Style Guides

* [CQ Style](https://github.com/jpoles1/cq_style) - A neat CadQuery structure for your projects.
