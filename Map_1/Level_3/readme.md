  #  :checkered_flag:Level-3(Day-2):Tools Check

  ## Yosys
 :rocket: Yosys is a lightweight, open-source tool for synthesizing Verilog designs into gate-level netlists or intermediate representations suitable for FPGAs and ASICs.

 ### 📥: Yosys installation
 
 ```
 $ sudo apt-get update
 $ git clone https://github.com/YosysHQ/yosys.git
 $ cd yosys
 $ sudo apt-get install build-essential clang bison flex \
 libreadline-dev gawk tcl-dev libffi-dev git \
 graphviz xdot pkg-config python3 libboost-system-dev \
 libboost-python-dev libboost-filesystem-dev zlib1g-dev
 $ make config-gcc
 ```
 
![Yosys install](/Map_1/Level_3/images/yosys_install.png)
