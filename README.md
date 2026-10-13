# Number Theory: Addition
In this lab you've learned the basics of number theory as it relates to addition.

## Rubric
| Item | Description | Value |
| ---- | ----------- | ----- |
| Summary Answers | Your writings about what you learned in this lab. | 25% |
| Question 1 | Your answers to the question | 25% |
| Question 2 | Your answers to the question | 25% |
| Question 3 | Your answers to the question | 25% |

## Lab Summary
In this lab, we explored more deeply the logic behind adders
and the utility of a full adder over a half adder. We 
discussed how a two-switch light bulb would behave similar 
to an XOR truth table, and how that can be used in an adder
circuit. We then learned how to handle an adder circuit with
a carry-in bit in addition to a carry-out bit. Afterwards,
we used multiple adders in conjunction to create an adder
for a larger set of numerical inputs.

## Lab Questions

### 1 - How might you add more than two bits together?
You can add more than two bits together by combining multiple
full adder modules into a larger circuit.

### 2 - What is the importance of the XOR gate in an adder?
The importance of the XOR gate in an adder component is that
it is the precise representation of the LSB of two bits being
added together, assuming the carry bit is considered the MSB
of the outputted binary number.

### 3 - What is the largest number a two bit adder can handle? What happens when you go over?
The largest number a two-bit adder can handle as an input is 
$3=11_2$. The largest output (disregarding the `Cout` value) 
it can give is also $3=11_2$. When you go over, the adder 
overflows, meaning the carry bit `Cout` is equal to `1`. 

But you could make the argument the largest outputted number,
with `Cout` regarded as the MSB would be $7=111_2$. However,
you must also consider the largest an input can be is $3=11_2$.
The largest possible output given the largest possible inputs
is $6=110_2$ if you count `Cout` as an output value.

