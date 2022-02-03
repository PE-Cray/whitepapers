## Description
This repository contains whitepapers with in-depth report on specific topics
that are related to Cray Programming Environments softwares.

### Message Passing Toolkit

**MPI Dynamic Process Management**

This document describes the use of MPI Dynamic Process Management or DPM. This
includes _MPI\_Comm\_spawn_, _MPI\_Comm\_connect_, _MPI\_Comm\_accept_ and
related DPM functionality, as well as a Cray extension, _MPIX\_Comm\_rankpool_.

[Download MPI Dynamic Process Management Whitepaper](https://github.com/PE-Cray/whitepapers/raw/master/mpt/mpi-spawn.doc)


**MPICH ABI Compatibility Status for HPE Cray EX Systems**

<p align="justify">
This document describes ANL MPICH ABI Compatibility on HPE Cray EX systems and how to use this capability.
</p>

[Download MPICH ABI Compatibility Status for HPE Cray EX Systems](https://github.com/PE-Cray/whitepapers/raw/master/mpt/ABI_Compat_white_paper_ex.doc)


### Cray OpenSHMEMX

**Introducing Cray OpenSHMEMX**

<p align="justify">
OpenSHMEM is a Partitioned Global Address Space (PGAS) library interface
specification, which is the culmination of a standardization effort among many
implementers and users of SHMEM programming model. SHMEM has a long history as
a parallel programming model. It is extensively used since 1993, starting from
Cray T3D systems. For the past two decades SHMEM library implementation in Cray
systems evolved through different generations. The current generation of the
SHMEM implementation for Cray XC and XK systems is called Cray SHMEM. Cray SHMEM
is a proprietary SHMEM implementation from Cray Inc., which is OpenSHMEM
standard compliant. In this paper, we introduce the next generation OpenSHMEM
implementation for current and future generation Cray systems. We call this new
implementation <b>Cray OpenSHMEMX</b>. In this paper, we provide a brief design
overview of the implementation along with the usage details, functional
differences and performance optimizations over the existing Cray SHMEM
implementation.
</p>

[Download Introducing Cray OpenSHMEMX Whitepaper](https://github.com/PE-Cray/whitepapers/raw/master/cray-openshmemx/introducing-cray-openshmemx.doc)

**Updating Cray Thread-Hot Semantics for OpenSHMEM v1.4**

<p align="justify">
Cray OpenSHMEMX is a proprietary SHMEM implementation which is OpenSHMEM
compliant and includes Cray specific features as part of SHMEMX prefixed
routines. One such feature is the Cray Thread-Hot which improves the performance
of multi-threaded applications where more than one thread issues Puts, Gets or
Atomic Memory Operations (AMOs) using standard SHMEM routines. Support for
multi-threading and OpenSHMEM Communication Context management features were
introduced in OpenSHMEM specification version 1.4. In this work, we provide a
brief overview of the updates made to the Cray Thread-Hot implementation to
coexist with OpenSHMEM v1.4 multi-threading and OpenSHMEM Communication Contexts
features
</p>

[Download Updating Cray Thread-Hot Semantics for OpenSHMEM v1.4 Whitepaper](https://github.com/PE-Cray/whitepapers/raw/master/cray-openshmemx/cray-openshmemx-thread-hot.doc)

**Cray OpenSHMEMX (SMP-DMAPP) on Different CLE Versions**

<p align="justify">
Cray OpenSHMEMX is a proprietary SHMEM implementation which is OpenSHMEM
version 1.4 compliant. Cray OpenSHMEMX build over DMAPP and XPMEM as
communication layers – DMAPP for inter-node operations and XPMEM intra-node
operations. We call this communication layer combination as SMP-DMAPP. In this
work, we provide detailed information on using Cray OpenSHMEMX with SMP-DMAPP
communication layer on different Cray Linux Environment (CLE) operating system
releases for Cray systems.
</p>

<p align="justify">
<b>NOTE:</b> The usage steps discussed in this work are relevant only for
Cray OpenSHMEMX version/8.0.1 and later. And, it is relevant only for SMP-DMAPP
communication layer based Cray OpenSHMEMX builds.
</p>

[Download Cray OpenSHMEMX (SMP-DMAPP) on Different CLE Versions Whitepaper](https://github.com/PE-Cray/whitepapers/raw/master/cray-openshmemx/cray-openshmemx-usage.doc)
