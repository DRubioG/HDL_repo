# FW Modules

These are the FW modules repository.

## Index

- [Generic](#Generic)
- [SD](#SD)
- [FFT/IFFT](#FFT/IFFT)
- [RNG](#RNG)
- [MAC](#MAC)
- [Comms](#Comms)
- [Cores](#Cores)
- [Ethernet](#Ethernet)
- [Floating points](#Floating_points)
- [SpaceWire](#spacewire)
- [MIL-STD-1553]()
- [GMII](#GMII)
- [RoCEv2](#RoCEv2)
- [Jesd204](#Jesd204)
- [PCIe](#PCIe)
- [NIC](#NIC)
- [Other pieces](#Other_pieces)



## Generic

### [Open-logic](https://github.com/open-logic/open-logic)
Open Logic FPGA Standard Library

- Language: VHDL

### [vhdl-dsp-building-blocks](https://github.com/AlbertoMarquillas/vhdl-dsp-building-blocks)
A collection of VHDL digital design building blocks implemented as part of a learning project in digital systems and hardware description. This repository includes 12 exercises covering a wide range of digital design concepts: from basic combinational logic to sequential circuits, filters, and the integration of IP cores.

- Language: VHDL

### [VHDL-extras Library](https://github.com/kevinpt/vhdl-extras)
Flexible VHDL library

- Language: VHDL

### [Hardware-Modeling-Using-VHDL](https://github.com/SamanKhamesian/Hardware-Modeling-Using-VHDL)
This repository will hold source codes for some simple projects based on VHDL language

- Language: VHDL

### [XESS VHDL Library Files](https://github.com/xesscorp/VHDL_Lib)
These are VHDL files for modules that are useful in a variety of larger designs for XESS FPGA boards (and possibly others).

- Language: VHDL


### [PSI Common](https://github.com/paulscherrerinstitute/psi_common)
Common elements for FPGA Design (FIFOs, RAMs, etc.)

- Language: VHDL

## SATA

### [sata_2_host_controller](https://github.com/CoreyChen922/sata_2_host_controller)
Sata 2 Host Controller for FPGA implimentation. SATA is a computer bus interface that connects host bus adapters to mass storage devices such as hard disk drives and optical drives .The SATA Host Controller IP is able to transfer data to and from a SATA device.

- Language: Verilog


### [sata3_host_controller](https://github.com/CoreyChen922/sata3_host_controller)
It is SATA 3 host controller. Using this you can read write to sata3 sdd/hdd from your fpga logic with simple memory like interface.

- Language: Verilog

### [Groundhog](https://github.com/fpgasystems/groundhog)
Groundhog implements a SATA host bus adapter. This Verilog-based project creates an easy-to-use interface between a user circuit on a Xilinx FPGA and a SATA hard drive or SSD.

- Language: Verilog

## NVME

### [NVMeCHA](https://github.com/yhqiu16/NVMeCHA)
NVMeCHA is an ultralow-latency and high-throughput NVMe controller with a highly parallel, pipelined, and scalable architecture that accommodates one admin controller and multiple fully hardware-automated I/O controllers. The admin controller features the software-hardware co-design, where the complex processing of the NVMe admin commands is managed by software whereas the data transmission over PCIe is handled by hardware. This hybrid architecture combines software flexibility and hardware efficiency to reduce CPU resources and improve performance. The I/O controller is designed with a highly parallel and pipelined hardware architecture that allows many NVMe I/O commands to be processed in parallel without any software intervention. Each I/O controller is corresponding to one NVMe I/O queue pair.

- Language: Verilog, VHDL



## SD

### [SD-Card controller](https://github.com/ZipCPU/sdspi)
SD-Card controller, using either SPI, SDIO, or eMMC interfaces

- Language: Verilog

## FFT/IFFT

### [Radix-2 FFT - VHDL Implementation](https://github.com/bugratufan/radix2-fft-vhdl)
VHDL implementation of radix2 fft pipeline algorithm for IEEE-754 single precision floating point data format

- Language: VHDL

### [FFT Verilog](https://github.com/roo16kie/FFT_verilog)
using verilog to implement Fast Fourier Transform

- Language: Verilog

### [Integer FFT/IFFT cores](https://github.com/hukenovs/intfftk)
Fully pipelined Integer Scaled / Unscaled Radix-2 Forward/Inverse Fast Fourier Transform (FFT) IP-core for newest Xilinx FPGAs

- Language: Verilog, VHDL

### [Floating point (FP23) FFT/IFFT cores](https://github.com/hukenovs/fp23fftk)
Floating point Forward/Inverse Fast Fourier Transform (FFT) IP-core for newest Xilinx FPGAs

- Language: Verilog, VHDL

### [r22sdf](https://github.com/nanamake/r22sdf)
Pipeline FFT Implementation in Verilog HDL

- Language: Verilog


### [8-point-FFT-using-Verilog](https://github.com/Dhruv6730/8-point-FFT-using-Verilog)
Implementation of an 8-point fast fourier transform using SystemVerilog Hardware Description Language. 

- Language: Verilog

### [FFT-using-Verilog(RADIX-2)](https://github.com/Devashrutha/FFT-using-Verilog-RADIX-2)
FFT is responsible for converting a signal into individual spectral components and thereby providing frequency information about the signal. The implementation of FFT is vast in the field of Digital Signal Processing and Communication. Verilog implementation of the FFT with reduced generation logic or reduced complexity is the proposed architecture, where the two inputs and two outputs of butterflies can be used to exchange all data and addresses in FFT dispensation.

- Language: Verilog

### [32-point-FFT-Verilog-design-based-DIT-butterfly-algorithm](https://github.com/AhmedAalaaa/32-point-FFT-Verilog-design-based-DIT-butterfly-algorithm)
This project aims to design an 32-point FFT (Fast Fourier Transform) based DIT (decimation in time) Butterfly Algorithm with multiple clock domains and time-shared design

- Language: Verilog

### [dblclockfft](https://github.com/ZipCPU/dblclockfft)
A configurable C++ generator of pipelined Verilog FFT cores

- Language: Verilog

### [Fast Fourier Transform using Cooley-Tukey Algorithm in Verilog](https://github.com/AugustinJose1221/FFTx32)
A 32 point radix-2 FFT module written in Verilog

- Language: Verilog

### [FFT](https://github.com/Jefferson-Lopes/FFT)
FFT algorithm implementation on an FPGA for processing 2^N points from the BINGO telescope.

- Language: Verilog

### [FFT64](https://github.com/vtsal/fft64)
VHDL FPGA implementation for 64-point FFT using 18-bit fixed-point arithmetic

- Language: VHDL

### [DFT32](https://github.com/vtsal/dft32)
32-point DFT using 18-bit fixed point arithmetic with single-cycle complex multiply-accumulates

- Language: VHDL

### [32 BIT FFT](https://github.com/steinmatt/vhdl_32bit_fft)
32 Bit FFT built in VHDL for ELEC 598 in Spring 2019

- Language: VHDL

### [VHDL_cooley-tukey_fft](https://github.com/guilbaudl/VHDL_cooley-tukey_fft)
VHDL implementation of a 8-points FFT using Cooley-Tukey algorithm during academic lessons with Martin Deshardillier, my classmate.

- Language: VHDL

### [High Throughput FFT Implementation](https://github.com/benreynwar/htfft)
A high throughput FFT implementation

- Language: VHDL


### [fpga-fft](https://github.com/owocomm-0/fpga-fft)
A highly optimized streaming FFT core based on Bailey's 4-step large FFT algorithm

- Language: VHDL

### [FFT for Xilinx Spartan 6 FPGA](https://github.com/Rookfighter/fft-spartan6)
An implementation of the FFT for the Spartan 6 FPGA.

- Language: VHDL

### [VHDL modular FFT radix 2](https://github.com/sampai97/Modular-FFT-radix-2)
VHDL modular Fast Fourier Transform based on Cooley-Tukey algorithm

- Language: VHDL


## [SpaceFFT](https://github.com/milovanovic/SpaceFFT)
Signal Processing ACcElerator For Fast Target detection

- Language: Scala

## [Verilog-Implementation-of-a-32-point-IFFT-Circuit](https://github.com/alice820621/Verilog-Implementation-of-a-32-point-IFFT-Circuit/tree/master)
A FIFO structure is implemented to hold input and output data. There are 32 pairs of real and imaginary inputs, consisting of 4-bit integer and 24-bit decimal values each. The 32-point IFFT has 5 layers with 32 butterflies each. The device operates with a speed of 200MHz.

- Language: Verilog


## [Design and Implementation of 64-point Fast Fourier Transform (FFT/IFFT) Chip for OFDM-based 802.11a WLAN](https://github.com/hibagus/64pointFFTProcessor)
Synthesizeable VHDL and Verilog implementation of 64-point FFT/IFFT Processor with Q4.12 Fixed Point Data Format.

- Language: Verilog

## [pipelined_fft_256](https://github.com/freecores/pipelined_fft_256)
Pipelined FFT/IFFT 256 points processor

- Language: Verilog

## [Fast-Fourier-Transform](https://github.com/ameyk1/Fast-Fourier-Transform)
16-Point FFT is developed in order to accurately model that of the MATLAB function. . The module successfully tested using verilog testbenches in the simulation and compared with Matlab generated output.

- Language: Verilog

## [Butterfly-DFT](https://github.com/janbbeck/Butterfly-DFT)
This is a butterfly discrete Fourier transform in Verilog

- Language: Verilog


## [Integer SPDF-FFT/IFFT Radix-2](https://github.com/hukenovs/intfft_spdf)
Integer (Scaled / Unscaled) Radix-2 Single Path Delay Feedback (SPDF) FFT / IFFT cores

- Language: VHDL







## Cyphers

### [FPGA implementation of Chinese SM4 encryption algorithm](https://github.com/gongxunwu/sm4-verilog)
This project is an implementation of Chinese SM4 (also known as sms4) encryption algorithm.

- Language: Verilog


### [FPGA SM3 HASH](https://github.com/gongxunwu/sm3-verilog)
This is an implementation of Chinese SM3 hash algorithm.

- Language: Verilog

### [ascon_lwc_aead](https://github.com/vtsal/ascon_lwc_aead)
Ascon AEAD with Basic Iterative Architecture in LWC API

- Language: VHDL

### [blake2](https://github.com/secworks/blake2)
Hardware implementation of the blake2 hash function

- Language: Verilog

### [blake3](https://github.com/secworks/blake3)
Hardware implementation of the Blake3 hash function

- Language: Verilog

### [xchacha](https://github.com/secworks/xchacha)
Hardware implementation of the extended-nonce ChaCha stream cipher

- Language: Verilog


### [vndecorrelator](https://github.com/secworks/vndecorrelator)
A Verilog implementation of a von Neumann decorrelator

- Language: Verilog


### [sha512](https://github.com/secworks/sha512)
Verilog implementation of the SHA-512 hash function.

- Language: Verilog


### [sha1](https://github.com/secworks/sha1)
Verilog implementation of the SHA-1 cryptgraphic hash function.

- Language: Verilog


### [stream_cipher](https://github.com/jgaztelu/stream_cipher)
Hardware implementation of Grain128a and Espresso ciphers

- Language: VHDL





## Filters

### [Symmetric FIR Filter Implementation in Verilog](https://github.com/yigitbektasgursoy/symmetric_FIR_Filter_Verilog)
A pipelined Symmetric FIR (Finite Impulse Response) filter implementation in Verilog HDL.

- Language: Verilog

### [FIR-Filter-VHDL-Implementation](https://github.com/ZiliottoFilippoDev/FIR-Filter-VHDL-Implementation)
FPGA implementation via VHDL and Python simultation for a low-pass FIR Filter. Testbenches before the implmentation are also available.

- Language: VHDL

### [VHDL-FIR-filters](https://github.com/BBN-Q/VHDL-FIR-filters)
Synthesizable FIR filters in VHDL

- Language: VHDL

### [FIR Filter](https://github.com/mirawara/FIR-Filter)
Digital circuit that implements a low-pass Finite Impulse Response (FIR) filter of order N (N=7).

- Language: VHDL

### [FIR Filter With VHDL](https://github.com/geoalx/FIR-VHDL)
The concept of this project is to design different implementations of the same FIR filter (more about FIR filters here) using VHDL for the Xilinx Zynq 7000 Soc and compatible with Zybo Z7 development board. The FIR filter is build with 8 bit numbers and with 8 coefficients. The system has an input of 8 bits and aoutput of 19 bits.

- Language: VHDL

### [PMOD I2S implementation with FIR filter](https://github.com/aidinattar/PMOD-FIR-filter-VHDL)
Implementation of a FIR-filter on a FPGA and its employment in an audio system obtained using a PMOD I2S2.

- Language: Verilog


### [FIR-Filter-in-Verilog](https://github.com/Divyansh03/FIR-Filter-in-Verilog)
8-Bit FIR Filter in Verilog using Pipelining

- Language: Verilog

### [Low-Pass FIR Filter](https://github.com/samiyaalizaidi/FIR-Filter)
Implementation of a low-pass FIR filter in Verilog HDL.

- Language: Verilog


### [Verilog-FIR](https://github.com/Grootzz/Verilog-FIR)
FIR implemention with Verilog

- Language: Verilog

### [Digital-Design-of-FIR-Filter-Transposed-Structure](https://github.com/basemhesham/Digital-Design-of-FIR-Filter-Transposed-Structure)
Design and Validation of a Customizable 50th-Order Low-Pass FIR Filter. Transitioning from MATLAB Modeling to Verilog RTL Design and simulation Testing.

- Language: Verilog

### [FIR-filter](https://github.com/ZhipengFan1407/FIR-Filter)
A 64-tap 16-bit FIR filter in Verilog.

- Language: Verilog

### [FIR Filter](https://github.com/TristanSaidi/FIR-Filter-Verilog)
FIR Filter

- Language: Verilog

### [Fixed Point FIR Verification](https://github.com/bvsnithin/fixed-point-fir-verification)
This project demonstrates how a digital signal processing block can be modeled in MATLAB and then validated against its hardware implementation written in Verilog. A simple FIR filter is used as the example, with emphasis on fixed-point behavior.

- Language: Verilog

### [IIR Filter Synthesizable Unit Specifications](https://github.com/jg-fossh/IIR_FILTER)
IIR Parallel Filter

- Language: Verilog

### [iir-bandstop-filter](https://github.com/amoudgl/iir-bandstop-filter)
Implementation of pipelined IIR bandstop filter in Verilog, C++ and MATLAB with fixed point arithmetic

- Language: Verilog

### [Multi_IIR](https://github.com/delhatch/Multi_IIR)
Multi-band IIR filter in Verilog. Uses time-domain multiplexing of a single, fixed-point, IIR filter to create a 27-band filter.

- Language: Verilog

### [Discrete-Time IIR Filter (lowpass - real)](https://github.com/aignacio/iir_filter)
IIR Lowpass Filter

- Language: Verilog

### [IIR_EQ](https://github.com/delhatch/IIR_EQ)
IIR audio filter in Verilog, running on Zedboard. Fractional integer coefficients.

- Language: VHDL

### [1st-Order IIR Filter (AXI-Stream) on FPGA](https://github.com/VRM21-Studios/IIR-1st-Order-Module-FPGA)
A first-order IIR filter for 16-bit PCM stereo data implemented on an FPGA with fixed-point representation.

- Language: Verilog

### [IIR-Filter](https://github.com/ckevar/IIR-Filter)
IIR Filter for audio application

- Language: VHDL

### [IIR-Bandpass-VHDL](https://github.com/axmora/IIR-Bandpass-VHDL)
IIR Bandpass filter designed in MATLAB and adapted into VHDL made as final pregrade project for Electronic and Automation degree granted by ESPOL

- Language: VHDL

### [VIIRF](https://github.com/MauererM/VIIRF)
Hardware description (VHDL) and configuration scripts (Python) of a versatile IIR Filter implemented as cascaded SOS/biquads. No vendor-specific hardware constructs used.

- Language: VHDL


### [FPGA-Audio-IIR](https://github.com/YetAnotherElectronicsChannel/FPGA-Audio-IIR)
IIR-filters for audio signal processing in a FPGA.

- Language: VHDL

### [IIR Filter on FPGA](https://github.com/gabrielebaris/iir-audio-filter-fpga)
Academic project for the course of Digital Systems Design. The aim of the project was to design and implement an IIR audio filter on FPGA

- Language: VHDL

### [IIR Filter IP](https://github.com/NuclearKev/iir-hardware)
Xilinx Vivado IIR Filter Compiler IP

- Language: VHDL


## RNG

### [The neoTRNG True Random Number Generator](https://github.com/stnolting/neoTRNG)
A Tiny and Platform-Independent True Random Number Generator for any FPGA (and ASIC).

- Language: VHDL

### [chaotic-rngs](https://github.com/bluemurder/chaotic-rngs)
Random number generators based on chaotic functions

- Language: VHDL

### [Whirlyfly](https://github.com/zdavkeos/whirlyfly)
Hardware RNG for Papilio One based on the original Whirlygig

- Language: VHDL

### [Burning Down the House: HDL Implementation of a TRNG Ring Oscillator](https://github.com/maxwell-bland/ring-oscillator)
Implementation of a ring oscillator in VHDL.

- Language: VHDL

### [Modelsim-Mersenne-Twister](https://github.com/htminuslab/Modelsim-Mersenne-Twister)
Adding strong RNG to Modelsim via the FLI

- Language: VHDL

### [OpenTRNG](https://github.com/opentrng/ptrng)
This project provides the community with reference implementations of Physical TRNGs (PTRNGs) based on ring oscillators, designed to be transparent, reproducible, and easy to experiment with.

- Language: VHDL

### [trng](https://github.com/secworks/trng)
This repo contains the design of a True Random Number Generator (TRNG) for the Cryptech OpenHSM project.

- Language: Verilog


### [Random-Number-Generator](https://github.com/aniket0511/Random-Number-Generator)
Hardware implementation of Random Number Generator using Verilog HDL

- Language: Verilog



### [TRNG-with-Ring-Oscillators-in-Verilog](https://github.com/adnanbaysal/TRNG-with-Ring-Oscillators-in-Verilog)
A true random number generator with ring oscillators structure written in VHDL targeting FPGA's.

- Language: Verilog


### [[128-bit] FPGA Implementation of an Asynchronous Quasi-Random Number Generator Using Linear-feedback Shift Registers and Mousetrap Logic](https://github.com/rodrigowue/128bit-async-qrng)
LFSRs are well-known circuits for generating pseudo-random sequences. At every cycle of the clock, you have a different value. However, the circuit presented in this work uses an asynchronous implementation (clockless) to mask the cycle and decrease the predictability after a certain amount of time. The PVT variations in this circuit will cause a displacement in time of each code for the pseudo-sequence, so the worst is the ring (in terms of variability), the better it is in terms of it is randomness.

- Language: VHDL

### [[128-bit] Pseudo Random Number Generator Using Linear-feedback Shift Registers](https://github.com/rodrigowue/128bit-prng)
[128bit] PRNG Using LFSRs (Linear-feedback Shift Register)

- Language: VHDL


### [COSO-TRNG](https://github.com/KULeuven-COSIC/COSO-TRNG)
Reference implementation for the COherent Sampling ring Oscillator based True Random Number Generator.

- Language: Verilog

### [FPGA true random number generator](https://github.com/esynr3z/strng)
FPGA implementation of true random generator on Self-timed Rings

- Language: Verilog

### [True Random Number Generator (TRNG) for TinyTapeout ASIC Design](https://github.com/engrbilal992/tt10-TRNG)
This project implements a True Random Number Generator (TRNG) for an ASIC design targeting TinyTapeout. The TRNG utilizes a noise source, a sampler, an 8-bit collector, and a SHA-256 conditioning module to produce high-quality random numbers suitable for cryptographic applications.

- Language: Verilog

### [verilog-trivium](https://github.com/ppashakhanloo/verilog-trivium)
Implementation of Trivium - a random bit generator

- Language: VHDL

### [figaro](https://github.com/secworks/figaro)
Implementation of the FiGaRO TRNG for FPGAs

- Language: Verilog


### [TRNG-True-Random-Number-Generator-in-Verilog](https://github.com/Gautham-8066/TRNG-True-Random-Number-Generator-in-Verilog)
This repository contains a synthesizable Verilog implementation of a True Random Number Generator

- Language: Verilog

 


## Cordic

### [CORDIC VHDL](https://github.com/LucasJSch/cordic_vhdl)
Implementation of CORDIC-algorithm with VHDL.

- Language: VHDL

### [VHDL CORDIC](https://github.com/pashwin92/vhdl-cordic)
VHDL CORDIC

- Language: VHDL

### [Cordic](https://github.com/freecores/cordic)
CORDIC core

- Language: VHDL

### [Cordic DDS](https://github.com/jgibbard/cordic_dds_vhdl)
Generates sine and cosine signals using a pipelined cordic method.

- Language: VHDL

### [Cordic VHDL](https://github.com/nachocarballeda/cordic_vhdl)
Cordic system implemented in VHDL FPGA (Spartan3E)

- Language: VHDL

### [Cordic](https://github.com/sadrasabouri/CORDIC)
Implementation of CORDIC Algorithms Using Verilog

- Language: Verilog

### [Cordic](https://github.com/cebarnes/cordic)
An implementation of the CORDIC algorithm in Verilog.

- Language: Verilog

### [Cordic Verilog](https://github.com/cassuto/CORDIC-all-in-one-verilog)
FPGA version of CORDIC algorithm that evaluates all the trigonometric and anti-trigonometric functions.

- Language: Verilog

### [Cordic Processor Verilog](https://github.com/Hrushti/Cordic-Processor-in-Verilog)
Cordic (Volder's algorithm) is an iterative method to compute a wide range of mathematical functions. It stands for COordinate Rotation DIgital Computer.

- Language: Verilog

### [Pipelined CORDIC Engine in Verilog](https://github.com/Pranav-2045/CORDIC)
This repository contains a synthesizable, 16-bit, 16-stage pipelined CORDIC (Coordinate Rotation Digital Computer) engine written in Verilog. It's designed to calculate the sine and cosine of a given input angle with high throughput, making it ideal for applications in Digital Signal Processing (DSP), communications, and real-time control systems.

- Language: Verilog

### [Cordic Unit](https://github.com/SudeepJoshi22/CORDIC-Unit)
CORDIC Unit designed in Verilog HDL. Completely reconfigurable with the number of iterations and Qm.n format

- Language: Verilog


## MAC

### [INT_FP_MAC](https://github.com/erihsu/INT_FP_MAC)
The design is a multiplier accumulator (MAC) support both INT8 and FP16 data format. The whole design is ASIC-specific and fully sythesizable independent of any IPs.

- Language: Verilog

### [MAC_Verilog](https://github.com/roo16kie/MAC_Verilog)
Using verilog to implement MAC (Multiply Accumulate) . Verifying it by testbench .

- Language: Verilog

### [Floating-point-MAC-verilog](https://github.com/Parimala6/Floating-point-MAC-verilog)
The proposed MAC unit is implemented in Xilinx ISE Design suite 2018.2 on ZedBoard Zynq Evaluation and Development Kit (xc7z020clg484-1). Both Floating Point adder and multiplier are fully synthesizable. The above approach has been adapted from [Implementation of 32 Bit Floating Point MAC Unit to Feed Weighted Inputs to Neural Networks].

- Language: Verilog

### [Floating-MAC-in-verilog](https://github.com/Ho97/Floating-MAC-in-verilog)
Floating mac from half precision inputs to single precision output

- Language: Verilog



## Comms

### [digital-radio-vhdl](https://github.com/AlbertoMarquillas/digital-radio-vhdl)
A complete QPSK transmitter designed and implemented in VHDL. This repository organizes the source code, testbenches, and documentation of a full digital radio chain, originally developed as a university practice, but restructured and documented as a standalone project.

- Language: VHDL


## Cores

### [nano-cpu32k](https://github.com/cassuto/nano-cpu32k)
Linux-capable superscalar out-of-order RISC core (with Cache& MMU) and SoC, having been verified on Xilinx Kintex-7 FPGA.

- Language: Verilog


### [PicoRV32](https://github.com/YosysHQ/picorv32)
PicoRV32 is a CPU core that implements the RISC-V RV32IMC Instruction Set. It can be configured as RV32E, RV32I, RV32IC, RV32IM, or RV32IMC core, and optionally contains a built-in interrupt controller.

- Language: Verilog

### [Rudi-RV32I](https://github.com/hamsternz/Rudi-RV32I)
A rudimental RISCV CPU supporting RV32I instructions, in VHDL

- Language: VHDL


### [RISCV HDL](https://github.com/sergeykhbr/riscv_vhdl)
Portable RISC-V System-on-Chip implementation: RTL, debugger and simulators

- Language: Verilog, VHDL

### [RISCY](https://github.com/mongrelgem/RISCY)
Simple RISC-V RV32I CPU in VHDL for use in FPGA Designs

- Language: VHDL


### [Altor32](https://github.com/ultraembedded/altor32)
AltOR32 is an OpenRISC 1000 architecture derived RISC CPU targeted at small FPGAs and contains only the most basic ISA features from the OpenRisc project. Instructions & registers relating to Vector, floating-point, 64-bit extensions, MMU & Cache have been omitted. The aim of AltOR32 is to provide a simple 32-bit soft CPU architecture aimed at control applications that can fit in low-end FPGA technology.

- Language: Verilog

### [The NEORV32 RISC-V Processor](https://github.com/stnolting/neorv32)
A small, customizable and extensible MCU-class 32-bit RISC-V soft-core CPU and microcontroller-like SoC written in platform-independent VHDL.

- Language: VHDL


### [XCrypto: a cryptographic ISE for RISC-V](https://github.com/scarv/xcrypto)
XCrypto: a cryptographic ISE for RISC-V

- Language: Verilog


### [Custom_MIPS_Processor_using_VHDL_with_RC5_Cipher](https://github.com/akhilwadhwa22/Custom_MIPS_based_Processor_using_VHDL_with_RC5_Cipher)
Implemented a processor with RC5 Key-Expansion, Encryption and Decryption running on it using VHDL.

- Language: VHDL

### [AVR-Processor](https://github.com/agural/AVR-Processor)
VHDL implementation of an AVR processor.

- Language: VHDL

### [LEON2](https://github.com/Galland/LEON2)
LEON2 SPARC CPU IP core LGPL by Gaisler Research

- Language: VHDL


### [RV12](https://github.com/RoaLogic/RV12)
The RV12 is a highly configurable single-issue, single-core RV32I, RV64I compliant RISC CPU intended for the embedded market. The RV12 is a member of the Roa Logic’s 32/64bit CPU family based on the industry standard RISC-V instruction set

- Language: Verilog

### [NoX RISC-V Core](https://github.com/aignacio/nox)
RISC-V Nox core

- Language: Verilog


### [MIPS-VHDL-Vivado](https://github.com/IgnacioChirinos/MIPS-VHDL-Vivado)
MIPS processor that performs matrix multiplication 3x3 based on VHDL and implemented in XILINX

- Language: VHDL



## Ethernet

### [Gigabit Ethernet Application Note](https://github.com/enclustra/GigabitEthernetAppNote)
Gigabit Ethernet

- Language: VHDL

### [Custom 10GBASE-R PHY (VHDL)](https://github.com/adilsondias-engineer/33-fpga-10gbe-phy-custom)
A complete custom implementation of the 10GBASE-R Physical Layer (PHY) in VHDL. This implementation provides full control over the 10 Gigabit Ethernet physical layer without relying on encrypted vendor IP.

- Language: VHDL

### [XGbE_lib](https://github.com/staerz/XGbE_lib)
This repository provides XGbE_lib, a VHDL library for 10 GbE supporting UDP/IP and embedded support for ARP, ICMP and DHCP.

- Language: VHDL

### [verilog-ethernet](https://github.com/alexforencich/verilog-ethernet)
Verilog Ethernet components for FPGA implementation

- Language: Verilog

### [10/100/1000 VHDL Ethernet MAC](https://github.com/yol/ethernet_mac)
Tri-mode (10/100/1000) full-duplex FPGA ethernet MAC in VHDL

- Language: VHDL

### [Ethernet Mac - VHDL Implementation](https://github.com/pabennett/ethernet_mac)
A VHDL implementation of an Ethernet MAC

- Language: VHDL


### [LMAC_CORE3](https://github.com/lewiz-support/LMAC_CORE3)
Ethernet MAC IP Core for 100G/50G/40G/25G/10Gbps

- Language: VHDL

### [gigabit_ethernet](https://github.com/hVHDL/hVHDL_gigabit_ethernet)
VHDL library for synthesizable minimal gigabit ethernet with RGMII interface, minimal ethernet, ip and udp header parsers.

- Language: VHDL

### [1000BASE-X](https://github.com/freecores/1000base-x)
1000BASE-X IEEE 802.3-2008 Clause 36 - Physical Coding Sublayer (PCS)

- Language: Verilog


### [An Open Source 10Gb Ethernet Switch](https://github.com/ZipCPU/eth10g)
The main goal of this project is to demonstrate a 10Gb Ethernet switch. Packets will arrive in one of four SFP+ interfaces, and from there be routed as appropriately.

- Language: Verilog


### [Passe_Passe](https://github.com/0xArt/Passe_Passe_Network_Switch)
A FPGA Layer 2 network switch that supports virtual ports for efficient UDP data transmission and reception. The use of virtual ports facilitates seamless integration with various applications requiring UDP communication, optimizing performance and reducing latency in real-time data transfer scenarios. It currently supports RMII and RGMII interfaces, offering flexibility across Ethernet standards. This design enables dynamic resource management without hardware changes, ideal for high-performance networking environments requiring low latency and real-time communication.

- Language: Verilog

### [MII to RMII and MII to SMII](https://github.com/WangXuan95/FPGA-RMII-SMII)
An FPGA-based MII to RMII & SMII converter to connect 100M ethernet PHY chip such as LAN8720 or KSZ8041TLI-S

- Language: Verilog




## Floating point

### [32-bit Single Precision Floating Point Adder](https://github.com/prashal/fp_adder)
Floating Point Adder in VHDL and Verification of result with matlab code

- Language: VHDL


### [Floating Point adder](https://github.com/RockingAayush/32bit-floating-point-adder)
Floating Point adder

- Language: Verilog


### [Floating-Point-Adder](https://github.com/shahsaumya00/Floating-Point-Adder)
32 bit pipelined binary floating point adder using IEEE-754 Single Precision Format in Verilog

- Language: Verilog


### [An efficient multi-format low-precision floating-point multiplier](https://github.com/balajirai/Floating-Point-Multiplier/tree/master)
An efficient multi-format low-precision floating-point multiplier

- Language: Verilog

### [Floating-Point-multiplier](https://github.com/remusbompa/Floating-Point-multiplier)
Implemented in VHDL a floating point multiplier which receives two IEEE 754 normalized numbers and return the product in IEEE 754 format. The designed is based on a 3-stages pipeline: add exponents and multiply mantissas, correct the exponent, normalize and adjust exponent. To increase performance, it uses a multiplication matrix circuit for binary multiplication of mantissas.

- Language: VHDL


### [Floating Point Single Precision Multiplier in SystemVerilog](https://github.com/tsarnadelis/HW2Project)
This project implements a floating point single precision multiplier in SystemVerilog. The implementation is divided into several modules, each handling different aspects of the multiplication process. Additionally, testbenches are provided to verify the functionality and correctness of the multiplier.

- Language: SystemVerilog

### [Logic Networks final test Polimi - ENG](https://github.com/pitesse/IEEE754-floating-point-multiplier)
Hardware-accurate IEEE 754 floating-point multiplier implementation (VHDL/Verilog), optimized for precision, low-latency and pipeline alignment

- Language: Verilog, VHDL


### [IEEE-754-Standard-64-bits-Floating-point-multiplication](https://github.com/Tsai-Cheng-Hong/IEEE-754-Standard-64-bits-Floating-point-multiplication-)
IEEE 754 Standard(64-bits Floating point multiplication) 浮點數乘法 完成階段:Post-Layout

- Language: Verilog


### [A SYNTHESIZABLE VHDL FLOATING-POINT PACKAGE](https://github.com/xesscorp/Floating_Point_Library-JHU/tree/master)
The FloatPt.vhd file contains all the components used to implement arithmetic operations with 32-bit IEEE standard floating-point numbers, along with the FloatPt package which contains all the declarations and functions to use the components. The components include FPP_MULT (for multiplication), FPP_ADD_SUB (for addition and subtraction) FPP_DIV (for division), and MantissaDivision (mantissa non-restoring division used in the FPP_DIV component). The package contains two functions: SIGNED_TO_FPP and FPP_TO_SIGNED for converting N-bit signed vectors to and from floating-point numbers, respectively.

- Language: VHDL

### [FPU Single and Double Precision](https://github.com/taneroksuz/fpu)
This floating point unit is conform to IEEE 754-2008 standards. Supported operations are compare, min-max, conversions, addition, subtruction, multiplication, fused multiply add, square root and division in single and double precisions. Except square root and division all operations are pipelined.

- Language: Verilog, VHDL


### [High level vhdl floating point library](https://github.com/hVHDL/hVHDL_floating_point)
high level VHDL floating point library for synthesis in fpga

- Language: VHDL

### [FPU-IEEE-754](https://github.com/akilm/FPU-IEEE-754)
Synthesizable Floating point unit written using Verilog. Supports 32-bit (Single-Precision) Multiplication, Addition and Division and Square Root Operations based on the IEEE-754 standard for floating point numbers

- Language: Verilog

### [Floating-Point-ALU-in-Verilog](https://github.com/nishthaparashar/Floating-Point-ALU-in-Verilog)
32-Bit Algorithms of Floating Point Operations are implemented on Verilog with logic Operations.

- Language: Verilog





## GMII

### [GMII-Packet-Generator-VHDL](https://github.com/Maeur1/GMII-Packet-Generator-VHDL)
A Packet Generator using VHDL to make Gigabit level traffic

- Language: VHDL

### [RGMII_Ethernet_Transceiver_Verilog](https://github.com/0xArt/RGMII_Ethernet_Transceiver_Verilog)
Verilog module to transmit/receive to/from RGMII compatible ethernet PHY

- Language: Verilog



## RoCEv2

### [100G RoCE2](https://github.com/Gabriele-bot/100G-verilog-RoCEv2-lite)
TX only RoCEv2. Super stripped down version of a RoCEv2 endpoint. Up to now only RC RDMA WRITE (with and without IMMEDIATE) RC SEND(with and without IMMEDIATE) are supported . RX part is there only to read ACKs and NAKs.

- Language: Verilog


## Jesd204

### JESD204B

#### [JESD204B Transport and Data Link Layer](https://github.com/Anthon1e/JESD204B-Transport-and-Data-Link-Layer)
This is a serialized interface between data converters (ADC/DAC) and logic devices (FPGA/ASIC). To further understand, this device specification has been divided into layers, including Application Layer, Transport Layer, Data Link Layer and Physical Layer. This repository will focus on the Transport Layer, the optional Scramber/Descrambler block and the 8B/10B Encode in the Data Link Layer. The section in Data Link Layer which deals with synchronization and alignment (CGS, ILAS, IFAS), are also developed but are left separately in another folder. This is because I am not sure what user data from an ADC would look like to write test cases accurately enough for the simulation. However, the implementation would still work for any inputs.

- Language: Verilog


## Aurora

### [aurora_64b66b-vhdl-sim](https://github.com/mnemocron/aurora_64b66b-vhdl-sim)
VHDL files to simulate the Aurora 64b66b protocol in Xilinx Vivado

- Language: Verilog, VHDL


### [Aurora RAW](https://github.com/MEEPproject/aurora-raw)
FPGA Shell aurora point to point solution

- Language: VHDL


### [Aurora](https://github.com/wolve265/aurora)
Implementation of the Aurora 8b/10b Simplex Transmitter

- Language: SystemVerilog


## PCIe

### [VerCoLib-PCIe](https://github.com/TI-Bonn/vercolib_pcie)
The Versatile Communication Library is a collection of VHDL modules to enable DMA data transfer over PCIe.

- Language: VHDL



### [PCIE Transaction Layer Verification](https://github.com/crusader2000/PCIE-Transaction-Layer-Verification)
PCIe System Verilog Verification Environment developed for PCIe course

- Language: SystemVerilog

### [KC705_pci_driver](https://github.com/GuillaumeTrebuchet/KC705_pci_driver)
Very simple pci-express driver for my FPGA board

- Language: VHDL

### [VerCoLib-PCIe](https://github.com/TI-Bonn/vercolib_pcie)
The Versatile Communication Library is a collection of VHDL modules to enable DMA data transfer over PCIe.

- Language: VHDL

### [Xilinx FPGA PCIe-XDMA Tutorial](https://github.com/WangXuan95/Xilinx-FPGA-PCIe-XDMA-Tutorial)

- Language: Other


### [VPIE](https://github.com/texane/vpcie)
implement PCIE devices using C or VHDL and test them against a QEMU virtualized architecture

- Language: VHDL








## NIC

### [Corundum](https://github.com/corundum/corundum)
Corundum is an open-source, high-performance FPGA-based NIC and platform for in-network compute. Features include a high performance datapath, 10G/25G/100G Ethernet, PCI express gen 3, a custom, high performance, tightly-integrated PCIe DMA engine, many (1000+) transmit, receive, completion, and event queues, scatter/gather DMA, MSI interrupts, multiple interfaces, multiple ports per interface, per-port transmit scheduling including high precision TDMA, flow hashing, RSS, checksum offloading, and native IEEE 1588 PTP timestamping. A Linux driver is included that integrates with the Linux networking stack. Development and debugging is facilitated by an extensive simulation framework that covers the entire system from a simulation model of the driver and PCI express interface on one side to the Ethernet interfaces on the other side.

- Language: Verilog



## SpaceWire

### [SpaceWire Light](https://github.com/freecores/spacewire_light)
SpaceWire Light is a SpaceWire encoder-decoder.
It is synthesizable for FPGA targets (up to 200 Mbit on Spartan-3).
Application interfaces include a simple FIFO interface, as well as
an AMBA bus interface for LEON3 system-on-chip designs.

- Language: VHDL


### [SpaceWire](https://github.com/freecores/spacewire)

- Language: Verilog

### [SpaceWireToGigabitEther](https://github.com/yuasatakayuki/SpaceWireToGigabitEther)
SpaceWire-to-GigabitEther is an interface to SpaceWire networks for PC software via GigabitEthernet. Users can send/receive SpaceWire packets from/to a user program running on an ordinary PC to/from a SpaceWire node or router connected to the device. The class library written in C++ is also available for user programs which run on the PC. Using the library, users can perform Remote Memory Access Protocol (RMAP) to RMAP Target nodes connected to the converter through the SpaceWire network. This device is not flight qualified, but originally intended for SpaceWire/RMAP-based data acquisition system of scientific experiments and ground tests of flight modules which use SpaceWire interfaces.


### [SpaceWireCODECIP_100MHz](https://github.com/shimafujigit/SpaceWireCODECIP_100MHz)
SpaceWire IP codec

- Language: VHDL


### [Open-source SpaceWire RMAP IP Core ](https://github.com/shimafujigit/SpaceWireRMAPTargetIP)
SpaceWire Remote Memory Access Protocol

- Language: VHDL

### [Open-source SpaceWire Router IP Core 6Port Version ](https://github.com/shimafujigit/SpaceWireRouterIP_6PortVersion)
Open-source SpaceWire Router IP Core 6Port Version 

- Language: VHDL

### [SpaceWireRouter](https://github.com/AranelLindi/SpaceWireRouter)
Fully functional SpaceWire router. Implemented in VHDL and under continuous development. See manual. Repository also contains a UART-SpaceWire adapter and several implementation files including constraints for Xilinx FPGAs.

- Language: VHDL

### [AXI_SpaceWire_IP](https://github.com/AranelLindi/AXI_SpaceWire_IP)
Standalone IP with ARM-AMBA/AXI capable device. Enables sending and receiving data via SpaceWire protocol. Tested on Xilinx FPGA (ZYNQ).

- Language: VHDL



## MIL-STD-1553

### [open1553](https://github.com/johnathan-convertino-afrl/open1553)
Projects for building MIL-STD-1553 communications devices

- Language: Verilog

### [MS1553_Firmware](https://github.com/phillipjohnston/1553-Firmware)
Contains VHDL implementing an 8085, Holt HI-6130 1553 IC, and Memory. Also includes firmware used to demo the system.

- Language: VHDL

### [mil-std-1553b-soc](https://github.com/fpga-soc/mil-std-1553b-soc)
development interface mil-std-1553b for system on chip

- Language: Verilog


### [mil1553-spi](https://github.com/zhelnio/mil1553-spi)
MIL-STD-1553 <-> SPI bridge with internal memory buffer support.

- Language: Verilog

### [UART pmod1553 FPGA Project](https://github.com/johnathan-convertino-afrl/uart_pmod1553)
base uart pmod1553 project files without IP.

- Language: Verilog

### [pmod1553](https://github.com/johnathan-convertino-afrl/pmod1553)
PMOD for MIL-STD-1553 bus comms

- Language: Verilog


### [](https://github.com/dointio/1553B_APB)
soc_ip_1553B

- Language: Verilog






## Other pieces

### [8B/10B Encoder/Decoder](https://github.com/Anthon1e/8B-10B-Encoder-Decoder)
8b/10b is a line code that maps 8-bit words to 10-bit symbols to achieve DC-balance and bounded disparity, which is used for telecommunications

- Language: Verilog

### [ADRV9009 Receiver Signal Path (FIR Filters)](https://github.com/Anthon1e/ADRV9009-Receiver-Signal-Path-FIR-Filter)
The ADRV9009 is a highly integrated, radio frequency (RF) transceiver. This is my attempt to implement the signal path on the receiver side, which consists multiple FIR filter designs to prevent data wrapping and overrange conditions.

- Language: Verilog

### [Verilog DSP](https://github.com/alexforencich/verilog-dsp)
Verilog digital signal processing components

- Language: Verilog

## [sv_math](https://github.com/nelsoncsc/sv_math)
Reusable math modules (multiplication, division, square root and logarithm) in SystemVerilog

- Language: SystemVerilog