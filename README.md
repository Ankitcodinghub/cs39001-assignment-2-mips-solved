# cs39001-assignment-2-mips-solved
**TO GET THIS SOLUTION VISIT:** [CS39001 Assignment 2-MIPS  Solved](https://www.ankitcodinghub.com/product/cs39001-indian-institute-of-technology-iit-kharagpur-solved-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;114633&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS39001 Assignment 2-MIPS&nbsp; Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (1 vote)    </div>
    </div>
AIM: To get proficient in handling arrays in MIPS, writing function subroutine in MIPS, allocating variables dynamically on the stack, passing parameters to functions by value, passing (local) arrays to functions by their addresses.

INSTRUCTIONS: Make one submission per group in the form of a single zipped folder containing your source code(s). Name your submitted zipped folder as Assgn 3 Grp GroupNo.zip and (e.g. Assgn 3 Grp 25.zip). Inside each submitted source files, there should be a clear header describing the assignment no., problem no., semester, group no., and names of group members. Liberally comment your code to improve its comprehensibility.

Question 1

Write a complete MIPS-32 program that –

1. Reads two 16-bit signed integers (encoded in 2’s complement form) withthe prompt – “Enter first number:” and “Enter second number:”.

2. After the two input numbers are collected from the user, there should besanity checking to ensure that they are within the proper numerical range.

3. Determine the product of these two numbers using the Booth’s Multiplication Algorithm as depicted in Figure 1.

4. At the end of your program, print the calculated product with the message– “Product of the two numbers are: ”.

Your program should have a procedure call multiply booth, with the two input arguments available in registers $a0 and $a1, and the final product available in register $v0.

Figure 1: Booth’s Algorithm

Question 2

Write a complete MIPS-32 program that –

1. Reads an array of ten integers from the user (can also be negative). Thesenumbers are collected from the input console using a loop and stored in the memory in an array called ‘array’. Do not store the numbers as scalars in ten different non-contiguous locations or in ten different registers.

2. Reads an integer ‘k’ with the prompt: “Enter the value of k: ”. Write afunction named find k largest that finds the kth largest number in the above array. Your program should also check whether k &gt; n. In such case, your program should display proper error message.

3. Write a function named sort array in order to sort the input array before finding the kth largest number. You have to implement Algorithm 1 as given below to sort the array. Pass the address of the 1-D array and the required parameters while implementing the function. After sorting, print the sorted array on the console with a proper message.

4. Thereafter, print the kth largest number from the sorted array with suitable messages.

Algorithm 1 sort array (Sort the array denoted as A with n numbers)

1: for j = 2 to n

2: temp = A[j];

3: // Insert A[j] to the sorted sequence A[1..j − 1]

4: i = j − 1;

5: while i &gt; 0 and A[i] &gt; temp

6: A[i + 1] = A[i]; 7: i = i − 1;

8: A[i + 1] = temp

Question 3

Write a complete MIPS-32 program that –

1. Prompts the user for four positive integers m, n, a r as “Enter four positive integers m, n, a and r: ”.

2. Allocates space for an m × n integer array A and an n × m integer array B on the stack.

3. Populates the array A in a row major fashion using a Geometric Progression (GP) series with initial value a and common ratio r.

4. Print the elements of matrix A.

5. Computes the transpose matrix of the matrix A in the n × m matrix B.

6. Prints the elements of B finally.

Follow these implementation-level constraints while writing your code. Write the following functions:

1. “initStack” : Initialise the stack pointer ($sp) and frame pointer ($fp).

2. “pushToStack” : This function takes one argument as input (in $a0) and push it to the stack.

3. “mallocInStack” : This function allocates space for m×n (stored in $a0) memory locations (each of 4 bytes for each integer) in the stack and returns the first address ($v0).

4. “printMatrix” : This function takes three parameters- the positive integersm (in $a0), n (in $a1) and the address of a two-dimensional m×n integer array A (in $a2) storing the matrix in row major form. It prints the elements of A in a row major manner.

5. “transposeMatrix” : The function takes (positive) integers m and n and addresses of two integer arrays A and B. It is to compute the transpose matrix of the matrix A and store in the n × m matrix B.

If required, you can write additional functions as well, but with proper comments and descriptions.
