

### 🔹 Yosys

```bash
sudo apt update
sudo apt install git make build-essential clang bison flex \
    libreadline-dev gawk tcl-dev libffi-dev graphviz xdot pkg-config \
    python3 libboost-system-dev libboost-python-dev \
    libboost-filesystem-dev zlib1g-dev

git clone --recurse-submodules https://github.com/YosysHQ/yosys.git
cd yosys
make config-clang        
make -j$(nproc)          
sudo make install
```

---

### 🔹 Icarus Verilog (iVerilog) 

```bash
sudo apt update
sudo apt install iverilog
```

---

### 🔹 GTKWave 

```bash
sudo apt update
sudo apt install gtkwave
```

---


