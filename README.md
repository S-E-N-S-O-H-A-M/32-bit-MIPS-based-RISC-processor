# 32-bit-MIPS-based-RISC-processor
## Intoduction
Microprocessors and Microcontrollers have been designed
around two philosophies: Complex Instruction Set Computer
(CISC) and Reduced Instruction Set Computer (RISC). The
CISC concept is an approach to the Instruction Set
Architecture (ISA) design that emphasizes doing more with
each instruction using a wide variety of addressing modes,
variable number of operands in various locations in its
Instruction Set. As a result, the instructions are of widely
varying lengths and execution times thus demanding a very
complex Control Unit, which occupies a large real estate on
chip. On the other hand, the RISC Processor have reduced
number of Instructions, fixed instruction length, more generalpurpose registers, load-store architecture and simplified
addressing modes which makes individual instructions execute
faster, achieve a net gain in performance and an overall
simpler design with less silicon consumption as compared to
CISC. The above features make the RISC design ideally suited
to participate in a powerful trend in the embedded Processor
market - the "system-on-a-chip". The most common RISC
microprocessors are ARM, SP ARC, MIPS and IBM's
PowerPC. There are number of semiconductor companies
implementing RISC processor on "system on chip" such as
Atmel A VR, Micro Blaze which are widely used for
embedded & DSP applications.
MIPS processor design is based on the RISC design
principle that emphasizes on load/store architecture. Due to
the difference in time taken to access a register as compared to
a memory location, it is much faster to perform operations in
on chip registers rather than in memory. The architecture
remains the same for all MIPS based processors while the
implementations may differ like single cycle, multi-cycle and
pipelined implementation 
## MIPS Pipelined Processor Datapath 
![pipelined_MIPS_32](https://user-images.githubusercontent.com/65547096/233430145-62c66172-77d5-478b-8641-42f1370f116c.PNG) <br>
Fig. MIPS Pipelined Processor Datapath 
## Register Bank
![register_banl](https://user-images.githubusercontent.com/65547096/233432863-546fe132-2427-4ae4-8087-990bd870fd9f.PNG)<br>
Fig.Register Bank
## Pipelining
![clock_cycles](https://user-images.githubusercontent.com/65547096/233433038-67ce03be-2985-4a32-8fd3-b6e8195e995a.PNG)<br>
Fig.Pipelining
## Test Performed in TestBench
![problem statement1](https://user-images.githubusercontent.com/65547096/233433584-4580bf99-492d-463a-a58c-525c8386b611.PNG)
![problem_statment_1_2](https://user-images.githubusercontent.com/65547096/233433610-02aea793-153e-4b5b-8354-111fb701b0be.PNG)
<br>
Fig.Test Performed


