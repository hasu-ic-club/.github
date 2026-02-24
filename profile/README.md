# Welcome to `Hasunosora IC Design Club`
*Note: This is a side of Nijigasaki IC Design Club*

We will provide some open-source free-to-use ASIC/FPGA IP cores, modules, design projects for everyone!

## Here are our TOP projects
### [Hasunosora Infrastructure](https://github.com/hasu-ic-club/hasunosora-hdl-infra)
This repository provides a collection of **Mordern System Verilog** infrastructure components for **RTL design and Verification**, 
focusing on scalability, modularity, and maintainability. Each module is designed to simplify integration and promote best practices across different hardware projects.

### HSFx Floating-Point Arithmetic Series
This is a series of floating-point arithmetic library which compatible with IEEE754 standard or ANY other mantissa/exponent combination.
All IP cores in this series are fully pipelined for maximize the performance, but also optimize to reduce the area.

| Math Function | Repository |
| -- | -- |
| Add (a + b) | [HSF1-FPADD-PIPE](https://github.com/hasu-ic-club/hsf1-fpadd-pipe) |
| Multiply  (a * b) | [HSF2-FPMUL-PIPE](https://github.com/hasu-ic-club/hsf2-fpmul-pipe) |

### HSAx Integer/Fixed-point Arithmetic Series
This is a series of integer/fixed-point arithmetic library. All IP cores in this series are parameterizable and easy to integrate.

| Math Function | Repository |
| -- | -- |
| Division (a / b, a % b) | [HSFA-NON-RESTORING-DIV](https://github.com/hasu-ic-club/hsa1-non-restoring-div) |

### HSXx FPGA-based High-Speed Communication
HSX series IPs are optimized for FPGAs to implement high-performance high-speed communication buses on them.

- [HSX1-XUS-PCIE-AXIL](https://github.com/hasu-ic-club/hsx1-xus-pcie-axil): PCIe to AXI-Lite Bridge for Xilinx UltraScale+ FPGAs

## Dependency Management
We use [FuseSoC](https://github.com/olofk/fusesoc) to manage **dependencies and relationships** between components. 
FuseSoC allows easy reuse, configuration, and simulation of IP blocks across projects.
You can also use FuseSoC to integrate our components directly into your design, ensuring a consistent and automated build flow.

## Coding Style and License
All components in this library follow a clean and unified coding style, with high readability and synthesizability in mind.
Under the MIT License, you are free to:
- Modify the functions or designs as you wish.
- Integrate them into commercial or academic projects.
- Contribute improvements or bug fixes back to the community.

## Contributing
We warmly welcome community contributions!
If you’d like to improve a design, add a new feature, or share your own module:
- Fork the repository you want to edit.
- Make your changes and test them.
- Submit a pull request with a clear description.

We review all contributions carefully to maintain design quality and consistency.

