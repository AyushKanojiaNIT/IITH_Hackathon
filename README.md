# Implementation of an Effective 16T 1-bit Hybrid Full Adder cell in 28nm process
## Table of contents
- [Abstract]()
- [Introduction]()
- [Design of the proposed 1-bit hybrid full adder]()
- [Simulation and Performance analysis]()
  - [Power]()
  - [Delay]()
- [Conclusion]()
- [Acknowledgement]()
- [References]()
## Abstract
An energy-efficient design of every computing tool is the need of the hour, and a full adder is an elementary part of almost every computing tool. In this work a 1-bit full adder is implemented using an hybrid approach for energy-efficient applications. The presented design provides a full swing output and consumes low power as compared to conventional design. The design, simulation and performance analysis of the presented full adder design is carried-out using Synopsys custom compiler tool in 28nm process node. The reduction observed by the presented 1-bit full adder cell in terms of power, delay, and power-delay product(PDP) is found to be about 9%, 27.4%, and 34% as compared to conventional design.
## Introduction
There is an explosive rise in demands of power-efficient electronic gadgets due to the increase in dependency on computing tools like cellular phones, smartwatches, fitness bands, etc. The VLSI design engineers are finding more and more ways to a circuit energy-efficient for the best utilization of these devices. But, it is a very hard task in lower technology nodes.
The Arithmetic Logic Unit(ALU) is responsible for every arithmetic operation performed by the chip, and one of the fundamental components of almost every arithmetic circuit like subtractor, multiplier, divider, is a full adder [1,2]. Therefore, improving the performance of a full adder cell at the primary stage effectively improves the overall system performance. Power-delay product (PDP) is considered as a fairer performance metric as it shows the energy consumed by the circuit. 
Various logic styles are available to downscale the total power and area of a full adder circuit [3,4]. Thus, it is very crucial to select a proper logic style. Here, hybrid logic style is employed to design the full adder cell. In the presented design, a hybrid logic style is used. In hybrid style various logic styles are exploited to improve the performance of the entire full adder circuit.
