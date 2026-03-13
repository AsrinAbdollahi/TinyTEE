# TinyTEE
Trusted Execution Environment(TEE) for resource-constrained IoT Devices

## Requierments
- RISC-V GNU Toolchain

```bash
make clean
make launch
make debug
source activate-toolchains.sh
```

- Renode
```bash
git clone https://github.com/renode/renode.git
git clone --recursive https://github.com/riscv-collab/riscv-gnu-toolchain
https://github.com/antmicro/renode-verilator-integration.git
```

- TinyTEE bare metal RISC-V
## RUN
After making sure all three dependencies are installed, run:

```bash
git clone https://github.com/AsrinAbdollahi/TinyTEE.git
cd TinyTEE
make toolchains
source activate-toolchains.sh
make launch
```

## Desceiption
Placeholder for TinyTEE paper; a draft paper about TEE for Low-power IoT devices. 
The code and DETAILS will be uploaded soon! 



