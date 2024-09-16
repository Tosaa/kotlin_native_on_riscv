# Extension of the Kotlin/Native compiler to support RISC-V targets

### Abstract
Abstract
This thesis describes how the Kotlin/Native compiler can be extended to enable compilation of Kotlin for the RISC-V architecture. For this pur- pose, changes in the JetBrains/Kotlin repository are presented and depen- dencies are analyzed. Strategies to resolve the dependencies and upcoming conflicts are discussed and pursued. Since the Kotlin/Native compiler re- lies on the LLVM toolchain, one focus of the work is the analysis and adaptation of the integration of the LLVM distribution and the necessary changes that go with it. This research was carried out to make the changes easier to implement later and to show the extent of the changes.
Besides that, theoretical principles are presented to provide a bet- ter understanding of the required changes. This includes details about the Kotlin/Native compiler and how it works during compilation and an introduction to the LLVM toolchain and the LLVM Intermediate Rep- resentation with a focus on upcoming changes. Moreover, a summary of RISC-V features and basics on the RISC-V ISA are explained to illustrate the benefit of using LLVM.
The result of this work is a fork of the Kotlin repository that makes it possible to build the Kotlin/Native compiler so that it can cross-compile Kotlin source code for RISC-V boards. This requires changes in the Kotlin/Native runtime, the use of a pre-built riscv-gnu-toolchain and the use of a more recent LLVM version. Additionally, an attempt to upgrade the LLVM version in the Kotlin project and upcoming problems are de- scribed.
Finally, the outcome of this work is compared with research that tar- gets similar objectives to port languages onto the RISC-V architecture.

### Notes:
This Repository only contains the paper/thesis which is the outcome of the master thesis. The concrete work to extend the Compiler can be found at: https://github.com/Tosaa/master-thesis-kotlin-repo  
The work has to be considered in detail and individual changes can be adopted for the official repository.

### Acknowledgement:
I am very grateful to Dr. X and Mr. Y for their support in writing the thesis and for always being available to answer questions. 

This work is the result of the final thesis of the master program 'Embedded computing' of the faculty 'Computer Science and Mathematics' at the 
(HM) Hochschule München University of Applied Sciences

Munich, Germany
