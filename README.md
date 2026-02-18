# Lab 05 - Combinatorial Logic

In this lab, you’ve learned real world applications of digital logic, as well
as how to assemble your own Verilog modules. In addition, you’ve learned how
the constraints file maps your inputs and outputs to real pins on the FPGA.

## Rubric

| Item | Description | Value |
| ---- | ----------- | ----- |
| Summary Answers | Your writings about what you learned in this lab. | 25% |
| Question 1 | Your answers to the question | 25% |
| Question 2 | Your answers to the question | 25% |
| Question 3 | Your answers to the question | 25% |

## Joshua Johnson, Hannah Weakley

## Lab Summary

   As far as logic and k-maps go, we had everything all figured out from the start. This lab was useful mostly in learning how to use Verilog and actually writing out how the inputs and outputs
   we had determined would connect to one another and whether it should go in the top.v or the circuit files. Our issues were mostly technical, but it taught us how to troubleshoot errors and make
   sure we had the correct files bolded and not duplicated. Josh's USB port was having issues with connecting to the Basys3 board and Hannah had issues with the logic being correct but not working on the board.
   Luckily, we discovered it was an assign error with the Verilog code and everything worked after that. There were difficulties with duplicate files and issues with deleting old lab files and inserting the new
   ones afterwards that we think caused the issues. Overall, it was a very informative lab and gave us experience with the hardware side of things.

## Lab Questions

### 1 - Explain the role of the Top Level file.

   The top level file defines what hardware is used for the inputs and outputs, and connects that hardware and the other circuits to one another.
        
### 2 - Explain the function of the Constraints file.

  The constraints file maps the variable names with the actual hardware names that the FGPA board will recognize.
    
### 3 - Was the selection of Minterm and Maxterm correct for each circuit? What would you have chosen?

  Circuit A would have been more optimized if it had been written with minterms, because there are only two inputs that matter for that implementation and only 2 gates, while the maxterm implementation takes 3 gates. 
  Circuit B wouldn't have changed much with the maxterm implementation since it has the same number of inputs and gates for both SOP and POS implementations. In short, it would have been better to use the minterm
  implementation of circuit A.
  
