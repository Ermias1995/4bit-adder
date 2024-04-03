# 4bit-adder
4bit adder and Subtractor  
As we learned from DLD course, we can build 4bit adder by cascading four 1bit full-adders. So in this Assignment I preferred to build every component from the basic logic gates. Therefore to construct a full-adder circuit lets use 2-XOR, 2-AND and 1-OR gates as shown in the figure below.
 
This adder circuit takes 3 input values:-the carry and two bits that are going to be added and in return give as 2 output values: - again the carry and the sum. The next step is how we are going to use this 1 bit full adder for building up 4 bit adder. As I said before we can cascade the circuit but how? Here is the answer, we add or subtract the 4 bit number, bit by bit like we did on paper and transfer the carry in to the next digit. So we add the first two digits then in return we get 3 outputs from the full-adder. Then we insert the output into the next full adder as an input like displayed in the figure below.
 
Now we finished adding the number. The remaining step is how we are going to subtract numbers? To subtract the bits we preferred to employ the same circuit with aid of additives. We append another XOR gates to alter Subtrahend. The reason is, in logic subtraction is adding 2’s complement of a number. So that is why we employed a full-adder and XOR gate to subtract.

 
Lastly as required I displayed the 4bit result that is without the carry, using 7-segment decoder.
