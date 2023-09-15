# RJ 45
- standard inputs for Ethernet cables 
- ![[Pasted image 20230903104138.png]]
- ![[Pasted image 20230903104151.png]]


# Ethernet 
- collection of network protocols/standards 

# Network protocols 
- set of rules and conventions that govern how data is transmitted
- physical protocols like shape and size of the cable 
- logical protocols like ip


# Bits and Bytes 
- the speed of connection between devices is measured in **bits per second**
- 8 bits = 1 byte
- G byte is 8 time larger that G bit
- it operates like a bit at a time not a byte at a time 
- ![[Pasted image 20230903105245.png]]


# Ethernet Standards (copper)
- Defined in the **IEEE 802.3 standard**
- IEEE ? 
	- Institute of Electrical and Electronics Engineers 
- ![[Pasted image 20230903110443.png]]


# UTP Cables 
- Unshielded Twisted Pair
	- have no metallic shield, which can make them vuln to electrical interference
- Twisted protects against EMI (Electromagnetic interference)
- **10BASE-T and 100BASE-T uses 2 pairs (4 wires)**
- **1000BASE-T and 10GBASE-T uses 4 pairs (8 wires)**
- ![[Pasted image 20230903111048.png]]


## Advantages of UTP (Unshielded Twisted Pair) Cables: 

1. **Cost-Effective:** UTP cables are generally less expensive than shielded cables, making them a cost-effective choice for many networking needs.
    
2. **Flexibility:** UTP cables are flexible and easy to work with, making them suitable for various installation scenarios.
    
3. **Common Usage:** UTP cables are widely used and readily available, making them a standard choice for Ethernet networking in homes, offices, and data centers.
    

## Situations Where Shielded Cables (STP) Might Be Preferred:

1. **High Electromagnetic Interference (EMI) Environments:** In locations with a high risk of electromagnetic interference, such as near heavy machinery or in industrial settings, shielded cables may be preferred to provide extra protection against EMI.
    
2. **Long Cable Runs:** For longer cable runs (typically beyond 100 meters or 328 feet), shielded cables can offer better resistance to signal degradation caused by interference.


# 10BASE-T, 100BASE-T
- used pins are 1,2 3,6
- ![[Pasted image 20230903111422.png]]
- Full-Duplex?
	- sends and recieve in the same time 
- **Straight-Through Cable**
- When two machines are connected together 
	- a **Crossover cable used**
	- ![[Pasted image 20230903111948.png]]
- ![[Pasted image 20230903112025.png]]


# Auto MDI-X
- a feature found in many modern Ethernet devices, designed to simplify network connections by automatically detecting and adjusting for the type of Ethernet cable being used, whether it's a straight-through cable or a crossover cable.


# 1000BASE-T, 10GBASE-T
- each pair can operate bidirectional, that's why it is faster
- ![[Pasted image 20230903112508.png]]



# Fibre-Optic Connections 
- ![[Pasted image 20230903112627.png]]
	- ports wit yellow => UTP cables 
	- ports with orange => fiber 
		- SFP (Small form-factor pluggable) transceiver  
		- ![[Pasted image 20230903112804.png]]
	- ![[Pasted image 20230903112818.png]]
		- these are the fiber-optic cables 
		- ![[Pasted image 20230903113004.png]]

- ![[Pasted image 20230903113132.png]]



# Multimode Fiber 
- core diameter is wider than single-mode fiber
- allows multiple angles (modes) of light waves to enter the fiberglass core
- allows longer cables than UTP, but shorter than single-mode fiber 
- cheaper than single-mode fiber (due to cheaper LED-based SFP transmitter)
- ![[Pasted image 20230903113526.png]]


# Single Mode Fiber
- Core diameter is narrower than multimode fiber 
- light enters at a single angle from a laser-based transmitters 
- allow the longest cables 
- more expensive than multimode 


# Fiber-Optic Cable Standards 
- ![[Pasted image 20230903113736.png]]

# UTP vs Fiber-Optic Cabling
- ![[Pasted image 20230903114015.png]]