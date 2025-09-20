  #  :checkered_flag:Level-3(Day-2):Tools Check

 ## :dart: <b>Objective-1:</b> Install Yosys and validate the installation process(Task-2)
 :rocket: Yosys is a lightweight, open-source tool for synthesizing Verilog designs into gate-level netlists or intermediate representations suitable for FPGAs and ASICs.
 
 ### 📥 Yosys installation
 
 ```
 $ sudo apt-get update
 $ git clone https://github.com/YosysHQ/yosys.git
 $ cd yosys
 $ sudo apt-get install build-essential clang bison flex \
 libreadline-dev gawk tcl-dev libffi-dev git \
 graphviz xdot pkg-config python3 libboost-system-dev \
 libboost-python-dev libboost-filesystem-dev zlib1g-dev
 $ make config-gcc
 $ make
 $ sudo make install
 ```
  ### 🖼️ Installation Validation
![Yosys install](/Map_1/Level_3/images/yosys_install.png)
<div align="center">:trophy:<b>Status:</b>  <mark>Validated Yosys Installation Objective</mark></div>

## :dart: <b>Objective-2:</b> Install IVerilog and validate the installation process(Task-2)
 :rocket: Icarus Verilog is an open-source Verilog simulation and synthesis tool that compiles Verilog HDL designs into simulation executables. It is mainly used for functional simulation of digital circuits.
 ### 📥 IVerilog installation
 
 ```
sudo apt-get update
sudo apt-get install iverilog
 ```
  ### 🖼️ Installation Validation
![Yosys install](/Map_1/Level_3/images/iverilog_install.png)
<div align="center">:trophy:<b>Status:</b>  <mark>Validated iverilog Installation Objective</mark></div>

## :dart: <b>Objective-3:</b> Install GTKWave and validate the installation process(Task-2)
GTKWave is a graphical waveform viewer used to visualize simulation results of digital designs, typically from Verilog, VHDL, or mixed HDL simulations. It helps designers debug and verify digital circuits by displaying signals over time.
### 📥 GTKWave installation
 
 ```
sudo apt-get update
sudo apt-get install gtkwave
 ```
  ### 🖼️ Installation Validation
![Yosys install](/Map_1/Level_3/images/gtkwave_install.png)
<div align="center">:trophy:<b>Status:</b> <mark>Validated GTKWave Installation Objective</mark></div>

## :star: Level Status: 

- All objectives completed.
- SoC design flow begins with these tools.
- 🔓 Next level unlocked(Digital design using verilog,verification and synthesis).
