# RISC-V-SoC-Tapeout_Maaz
Week by week summary of my progress in RISC-V SoC Tapeout Program by VSD
<details>
<summary><h2>Week 0</h2>:</summary>
Summary of the introductary video:
Learned the entire flow of designing a RISC-V SoC, starting with a C code model of its functionalities, then moving to HDL code (usually in Verilog/SystemVerilog/Chisel) while ensuring that the code is synthesizable. The respective HDL blocks are then integrated into an SoC (System-on-Chip). From this, a GDSII file is generated and sent for tapeout. The fabricated chip is assembled on a board with peripherals, and the same C code is run to check if it still provides the intended functionalities,something that must be verified at each step.

<h3>Installing Yosys</h3>
```# Install dependencies
sudo apt-get install git build-essential clang bison flex  \

libreadline-dev gawk tcl-dev libffi-dev graphviz xdot \

pkg-config python3 libboost-system-dev libboost-python-dev \

libboost-filesystem-dev zlib1g-dev make -y

git clone https://github.com/YosysHQ/yosys.git

cd yosys

make

sudo make install

yosys -V ```

![yosys](url)

<h3>Installing iVerilog</h3>
```sudo apt-get update

sudo apt-get install iverilog ```
![iVerilog](url)

<h3>Installing Gtkwave</h3>
```sudo apt-get update
sudo apt install gtkwave```
![GTKWave](url)

