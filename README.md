# calculator-mcs-8051
 This is a project I did for my Microprocessor and Assembly Language Programming Lab course. It is a simple calculator that can only work with two 2-digit inputs. The first number, the operator and the second number are prompted separately to save my sanity. 
 
 The following are considered invalid and if entered, will force the user to start again: 
 - '+' before any number. But (-ab) (operator) (-xy) is okay.
 - more than one operator: ++, //, \*/\* etc. 
 - inputs having more than two digits.
 - inputs with symbols in between or at the end


 Load calculator.hex into the AT89C51 model in proteus before running the simulation.
