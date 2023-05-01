Download Link: https://assignmentchef.com/product/solved-cda4203l-lab2-verilog-based-circuit-modeling-and-validation-by-simulation
<br>
Objectives:  To learn and practice Verilog based circuit modeling and validation by simulation.

Problem: Implement an ALU (Arithmetic Logic Unit) satisfying the following functional requirements. You should complete schematic capture tutorial, before you start on this lab. You should complete tutorial 2 before starting this lab.

<table width="624">

 <tbody>

  <tr>

   <td width="321"></td>

   <td width="303">


    <table width="247">

     <tbody>

      <tr>

       <td width="100">Function</td>

       <td width="81">Select (S)  S1    S0</td>

       <td width="66">Y</td>

      </tr>

      <tr>

       <td width="100">Invert</td>

       <td width="81"> 0      0</td>

       <td width="66"><em>A</em></td>

      </tr>

      <tr>

       <td width="100">Add</td>

       <td width="81"> 0      1</td>

       <td width="66">A + B</td>

      </tr>

      <tr>

       <td width="100">Subtract</td>

       <td width="81"> 1      0</td>

       <td width="66">A – B</td>

      </tr>

      <tr>

       <td width="100">Double</td>

       <td width="81"> 1      1</td>

       <td width="66">2*A</td>

      </tr>

     </tbody>

    </table></td>

  </tr>

 </tbody>

</table>




Figure 1: ALU Port Interface and Function Table

<ol>

 <li>Behavioral Verilog: Design an ALU in behavioral Verilog with port interface and functionality as shown in Figure 1. Test the ALU functionality by simulation.  Include at least two vectors per function.</li>

 <li>Structural Verilog: Design the ALU in structural Verilog. Only use the following components: NOT, Full Adder, and 2-to-1 Mux.  First you need to develop behavioral Verilog module for each of the above components.  Then, you can instantiate these components to build the ALU. Test the ALU functionality by simulation.  Include at least two vectors per function. You may re-use the test bench you have created in Lab 1.</li>

</ol>

Deliverables: (1) a concise PDF report that includes your Verilog code and simulation results; (2) A zipped file of your design files (Verilog models and test benches).  Include a README file. Organize your files in folders named Problem1 and Problem2.

Report Organization (A template is provided on Canvas):

□Cover sheet

□Problem 1: Behavioral Verilog Code, Test Bench, and Simulation Results (Waveforms)

□Problem 2: Behavioral Verilog for Components, ALU Structural Code, Test Bench, and Simulation Results (Waveforms)


