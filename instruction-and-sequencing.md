# **INSTRUCTIONS & INSTRUCTION SEQUENCING**
Computer programs perform various tasks, like adding numbers, checking conditions, reading from keyboards, or displaying on screens. To do these, computers use instructions. 

Instructions on a computer must be able to carry out the following four sorts of operations:

**Data transfers:** These instructions move data between the computer's memory and its registers, which are like temporary storage spaces. For example, you might move a number from memory into a register to work with it.

**Arithmetic and logic operations:** These instructions perform math and logical operations on data. For instance, you can add or subtract numbers, multiply or divide them, or perform logical operations like AND (combining two pieces of data based on certain conditions).

**Program sequencing and control:** These instructions control how the program flows and executes. They include things like calling a function (a named block of code), returning from a function, looping 

(repeating a section of code), and generating interrupts (signals that can halt normal program execution to handle special events).

**I/O transfers:** These instructions handle input and output operations, like reading from a keyboard or sending data to a display screen.
# **Register Transfer Notation (RTN)**
We're talking about moving data around inside a computer.This could mean shifting information from one spot to another, like from memory to the processor's register (a temporary storage space), or to registers in input/output (I/O) devices. We often give these spots names for easier reference. The key places where this transfer happens are:

**1.Memory**: Where data is stored in the computer.

**2.Processor Registers**: Temporary storage spaces inside the processor that hold onto data temporarily for quick access.

**3.Registers in I/O Devices**: These are like special storage spaces in input/output devices, such as keyboards or displays.

We use these locations to keep track of where data is and where it needs to go. This helps the computer efficiently handle information as it's processed and moved around.
![Aspose Words 65f92424-9d14-4234-9d15-cf73504a9d2f 001](https://github.com/akasharjuna/co/assets/159150741/5f2cc420-2947-42a9-a12d-e0c3856692ee)
## **ASSEMBLY LANGUAGE NOTATION**
Another sort of notation used to express programs and machine instructions is assembly language notation
![Aspose Words 65f92424-9d14-4234-9d15-cf73504a9d2f 002](https://github.com/akasharjuna/co/assets/159150741/7d8e20ee-0d4c-4f6c-bf49-b3a40e735577)

MOVE R2, R1, for instance 

• According to this expression, processor register R2's contents are moved to processor register R1. As a result, the contents of register R1 are overwritten but the contents of register R2 stay the same.
## **Basic Instruction Types**
- Operation code:The operation to be carried out is specified in the instruction's operation code field. Operation code, or simply opcode, gets its name from the binary code that specifies the operation. 
- Source / Destination operand: The operand for the instruction is directly specified in the source/destination operand field.
- Source operand address: We are aware that one or more operands may be needed for the operation that the instruction specifies. The memory or the CPU register could contain the source operand. In order for the CPU to access and operate the operand(s) in accordance with the instruction, the address of the source operand is frequently specified in the instruction. 
- Destination operand address: The CPU's operation may result in a result. The result is typically stored in one of the operands.

Write a program for evaluating the statement of arithmetic. Y is equal to (A+B) \* (C+D).

ADD A, B,R1      ;   R1←M[A] + M[B]

ADD C, D,R2      ;   R2←M[C] + M[D]

MUL R1, R2,Y    ;   M[Y]← R1 \* R2
## **Branching**
A new value is loaded into the program counter by branch-type instructions.

In order to execute instructions, the processor retrieves them from this new address, known as the "branch target."

Branching that is conditional occurs when a certain requirement is met.

An example would be Branch>0 LOOP –conditional branch instruction.If the condition is met, it will only execute.
## **Instruction sequencing**
![Aspose Words 65f92424-9d14-4234-9d15-cf73504a9d2f 003](https://github.com/akasharjuna/co/assets/159150741/36192485-9412-49a4-afd8-566034888fb9)

Processor has program counter (PC) register

- Address i for first instruction placed in PC
- Control circuits fetch and execute instructions, one after another in

straight-line sequencing

- During execution of each instruction,PC register is incremented by 4
- PC contents are i +16 after Store is executed

The computer system's data can be altered by using computer instructions, which can also be used to transfer data between memory and the CPU, carry out logical and mathematical operations, and perform other operations.
