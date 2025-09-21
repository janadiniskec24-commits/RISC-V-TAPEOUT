###  RISC-V-Tapeout-Program :

A 20-week hands-on program by VSD & IIT Gandhinagar, guiding you through the complete RISC-V SoC tapeout cycle using Synopsys tools and SCL 180nm PDK.

###  Highlights :

1. RTL Design & Functional Validation

2. Custom IP Integration

3. Full-Chip Gate-Level Simulation

4. Physical Design & Timing Closure

5. Signoff → Tapeout → Post-Silicon Validation

###  Outcome :

Gain the skills to design, implement, and fabricate a RISC-V SoC at a national foundry, supporting India’s Semiconductor Mission.

[Oracle VirtualBox Link](https://www.vlsisystemdesign.com/soc-labs/)

###   Yosys :

```bash
sudo apt update
sudo apt install git make build-essential clang bison flex \
    libreadline-dev gawk tcl-dev libffi-dev graphviz xdot pkg-config \
    python3 libboost-system-dev libboost-python-dev \
    libboost-filesystem-dev zlib1g-dev

git clone --recurse-submodules https://github.com/YosysHQ/yosys.git
cd yosys
make config-clang        
make          
sudo make install
```

![proof](https://github.com/JANADINI/RISC-V-TAPEOUT/blob/main/Week-0/yosys.png)
---

###   Icarus Verilog (iVerilog) :

```bash
sudo apt update
sudo apt install iverilog
```
![proof](https://github.com/JANADINI/RISC-V-TAPEOUT/blob/main/Week-0/iverilog.png)
---

###   GTKWave : 

```bash
sudo apt update
sudo apt install gtkwave
```
![proof](https://github.com/JANADINI/RISC-V-TAPEOUT/blob/main/Week-0/gtkwave.png)
---
### GTKWave Installation Proof :
![proof](https://github.com/JANADINI/RISC-V-TAPEOUT/blob/main/Week-0/gtkwave%20installation%20proof.png)
---


