## General ideas

**_Recursion_** goes hand in hand with **_loops_**. 
Using Recursion is also closely related to playing with **_Stack_**.
Sometimes we first figure out a solution using loops, and then convert the solution into Recursion by cases.

Recursion can be implemented starting with the **_base cases_**, followed by the **_inductive case_**. 

Each case will do some work, and then returns according to the type of the funciton.

**base cases** are where the function finishs.

**inductive cases** used to deal with the **_partially correct_** work.

Generally speaking, the inductive cases work by **_decomposing - recomposing_**. 
That is, we decompose the component into the next lower level sub-components, 
pretend the sub-components are handled correctly, and then **_combining_** them correctly.

See 0203, 0206 for example.

Note **Recursion** uses **O(n) space** implicitly.
See the difference of **in-place** and **O(n) space** in https://leetcode.com/problems/reverse-string/solution/
