# System Specification

# Oracle virtual machine link
https://www.virtualbox.org/wiki/Downloads

6GB RAM, 50 GB SSD
Ubuntu 20.04
6vCPU 

# Tools installation for Day 0

Install the tools for now Yosys, iverlog and gtkwave

#Yosys

sudo apt-get update
## first time ur cloneing the git repo .please enter these command
sudo apt install git

git clone https://github.com/YosysHQ/yosys.git

sudo apt install make (If make is not installed please install it)

sudo apt-get install build-essential clang bison flex libreadline-dev gawk tcl-dev libffi-dev git graphviz xdot pkg-config python3 libboost-system-dev libboost-python-dev \
libboost-filesystem-dev zlib1g-dev 

make config-gcc

make

sudo make install

![image alt](https://github.com/plnarasimha/SOC_RTL_GDSII/blob/57b6a01892ce9ebbeaa78871c36764f7a573a64e/Day0/Tools/yosys.png)

#iverilog

sudo apt-get install iverilog

![image alt](https://github.com/plnarasimha/SOC_RTL_GDSII/blob/e057799538180aa885d72925c387865b57236bcf/Day0/Tools/aaa.png)
# gtkwave

sudo apt-get install gtkwave

![image alt](https://github.com/plnarasimha/SOC_RTL_GDSII/blob/e057799538180aa885d72925c387865b57236bcf/Day0/Tools/aab.png)

