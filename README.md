# SConsLib

SconsLib is a "library" or module which extends Scons build system with variety of functionality aiming to support large, cross-platform C/C++ projects.

## Prerequisites
Scons is expected to be available in the environment.

## Installation
Move or copy "sconslib" root directory as "$HOME/.scons/site_scons".
Alternatively you can copy "sconslib" as "/path/your_project/site_cons".
Both of this locations will make sconslib available; former make it available for every project, latter make it available for one project only.

## Usage
In your Scons scripts (primarily in SConstruct), import "SconsLib" module.
Following projects uses sconslib which can give you elaborate examples on how to use:

https://github.com/semihc/gsl
https://github.com/semihc/qdecimal

