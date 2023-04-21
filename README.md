# 32-bit-MIPS-based-RISC-processor
## Intoduction
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
![problem statement1](https://user-images.githubusercontent.com/65547096/233547731-9c9b6856-cf1b-49d6-948c-51ab4547c5b7.PNG)
![problem_statment_1_2](https://user-images.githubusercontent.com/65547096/233433610-02aea793-153e-4b5b-8354-111fb701b0be.PNG)
<br>
Fig.Test Performed
<br>
Implemented in verilog using QuestaSim
<br>
## Simulated Waveform
* Output
![21](https://user-images.githubusercontent.com/65547096/233547207-d5d13701-c2d4-47e5-95a0-7f70cc844a93.PNG)
* Instruction Memory
![23](https://user-images.githubusercontent.com/65547096/233547267-4eeb52f8-ee85-4ab6-b4b6-5ed881d2a775.PNG)
* Register Bank
![22](https://user-images.githubusercontent.com/65547096/233547256-54c1a2be-0170-4303-afb1-41eb182f0db7.PNG)


