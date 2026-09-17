# 8-Bit ALU — Building a CPU Datapath from Scratch

A from-scratch implementation of an 8-bit Arithmetic Logic Unit (ALU), designed to understand how fundamental digital logic blocks come together to form a core component of a CPU datapath.

The ALU performs arithmetic and logical operations on 8-bit operands and uses control signals to select the required operation. The project focuses on understanding the hardware-level implementation of computation rather than treating the ALU as a black-box component.

🔩 Hardware & ICs Used

The ALU is constructed using 74xx-series TTL logic ICs along with passive components and a breadboard-based interconnection.

IC / Component      Function

74LS283	            4-bit Binary Full Adder

74LS86	            XOR Gate

74LS08	            AND Gate


74LS32	            OR Gate
74LS04	            NOT / Inverter Gate
74LS157	            Quad 2-to-1 Multiplexer
74LS173            	4-bit Register
74LS245	            Bus Transceiver
74LS00            	NAND Gate
LEDs	              Output / status indication
Resistors	          LED current limiting / pull-up or pull-down

