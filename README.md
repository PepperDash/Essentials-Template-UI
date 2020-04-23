# Essentials-Template-UI
The template Crestron SmartGraphics UI for the Essentials standalone rooms

## License
Provided under MIT license

## Overview
This is a template XPanel project based on a Crestron TSW-760 SmartGraphics touchpanel 

## Minimum Requirements
- Essentials Framework runs on any Crestron 3-series processor or Crestron's VC-4 platform.
- To edit and compile the source, Microsoft Visual Studio 2008 Professional with SP1 is required.
- Crestron's Simpl# Plugin is also required (must be obtained from Crestron).

## Dependencies

The [PepperDash.Core](https://github.com/PepperDash/PepperDashCore) SIMPL# library is required.  It is referenced as a submodule and will be automatically checked out when cloning this repo if set to recurse submodules.  This allows different builds of the PepperDash.Core library to be referenced by checking out the desired submodule commit.