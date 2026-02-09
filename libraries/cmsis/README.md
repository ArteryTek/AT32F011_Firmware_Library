# CMSIS Version 5

The branch *master* of this GitHub repository contains the CMSIS Version 5.9.0.  The [documentation](http://arm-software.github.io/CMSIS_5/General/html/index.html) is available under http://arm-software.github.io/CMSIS_5/General/html/index.html

Use [Issues](https://github.com/ARM-software/CMSIS_5#issues-and-labels) to provide feedback and report problems for CMSIS Version 5. 

**Note:** The branch *develop* of this GitHub repository reflects our current state of development and is constantly updated. It gives our users and partners contiguous access to the CMSIS development. It allows you to review the work and provide feedback or create pull requests for contributions.

A [pre-built documentation](http://www.keil.com/pack/doc/CMSIS_Dev/index.html) is updated from time to time, but may be also generated using the instructions under [Generate CMSIS Pack for Release](https://github.com/ARM-software/CMSIS_5#generate-cmsis-pack-for-release).

## Other related GitHub repositories

| Repository                  | Description                                               |                
|:--------------------------- |:--------------------------------------------------------- |
| [cmsis-pack-eclipse](https://github.com/ARM-software/cmsis-pack-eclipse)    |  CMSIS-Pack Management for Eclipse reference implementation Pack support  |
| [CMSIS-FreeRTOS](https://github.com/arm-software/CMSIS-FreeRTOS)            | CMSIS-RTOS adoption of FreeRTOS                                                      |
| [CMSIS-Driver](https://github.com/arm-software/CMSIS-Driver)                | Generic MCU driver implementations and templates for Ethernet MAC/PHY and Flash.  |
| [CMSIS-Driver_Validation](https://github.com/ARM-software/CMSIS-Driver_Validation) | CMSIS-Driver Validation can be used to verify CMSIS-Driver in a user system |
| [CMSIS-Zone](https://github.com/ARM-software/CMSIS-Zone)                    | CMSIS-Zone Utility along with example projects and FreeMarker templates         |
| [NXP_LPC](https://github.com/ARM-software/NXP_LPC)                          | CMSIS Driver Implementations for the NXP LPC Microcontroller Series       |
| [mdk-packs](https://github.com/mdk-packs)                                   | IoT cloud connectors as trail implementations for MDK (help us to make it generic)|
| [trustedfirmware.org](https://www.trustedfirmware.org/)                     | Arm Trusted Firmware provides a reference implementation of secure world software for Armv8-A and Armv8-M.|

## Overview of CMSIS Components

The following is an list of all CMSIS components that are available, **but only the useful parts were copied into this package**.

| CMSIS-... | Target Processors   | Description  |
|:----------|:--------------------|:-------------|
|[Core(M)](http://arm-software.github.io/CMSIS_5/Core/html/index.html)  | All Cortex-M, SecurCore | Standardized API for the Cortex-M processor core and peripherals. Includes intrinsic functions for Cortex-M4/M7/M33/M35P SIMD instructions.|
|[Core(A)](http://arm-software.github.io/CMSIS_5/Core_A/html/index.html)| Cortex-A5/A7/A9 | API and basic run-time system for the Cortex-A5/A7/A9 processor core and peripherals.|
|[Driver](http://arm-software.github.io/CMSIS_5/Driver/html/index.html) | All Cortex-M, SecurCore | Generic peripheral driver interfaces for middleware. Connects microcontroller peripherals with middleware that implements for example communication stacks, file systems, or graphic user interfaces.|
|[DSP](http://arm-software.github.io/CMSIS_5/DSP/html/index.html)       | All Cortex-M | DSP library collection with over 60 Functions for various data types: fixed-point (fractional q7, q15, q31) and single precision floating-point (32-bit). Implementations optimized for the SIMD instruction set are available for Cortex-M4/M7/M33/M35P.|
|[NN](http://arm-software.github.io/CMSIS_5/NN/html/index.html)        | All Cortex-M | Collection of efficient neural network kernels developed to maximize the performance and minimize the memory footprint on Cortex-M processor cores.|
|[RTOS v1](http://arm-software.github.io/CMSIS_5/RTOS/html/index.html) | Cortex-M0/M0+/M3/M4/M7 | Common API for real-time operating systems along with a reference implementation based on RTX. It enables software components that can work across multiple RTOS systems.|
|[RTOS v2](http://arm-software.github.io/CMSIS_5/RTOS2/html/index.html)| All Cortex-M, Cortex-A5/A7/A9 | Extends CMSIS-RTOS v1 with Armv8-M support, dynamic object creation, provisions for multi-core systems, binary compatible interface. |
|[Pack](http://arm-software.github.io/CMSIS_5/Pack/html/index.html)    | All Cortex-M, SecurCore, Cortex-A5/A7/A9 | Describes a delivery mechanism for software components, device parameters, and evaluation board support. It simplifies software re-use and product life-cycle management (PLM). |
|[SVD](http://arm-software.github.io/CMSIS_5/SVD/html/index.html)      | All Cortex-M, SecurCore | Peripheral description of a device that can be used to create peripheral awareness in debuggers or CMSIS-Core header files.|
|[DAP](http://arm-software.github.io/CMSIS_5/DAP/html/index.html)      | All Cortex | Firmware for a debug unit that interfaces to the CoreSight Debug Access Port. |
|[Zone](http://arm-software.github.io/CMSIS_5/Zone/html/index.html)    | All Cortex | Defines methods to describe system resources and to partition these resources into multiple projects and execution areas. |

## License

Arm CMSIS is licensed under Apache-2.0.
