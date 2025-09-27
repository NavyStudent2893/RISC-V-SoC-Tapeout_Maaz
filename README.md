# RISC-V-SoC-Tapeout_Maaz
# RISC-V SoC Tapeout Program - Week-by-Week Progress

This repository contains a weekly summary of my progress in the RISC-V SoC Tapeout Program by VSD.

<details>
  <summary><h2>Week 0</h2></summary>
  
  *Summary of the introductory video*:  
  Learned the entire flow of designing a RISC-V SoC, starting with a C code model of its functionalities, then moving to HDL code (usually in Verilog/SystemVerilog/Chisel) while ensuring that the code is synthesizable. The respective HDL blocks are then integrated into an SoC (System-on-Chip). From this, a GDSII file is generated and sent for tapeout. The fabricated chip is assembled on a board with peripherals, and the same C code is run to check if it still provides the intended functionalities, something that must be verified at each step.



---

## Installing Yosys

### Install dependencies

```bash
sudo apt-get install git build-essential clang bison flex  \
libreadline-dev gawk tcl-dev libffi-dev graphviz xdot \
pkg-config python3 libboost-system-dev libboost-python-dev \
libboost-filesystem-dev zlib1g-dev make -y
```

### Clone and build Yosys

```bash
git clone https://github.com/YosysHQ/yosys.git
cd yosys
make
sudo make install
```


### Verify Installation

```bash
yosys -V
```

### Yosys

![yosys](https://raw.githubusercontent.com/NavyStudent2893/RISC-V-SoC-Tapeout_Maaz/refs/heads/main/Screenshot%202025-09-20%20172753.png)

---

## Installing iVerilog

### Install iVerilog

```bash
sudo apt-get update
sudo apt-get install iverilog
```

### iVerilog

![iVerilog](https://raw.githubusercontent.com/NavyStudent2893/RISC-V-SoC-Tapeout_Maaz/refs/heads/main/Screenshot%202025-09-20%20173108.png)

---

## Installing GTKWave

### Install GTKWave

```bash
sudo apt-get update
sudo apt install gtkwave
```

### GTKWave

![GTKWave](https://raw.githubusercontent.com/NavyStudent2893/RISC-V-SoC-Tapeout_Maaz/refs/heads/main/Screenshot%202025-09-20%20183252.png)



  
