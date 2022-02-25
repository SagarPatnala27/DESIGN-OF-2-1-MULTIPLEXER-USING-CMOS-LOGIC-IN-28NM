# DESIGN-OF-2-1-MULTIPLEXER-USING-CMOS-LOGIC-IN-28NM
This repository presents the design of 2:1 mulitiplexer implemented using Synopsis Custom compiler on 28nm CMOS Technology
## Table of Contents
1. [Abstract](#abstract)
2. [Circuit Details](#circuit-details)
3. [Toolsused](#toolsused)
4. [Specifications](#specifications)
5. [Implemented Circuit Diagram](#implemented-circuit-diagram)
6. [Testbench](#testbench)
7. [Implemented Waveforms](#implemented-waveforms)
8. [Netlist](#netlist)
9. [Acknowledgement](#acknowledgement)
10. [References](#references)
## Abstract
A multiplexer is a unidirectional device which is used in any application in which data must be switched from mul- tiple sources to a destination. It is a combinational circuit which has a maximum of 2 to the power n data inputs, ‘n’ selection lines and a single output line. One of these data inputs will be connected to the output based on the values  of the selection lines. Multiplexers are used in building dig- ital semiconductors such as CPUs and graphics controller, as programmable logic devices, in computer networks and digital video. This paper presents a 2:1 multiplexer using CMOS logic. The implementation is done in VLSI technol- ogy as it has features like small size, low cost, high operat- ing speed and low power.

Keywords- CMOS, PMOS, NMOS, Multiplexer,Inverter

## Circuit Details
A 2 to 1 multiplexer consists of two inputs ‘A’ and ‘B’, one select input ‘S’ and one output ‘Y’. De- pending on the select signal, the output is connected to ei- ther of the inputs. Since there are two input signals, only two ways are possible to connect the inputs to the outputs, so one select signal is needed to do these operations. Ig- noring the don’t care conditions, we can derive the Boolean Expression of a 2 to 1 Multiplexer as Y= selectbar(B)
+ select(A), where selectbar indicates negation of select signal. The static CMOS based 2:1 MUX using the above Boolean expression will be designed using a pull-up net- work consisting of 4 pMOS and a pull-down network con- sisting of 4 nMOS. The pull up network is constructed using two parallel pMOS circuits connected in series. The pull- down network wil be constructed using two series nMOS cir- cuits connected in parallel. The output of the Static CMOSlogic is connected to an inverter to obtain the correct output.VDD is connected to the pull-up circuit to provide power supply and the ground is connected to the pull-down circuit. The input A is a pulse wave of width 5us and input B is a pulse wave of width 10us . One of these inputs is selected based on the select signal pulse. One of the major advan- tages of Static CMOS logic is that they have zero quiescent power dissipation, where for any applied input state either the pull-up network or the pull-down network remains off. The problem with this type of implementation is that more area is required in implementing logics.
## Toolsused
Synopsys Custom Compiler:  The Synopsys Custom Compiler™ design environment is a modern solution for full-custom analog, custom digital, and mixed-signal IC design. As the heart of the Synopsys Custom Design Platform, Custom Compiler provides design entry, simulation management and analysis, and custom layout editing features. This tool was used to design the circuit on a transistor level.
Synopsys Primewave:  PrimeWave™ Design Environment is a comprehensive and flexible environment for simulation setup and analysis of analog, RF, mixed-signal design, custom-digital and memory designs within the Synopsys Custom Design Platform. This tool helped in various types of simulations of the above designed circuit.
Synopsys 28nm PDK:  The Synopsys 28nm Process Design Kit(PDK) was used in creation and simulation of the above designed circuit.
## Specifications
![Image text](https://github.com/SagarPatnala27/DESIGN-OF-2-1-MULTIPLEXER-USING-CMOS-LOGIC-IN-28NM/blob/main/PROJECT%20FILES/a_properties.PNG)
![Image text](https://github.com/SagarPatnala27/DESIGN-OF-2-1-MULTIPLEXER-USING-CMOS-LOGIC-IN-28NM/blob/main/PROJECT%20FILES/b_properties.PNG)
![Image text](https://github.com/SagarPatnala27/DESIGN-OF-2-1-MULTIPLEXER-USING-CMOS-LOGIC-IN-28NM/blob/main/PROJECT%20FILES/c_properties.PNG)
![Image text](https://github.com/SagarPatnala27/DESIGN-OF-2-1-MULTIPLEXER-USING-CMOS-LOGIC-IN-28NM/blob/main/PROJECT%20FILES/capacitor_properties1.PNG)


## Implemented Circuit Diagram
![Image text](https://github.com/SagarPatnala27/DESIGN-OF-2-1-MULTIPLEXER-USING-CMOS-LOGIC-IN-28NM/blob/main/PROJECT%20FILES/schematic2.PNG)
## Testbench
![Image text](https://github.com/SagarPatnala27/DESIGN-OF-2-1-MULTIPLEXER-USING-CMOS-LOGIC-IN-28NM/blob/main/PROJECT%20FILES/tb_symbol_2.PNG)

## Implemented Waveforms
![Image text](https://github.com/SagarPatnala27/DESIGN-OF-2-1-MULTIPLEXER-USING-CMOS-LOGIC-IN-28NM/blob/main/PROJECT%20FILES/timing.PNG)
## netlist

## Acknowledgements

## References


