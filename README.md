# 8088-8086 Processor Simulation

This project demonstrates the basic working and simulation of the 8088-8086 processor using Python. The goal of the project is to simulate how the processor generates opcodes for various instructions such as `MOV`, `XOR`, `ADD`, etc., and display these opcodes in the command line.

## Working

To achieve the simulation of the 8088-8086 processor, we implemented functions in Python capable of generating the appropriate opcode for various assembly instructions. The processor works by converting each command into a unique machine code (opcode) that the computer understands to execute the desired operation. 

Our Python program operates on the same principle: it takes a command from the user and converts it into an opcode based on specific rules. The project covers all possible cases for instructions, such as:

- **MOV Instruction**: Handling register-memory, memory-register, register-register, register-immediate, memory-immediate, and displacement cases.
- **Additional Instructions**: The project also supports other instructions like `ADD`, `SUB`, `XOR`, `IMUL`, `IDIV`, etc.

### Features

- **Opcode Generation**: For instructions such as `MOV`, `CMP`, `NEG`, `NOT`, `ADD`, `SUB`, `INC`, `DEC`, `XOR`, `IMUL`, `IDIV`, `AND`, `SHIFT`, and `OR`.
- **Instruction Types**: Includes handling various instruction formats such as register-to-register, memory-to-register, and immediate-to-register conversions.
- **Command Line Interface**: Input instructions are processed through a command-line interface, and the resulting opcode is displayed.

## How to Run

1. Clone the repository or download the source files.
2. Ensure you have Python installed on your machine.
3. Run the Python script, pass an assembly instruction (like `MOV AX, BX`), and the program will output the corresponding opcode.

## Project Structure

- `AliAwais(MOV,CMP,NEG,NOT)`: Python script handling the `MOV`, `CMP`, `NEG`, and `NOT` instructions.
- `Zainab_add_sub_inc_dec`: Python script handling the `ADD`, `SUB`, `INC`, and `DEC` instructions.
- `and_or_xor_imul_idiv`: Python script handling the `AND`, `OR`, `XOR`, `IMUL`, and `IDIV` instructions.
- `umama_and_or_xor_shr.py`: Python script handling `AND`, `OR`, `XOR`, and shift instructions.
- `Task11.png`, `Task12.png`, `Task13.png`, `Task21.png`, `Task22.png`, `Task23.png`: Screenshots showing the working and output of the simulation.
- `Video Presentation.mp4`: Video presentation explaining the project.

## Credits

- **Ali Awais Safdar** - Handled opcodes for `MOV`, `CMP`, `NEG`, `NOT` instructions.
- **Zainab Kashif** - Handled opcodes for `ADD`, `SUB`, `INC`, `DEC` instructions.
- **Huzaifa Liaqat** - Developed the graphical user interface (GUI).
- **Syed Aon Raza** - Handled opcodes for `XOR`, `IMUL`, `IDIV` instructions.
- **Umama Zainab** - Handled opcodes for `OR`, `SHIFT`, `AND` instructions.

## Acknowledgments

This project demonstrates how low-level assembly commands can be converted into machine-readable opcodes, simulating the behavior of the 8088-8086 processor. It provides a practical understanding of how processors translate instructions into machine code.
