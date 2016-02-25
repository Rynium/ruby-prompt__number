---
title: Numbers
instructor_notes: Feel free to re-organize the headings (or add/remove headings) below. We included the headings for your benefit, but it's 100% fine if you want to write your responses in some different structure.
---

# What are the different kinds of numbers in Ruby?

There are 2 types of numbers in Ruby. First is "integers" aka "fixnums'. These are whole numbers that do not contain any decimals. 
     EX. 2,3,6,46,1251,-555,-20
The 2nd type of numbers are "floats". These are numbers that do contain decimals.
     EX. 1.0, 5.9792, 9.001, -8.74
    
    
    
# What are some common operations and comparisons you would perform on numbers?
Addition using the "+" operator. Simply adds two numbers together.
     EX     2+3 = 5
Subtraction using the "-" operator. Simply subtracts one number from the other.
     EX     3-2 = 1
Multiplication using the "*" operator. Multiplies one number by the other.           
     EX     3*2 = 6
Division using the "/" operator. Divides one number by the other. Dividing an integer by an integer will return an integer for an answer and will round down to the nearest full integer. If either the numerator or denominator is a float, the answer returned will be a float.                    
     EX     3/2 = 1
     EX     7/3.0 = 2.3333333333333335
     EX     7.0/3 = 2.3333333333333335
     
     
     
     
Raising to the power of using the "**" operaator. Raises one number to the power of the other. 
     EX     3**2 = 9
Finding the Remainder using the "%" modulo operator. Divides one number by the other and returns the remainder.
     EX     3%2 = 1



# What is the difference between the `+` operation on a number versus on a String?

The "+" operation on a string will concatenate the strings together, but will not alter the original strings, resulting in more memory taken up than just using the "<<" concat operator. EX   "This is a "  +  "string"   = "This is a string"

The "+" operation on numbers will add the two numbers together. EX 2 + 3 + 9 = 14



# If you have a _String_ `"20"` and want to perform a mathematical operation (like division or multiplication) on it, will it work? If yes, why? If not, how would you make it work?

No, mathematical operations will only work on floats or integers. If a numerical number is contained inside of a string. We can use the ".to_i" or ".to_f" methods to convert it to a number. At this point, we can go ahead and use a mathematical operator on it. If we have a string that is followed by a "*x" where x is an integer, the string will be concatenated to itself x amount of times. For example "20' * 5 will give us a string of "2020202020", but 5* "20 will give us an error.

# What is the purpose of the `times` operation? Is that the same as `*`?

".times" is an iterator function in Ruby that allows us to repeat expressions multiple times.
   EX    3.times {print "Peanutbutter jelly time! "}   > Peanutbutter jelly time! Peanutbutter jelly time! Peanutbutter jelly time! 

The "*" operator is used with numbers to multiply the by each other.
   EX     7*8 = 56
