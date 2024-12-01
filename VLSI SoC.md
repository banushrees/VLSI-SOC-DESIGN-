# VLSI SOC DESIGN 

   ## DAY 1  
 <details>
    <summary>lab-1</summary>

# CHIP NAME:` QFN - 48 `

![Screenshot (14)](https://github.com/user-attachments/assets/9e4a187f-ad04-4e36-820a-37372000c6a3)



- Each side of this has 12 pins
- chip is connected to each pins

  ![Screenshot (15)](https://github.com/user-attachments/assets/eb160ae7-5324-4d1a-8662-423b7dc3e66f)

 important components of this chips are  PADS, core, dies.
  - CORE is area where all the digital logic chips are embedded
  - PADS is used to send the signals inside the chip and vise versa
  - DIE is used entire size of the chip where all pins  are embedded

![Screenshot (18)](https://github.com/user-attachments/assets/bc17abfb-f80c-47c7-92dc-8ff4c6c86f3d)

- A typical chip contains of SoC(RISC-V) , SRAM, ADC, DAC, PLL, GPIO, SPI.
- SRAM, PLL, ADC, DAC  are called ` FOUNDRY IP'S `(factory where all the chips are manufactured).
- FOUNDRY IP's has some files which will help us to communicate the parts present  in the chip (Foundry IP parts)
- MACROS's are digital logic components contains of  RISCV (Soc), SPI, GPIO  Bank.
- IP's (Intellilectual Property )is an intelligent technique to built the building blocks.

---

# INTRODUCTION TO THE RISC-V ARCHITECTURE

![Screenshot (19)](https://github.com/user-attachments/assets/b1930879-780a-4052-a572-5fe76917728b)

- RISC V is Instruction set architecture (eg.C-program has to be typed on the hardware which has a particular layout )
- The C-program is compiled on the assembly launguage program
- The assembly launguage program later on converted to machine launguage (eg 0101110)  Hexadecimal--> binary
- The interface that present between the RISCV  and layout is HDL( Hardware Description Launguage)

---

# SOFTWARE APPLICATION TO HARDWARE IMPLEMENTATION

Interaction between the software apps and HardWare happens by the help of System software 

![Screenshot (19)](https://github.com/user-attachments/assets/abacd6ff-7437-495c-9bfd-2aad14de8ea6)

### components of system software

 #### OS -> COMPILER -> ASSEMBLER
 1. OS - Operating System
   -Handles i/o operations
   - Allocate Memory
   - Low level system functions

 2. COMPILER
    -converts c,c++ VB, Java, to instructions depends on what kind of hardware it is (eg..exe file).

 3.ASSEMBLER
   - converts instrction set  into machine launguage (eg 101011)

 ![Screenshot (22)](https://github.com/user-attachments/assets/4230546d-cf87-4026-a798-da9f708b70ae)


 - The instructions set from the compiler act as a interface from C launguage to the HardWare machine launguage .
 - HardWare only understands 0 and 1.
 - output of the assembler is binary.
 - first the instruction set specification will be converted to binary by assembler then the RTL of the H/W  will add the specs from instructions set in the  form of binary.
 - Then it is synthesized by netlist from RTL  and then implemented by H/W.

 ----
 
# SOC DESIGN AND OPENLANE

## INTRODUCTION TO ALL COMPONENTS OF OPENSOURCE DIGITAL ASIC DESIGN







