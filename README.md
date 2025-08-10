# OpenTriton

This is the well known *Triton* framework for classic Amiga, refactored to build against NDK3.2

## [amigazen project](http://www.amigazen.com)

*A web, suddenly*

*Forty years meditation*

*Minds awaken, free*

**amigazen project** uses modern software development tools and methods to update and rerelease classic Amiga open source software. Our upcoming releases include a new AWeb, and a new Amiga Python 2.

Key to our approach is ensuring every project can be built with the same common set of development tools and configurations, so we created the ToolKit project to provide a standard configuration for Amiga development. All *amigazen project* releases will be guaranteed to build against the ToolKit standard so that anyone can download and begin contributing straightaway without having to tailor the toolchain for their own setup.

The original authors of the *OpenTriton* software are not affiliated with the amigazen project. This software is redistributed on terms described in the documentation.

Our philosophy is based on openness:

*Open* to anyone and everyone	- *Open* source and free for all	- *Open* your mind and create!

PRs for all of our projects are gratefully received at [GitHub](https://github.com/amigazen/). While our focus now is on classic 68k software, we do intend that all amigazen project releases can be ported to other Amiga-like systems including AROS and MorphOS where feasible.

## About ToolKit

**ToolKit** exists to solve the problem that most Amiga software was written in the 1980s and 90s, by individuals working alone, each with their own preferred setup for where their dev tools are run from, where their include files, static libs and other toolchain artifacts could be found, which versions they used and which custom modifications they made. Open source collaboration did not exist as we know it in 2025. 

**ToolKit** from amigazen project is a work in progress to make a standardised installation of not just the Native Developer Kit, but the compilers, build tools and third party components needed to be able to consistently build projects in collaboration with others, without each contributor having to change build files to work with their particular toolchain configuration. 

All *amigazen project* releases will release in a ready to build configuration according to the ToolKit standard.

Each component of **ToolKit** is open source and like *OpenTriton* here will have it's own github repo, while ToolKit itself will eventually be released as an easy to install package containing the redistributable components, as well as scripts to easily install the parts that are not freely redistributable from archive.

## Requirements

- Amiga or Amiga-compatible computer with latest operating system software
- SAS/C 6.58 setup according to ToolKit standard
- LibDescConverter for generating library headers. Can be obtained from https://gitlab.com/boemann/libdescconverter
- NDK3.2R4
- TexInfo is required to generate the Triton framework documentation

## To Do

- Add VBCC build
- Add unittests
- Code review and hardening
- Fix issue with libdescconverter and add to smakefile

## Contact 

- At GitHub https://github.com/amigazen/opentriton
- on the web at http://www.amigazen.com/toolkit/ (Amiga browser compatible)
- or email toolkit@amigazen.com

## Original OpenTriton Readme

This release of OpenTriton consists of three archives:
  - opentriton-2.0-usr.lha contains all files required to run
    Triton applications.
  - opentriton-2.0-dev.lha is required by application developers
    for writing Triton applications.
  - opentriton-2.0-src.lha contains the complete source code
    for OpenTriton 2.0.

## License

OpenTriton is free software; you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation; either version 2 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

For the complete license text, see [LICENSE.md](LICENSE.md).

**Copyright (C) 1993-1998 Stefan Zeiger**

## Acknowledgements

*Amiga* is a trademark of **Amiga Inc**.
