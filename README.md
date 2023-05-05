Download Link: https://assignmentchef.com/product/solved-cse331-homework-3-alu-with-multiplication-design
<br>
In this assignment you will design an ALU that is capable of unsigned multiplication using <strong>Quartus</strong> and <strong>Verilog</strong> <strong>HDL</strong>.

<h1>1.     mult32.v Module</h1>




Your design will have three modules: adder.v, control.v and datapath.v. You will combine them in a mult32.v file to have the 32 bit multiplier.

Your Control Unit (control.v) will implement the below ASM. Design that first drawing your state diagram and finding the Boolean expressions for Next state variables and control signal outputs:

<h1>2.     alu32.v Module</h1>

Your ALU will be able to perform addition, subtraction, multiplication, AND, OR, XOR, NOR and Set Less Than operations.

Therefore the <strong>alu32.v</strong> will use <strong>mult32.v</strong> module inside.




<ul>

 <li>Write a report showing and explaining all Verilog files, including your schematics.</li>

 <li><strong>You can only use structural Verilog. Behavioral Verilog is not permitted. </strong></li>

 <li><strong>No other operations are permitted. And you cannot change ALUop decisions. </strong></li>

 <li>Perform simulations and check for accuracy. Not working designs will not get above 30pts. If the mistake is small it is your responsibility to find and correct it.</li>

</ul>