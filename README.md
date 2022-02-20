# MIPS32_ISA
The MIPS32 instruction set is an instruction set standard published in 1999 that was promulgated by MIPS Technologies after its demerger from Silicon Graphics in 1998. The MIPS32 instruction set was developed along side the MIPS64 Instruction Set which includes 64-bit instructions. The MIP32 standard included coprocessor 0 control instructions for the first time. Today, the MIP32 instruction set is the most common MIPS instruction set, compatible with most CPUs. Due to its relative simplicity, the MIP32 instruction set is also the most common instruction set taught in computer architecture university courses.

The latest MIPS32 revision is revision 5, which added a set of new memory-efficient operations for large memory footprint applications.
<h4>ARITHEMATIC INSTRUCTION</h4>
<table>
 <tr>
  <th>OPCODE</th>
  <th>NEUMATICS</th>
 </tr>
 <tr>
 <td>000000</td>
 <td>ADD</td>
 </tr>
 <tr>
 <td>000001</td>
 <td>SUB</td>
 </tr>
 <tr>
 <td>000010</td>
 <td>AND</td>
 </tr>
 <tr>
 <td>000011</td>
 <td>OR</td>
 </tr>
 <tr>
 <td>000100</td>
 <td>SLT</td>
 </tr>
 <tr>
 <td>000101</td>
 <td>MUL</td>
 </tr>
 <table>
  <h4>IMMEDIATE INSTRUCTION</h5>
  <table>
 <tr>
  <th>OPCODE</th>
  <th>NEUMATICS</th>
 </tr>
 <tr>
 <td>001010</td>
 <td>ADDI</td>
 </tr>
 <tr>
 <td>001011</td>
 <td>SUBI</td>
 </tr>
   <tr>
 <td>001100</td>
 <td>SLTI</td>
 </tr>
  </table>
  <H4>BRANCH INSTRUCTION</h5>
  <table>
    <tr>
  <th>OPCODE</th>
  <th>NEUMATICS</th>
 </tr>
 <tr>
 <td>001110</td>
 <td>BEQZ</td>
 </tr>
   <tr>
 <td>001101</td>
 <td>BNEQZ</td>
 </tr>
  </table>
  <h4>MOMORY CONTROL INSTRUCTION</h4>
  <table>
   <tr>
  <th>OPCODE</th>
  <th>NEUMATICS</th>
 </tr>
 <tr>
 <td>001000</td>
 <td>LW</td>
 </tr>
   <tr>
 <td>001001</td>
 <td>SW</td>
 </tr>
  </table>
  <table>
   <tr>
  <th>OPCODE</th>
  <th>NEUMATICS</th>
 </tr>
 <tr>
 <td>111111</td>
 <td>HLT</td>
 </tr>
  </table>

<h2> Five pipeline stages of MIPS32 ISA </h2>
<ol>
 <li>IF = Instruction Fetch </li>
 <li>ID = Instruction Decode </li>
 <li>EX = Execute </li>
 <li>MEM = Memory </li>
 <li>WB = Write Back</li>
 </ol>
 
![block diagram](https://user-images.githubusercontent.com/84762990/154837143-b8887dd6-b4f1-4249-a578-f4527f3209cf.png)

<h3>IF(Instruction Fetch)</h3>

![IF_ID](https://user-images.githubusercontent.com/84762990/154839339-1622a2bb-faf3-40b0-b282-5cb298b94c07.png)

<h3>ID(Instruction Decode)</h3>

![ID_EX](https://user-images.githubusercontent.com/84762990/154839367-a8258f64-04c1-4197-8f29-5efdaed79963.png)

<h3>EX(Execute)</h3>

![EX_MEM](https://user-images.githubusercontent.com/84762990/154839388-4cb046fd-d348-4046-8617-4f18c57ae88b.png)

<h3>MEM(Memory)</h3>

![MEM_WB](https://user-images.githubusercontent.com/84762990/154839401-303f685b-62e4-4a21-a5f4-615dcb57eac3.png)

<h3>WB(Write Back)</h3>

![WB](https://user-images.githubusercontent.com/84762990/154839422-6466e452-e701-49b2-b1c2-ac9869ffbbe7.png)

![image](https://user-images.githubusercontent.com/84762990/154840704-5e67ed10-9fd6-4346-880e-5f6186718f50.png)

