# C++ Program Structure: Data Types

## Aim
To study and understand different data types in C++ and implement a program that demonstrates their usage and memory requirements.

---

## Software Required
Visual Studio

---

## Theory
In C++, data types define the type of data a variable can hold. When a variable is declared, the compiler allocates memory according to its data type, as each type requires a different amount of storage. Choosing the correct data type ensures efficient memory usage and accurate representation of values. C++ provides a variety of data types suitable for different needs:

1. **Character Data Type (`char`)**  
   - Used to store a single character.  
   - Size: 1 byte.  
   - Characters are enclosed in single quotes (`'a'`).  
   - Can store up to 256 characters based on ASCII codes.

2. **Integer Data Type (`int`)**  
   - Stores integer numbers.  
   - Size: 4 bytes (on 64-bit systems).  
   - Can store numbers in binary, octal, decimal, or hexadecimal systems.  
   - Range: -2,147,483,648 to 2,147,483,647.

3. **Boolean Data Type (`bool`)**  
   - Stores logical values: `true` (1) or `false` (0).  
   - Size: 1 byte.

4. **Floating Point Data Type (`float`)**  
   - Stores numbers with decimal points.  
   - Size: 4 bytes (on 64-bit systems).  
   - Range: approximately 1.2e-38 to 3.4e+38.

5. **Double Data Type (`double`)**  
   - Stores decimal numbers with higher precision than `float`.  
   - Size: 8 bytes (on 64-bit systems).  
   - Range: approximately 1.7e-308 to 1.7e+308.

---

## Implementation
In this program, the user is prompted to enter values of various data types. The program then displays the value, its type, and the memory size occupied by each variable.  

This implementation demonstrates how different data types store different kinds of information and how memory is allocated according to the type.

To run this program:  
1. Copy the code into Visual Studio.  
2. Compile and run the program.  
3. Enter values for different data types as prompted and observe the output.

---

## Conclusion
Through this practical, I learned about the different data types in C++ and how they are used to store values of varying types and sizes. This exercise helped me understand the importance of selecting appropriate data types for efficient memory usage and accurate computation.
