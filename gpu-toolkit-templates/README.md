# GPU Toolkit Modulefile Templates for Cray PE

## Overview

This whitepaper (and accompanying files) provide some basic example templates for environment modulefiles and pkg-config files for both CUDA and ROCm GPU toolkits to give sysadmins and users a solid headstart in using these toolkits with Cray PE. Assumption here is that these GPU toolkits are already installed on the target system alongside an install of Cray PE. These example templates are intended to be used on systems without a CLE or COS install which typically provides a "cudatoolkit/x.x.x" or "rocm/x.x.x" modulefile on Cray GPU systems.

## Cases Covered
 
**ROCm toolkit**
- In the *rocm_example_template* dir.
- Intended for Cray PE systems with ROCm and vanilla OS install.
- Paired "rocm/x.x.x" modulefile and "rocm-x.x.x.pc" pkg-config file.
 
**CUDA toolkit from an NVIDIA SDK install**
- In the *cuda_sdk_example_template* dir.
- Intended for Cray PE systems with an NVIDIA SDK CUDA toolkit and vanilla OS install.
- Paired "cudatoolkit/x.x" modulefile and "ctk-x.x.pc" pkg-config file.

**CUDA toolkit using a standalone install**
- In the *cuda_standalone_example_template* dir.
- Intended for Cray PE systems with a standalone NVIDIA CUDA toolkit and vanilla OS install.
- Paired "cudatoolkit/x.x" modulefile and "ctk-x.x.pc" pkg-config file.
