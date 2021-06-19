# FABulous Sky - a heterogeneous FPGA fabric in Skywater130

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0) [![UPRJ_CI](https://github.com/efabless/caravel_project_example/actions/workflows/user_project_ci.yml/badge.svg)](https://github.com/efabless/caravel_project_example/actions/workflows/user_project_ci.yml) [![Caravel Build](https://github.com/efabless/caravel_project_example/actions/workflows/caravel_build.yml/badge.svg)](https://github.com/efabless/caravel_project_example/actions/workflows/caravel_build.yml)

# Introduction 
Demonstration of the Fabulous Fpga design flow using the Skywater 130 process. 
The design flow includes the specification of the routing fabric, individual tiles, and the exact fabric description. This is used to implement heterogeneous tiles for logic, memory, and I/O that are then stitched together to a fabric. 
The Fabulous tool generates all RTL codes, physical constraints for the implementation, a model for the Yosys-Abc-Nextpnr FPGA CAD suite as well as a bitstream assembler. Additionally, our flow provides an emulation path to test Fabulous FPGA systems on commercial FPGAs. 
We will demonstrate how external modules can be integrated into Fabulous fabrics including configuration support. All this is supported with good quality of results (Area, Performance, Power) and very little design effort.
