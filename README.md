# cse220-lab-05--parenthesis-balancing-solved
**TO GET THIS SOLUTION VISIT:** [CSE220 Lab 05- Parenthesis Balancing Solved](https://mantutor.com/product/cse220-solved-5/)


---

**For Custom/Order Solutions:** **Email:** mantutorcodes@gmail.com  

*We deliver quick, professional, and affordable assignment help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;113531&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSE220 Lab 05- Parenthesis Balancing Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
&nbsp;

Lab 05

Parenthesis Balancing

I. Topic Overview:

Students will learn a practical use case for stack data structure. By implementing and using stacks methods, they will learn to check whether a given expression has balanced parentheses or brackets.

II. Lesson Fit:

For successfully completing this lab’s tasks, the students need to have a good idea on how stack is implemented and how the various methods such as push(), pop() etc works. They also need a clear idea about array and linked list as both of these data structures are used to create a stack.

Moreover, students need a solid grasp on programming in Java and Java IDE.

III. Learning Outcome:

a. Understand the functionality of stack data structure

b. Use stack methods to solve programming problems

c. Implement stack ADT using both array and linked list

IV. Anticipated Challenges and Possible Solutions

a. Students might find it difficult to implement stack using array or linked list or both. For example, in array based implementation, students have to check for stack overflow and underflow exceptions. Also, in case of linked list based implementation, only stack underflow condition needs to be checked.

Solutions:

i. Students have to create class for stack related exceptions. Two different classes can be declared, one for overflow and one for underflow. Both classes need to extend the Exception class of Java.

ii. Put stack’s push and pop methods inside a try-catch block and handle the exceptions.

b. It can get difficult or confusing to check all conditions of parenthesis matching. Because, when a closing parenthesis/curly brace/bracket is encountered one needs to make sure the correct type of opening parenthesis/curly brace/bracket are popped from the stack Solutions:

i. Students need to write if-else if checking for each type of parenthesis/curly brace/bracket separately when an opening parenthesis/curly brace/bracket is encountered.

ii. Also, a method to check whether the stack is empty after reading all inputs needs to be implemented.

V. Acceptance and Evaluation

Instructions for students:

3. You need to create a full functioning Stack data structure to solve this problem.

You are not allowed to use the built in Stack.

5. The submission format MUST be maintained. You need to copy paste all your codes in ONE SINGLE .txt file and upload that. If format is not maintained, whole lab submission will be canceled.

6. If you are using JAVA, you must include the main method as well which should test your other methods and print the outputs according to the tasks.

7. If you are using PYTHON, make sure your code has the methods invoked and proper printing statements according to the tasks.

Lab 04 Activity List

Input

Your program will take an arithmetic expression as a String input. For Example:

1. “1+2*(3/4)”

2. “1+2*[3*3+{4–5(6(7/8/9)+10)–11+(12*8)]+14”

3. “1+2*[3*3+{4–5(6(7/8/9)+10)}–11+(12*8)/{13+13}]+14”

Program

Your program will determine whether the open brackets (the square brackets, curly braces and the parentheses) are closed in the correct order.

Outputs:

Output 1

1+2*(3/4)

This expression is correct.

Output 2

1+2*[3*3+{4–5(6(7/8/9)+10)–11+(12*8)]+14 This expression is NOT correct.

Error at character # 10. ‘{‘- not closed.

Output 3

1+2*[3*3+{4–5(6(7/8/9)+10)}–11+(12*8)/{13+13}]+14 This expression is correct.

Output 4

1+2]*[3*3+{4–5(6(7/8/9)+10)–11+(12*8)]+14 This expression is NOT correct.

Error at character # 4. ‘]‘- not opened.

Task 1

Solve the above problem using an array based stack.

Task 2

Solve the above problem using a linked list based stack.
