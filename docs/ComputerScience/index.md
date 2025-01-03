# 计算机系统概论

## 概述

计算机系统包含软件系统和硬件系统。**一个实际问题，可以一层层的分解，最后变为机器码被计算机执行。**

1. **问题**
2. **算法**
3. **高级语言**。高级语言是一种抽象，例如：C语言不是直接建立在汇编语言之上的，而是作为一种高级语言，提供了更高级别的抽象来描述程序逻辑。
4. **汇编语言**。汇编语言是符号替换。汇编语言提供了指令的符号表示：汇编语言使用助记符来表示ISA定义的指令，使得程序员可以使用这些助记符来编写程序。
    
    !!! 示例 Note
        ```shell
        00100001000010  在ISA中表示 将R1和R2寄存器相加
        ADD R1, R2      在汇编中表达了上述二进制的功能。
        ```

5. **ISA**。指令集。**ISA是软硬件的桥梁**。向上是软件层次，向下是硬件层次。ISA定义了处理器应该做什么（即软件层面的接口）；ISA是抽象层次上的定义，它描述了处理器的能力范围；微结构则描述了处理器是如何做的（即硬件层面的实现）。微结构是实现层次上的设计，它描述了如何在物理上实现ISA所定义的能力。
6. **微结构**。微结构是一些逻辑电路组成的功能单元。在逻辑电路的基础上，微结构进一步定义了如何组织和连接这些逻辑电路，以及如何管理数据流动和控制信号等。
7. **逻辑电路**。在门电路的基础上组成一些复杂的结构。逻辑电路：门电路组合起来形成了实现特定功能的逻辑电路，如加法器、乘法器等。
8. **门电路**。门电路在基本元器件上构成了基本电路。门电路：这是逻辑电路的物理实现，通过晶体管等基本电子元件构成AND门、OR门、NOT门等逻辑门。
9. **元器件**。各类元器件，晶体管等。
