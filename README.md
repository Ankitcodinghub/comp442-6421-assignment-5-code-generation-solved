# comp442-6421-assignment-5-code-generation-solved
**TO GET THIS SOLUTION VISIT:** [COMP442_6421 Assignment 5-Code Generation Solved](https://www.ankitcodinghub.com/product/comp442_6421-assignment-5-code-generation-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;96187&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP442_6421 Assignment 5-Code Generation Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
In this assignment, you are to implement a code generation phase for the language as described in the previous assignments. The following section lists the different specific constructs/concepts for which code generation needs to be implemented for all the aspects of the language to become executable.

Problem statement

1. Memory allocation: As variables are declared, memory space must be allocated that will eventually be used to store their values. Memory cells are either identified using a unique Moon assembly code label, or an offset relative to the stack frame on which the variable will reside during execution of the function scope in which it is declared. The size of the allocated memory block should depend on the declared type/kind of variable (integer, float, array, object, array of objects, etc.) and should be stored in the symbol table entries for each declared variable.

2. Functions: The code generated for functions should be associated with a Moon assembly code subroutine, i.e. a block of code that can be jumped to using a label, then when the function resolves, jump back to the instruction following the initial jump. Parameters should be passed/received during the function call. The return value should be passed to the calling function when the function resolves. If a call to a member function is made, the member function should have access to the data members of the object from which it was called.

3. Statements: Every kind of statement as defined in the grammar should be implemented: assignment statement, conditional statement, loop statement, input/output statements, and return statement, etc.

4. Aggregate data elements access: Aggregate data types such as arrays and objects contain a group of data values. The code must be generated so that contained member values in such an aggregated value can be accessed when referred to as factors in an expression or the left-hand side of an assignment statement. This includes access to array elements and object members. Access to these should be implemented using offset calculation.

5. Expressions: Computing of the resulting value of an entire expression, including the simple case when an expression is either a variable name or a single literal value, up to complex expressions involving all kinds of operators (arithmetic, logical, and relational), array indexed with expressions, deeply nested object member access, etc. This involves memory allocation for temporary results, and register allocation/deallocation when necessary.

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Work to submit

Document

You must provide a short document that includes the following sections:

</div>
</div>
<div class="layoutArea">
<div class="column">
Section 1. Section 2.

</div>
<div class="column">
Analysis : Using the (1-5) itemized list provided below (see “Implementation”), provide a checklist that identifies what code generation items are either implemented or not implemented in your assignment.

Design : I – Overall design – Description/rationale of the overall structure of the solution and the roles of the individual components used in the applied solution. II – Phases – Description of the purpose of each phase involved in the implementation of this assignment.

</div>
</div>
<div class="layoutArea">
<div class="column">
Section 3. Implementation

</div>
</div>
<div class="layoutArea">
<div class="column">
Use of tools : Identify all the tools/libraries/techniques that you have used in your implementation and justify why you have used these particular ones as opposed to others.

</div>
</div>
<div class="layoutArea">
<div class="column">
1. Memory allocation

</div>
</div>
<div class="layoutArea">
<div class="column">
<ol>
<li>1.1 &nbsp;Allocate memory for basic types (integer, float).</li>
<li>1.2 &nbsp;Allocate memory for arrays of basic types.</li>
<li>1.3 &nbsp;Allocate memory for objects.</li>
<li>1.4 &nbsp;Allocate memory for arrays of objects.</li>
</ol>
<ol>
<li>2.1 &nbsp;Branch to a function’s code block, execute the code block, branch back to the calling function.</li>
<li>2.2 &nbsp;Pass parameters as local values to the function’s code block.</li>
<li>2.3 &nbsp;Upon execution of a return statement, pass the return value back to the calling function.</li>
<li>2.4 &nbsp;Call to member functions that can use their object’s data members.</li>
</ol>
<ol>
<li>3.1 &nbsp;Assignment statement: assignment of the resulting value of an expression to a variable, independently of what is the expression to the right of the assignment operator.</li>
<li>3.2 &nbsp;Conditional statement: implementation of a branching mechanism.</li>
<li>3.3 &nbsp;Loop statement: implementation of a branching mechanism.</li>
<li>3.4 &nbsp;Input/output statement: execution of a keyboard input statement should result in the user being prompted for a value from
the keyboard by the Moon program and assign this value to the parameter passed to the input statement. Execution of a console output statement should print to the Moon console the result of evaluating the expression passed as a parameter to the output statement.
</li>
</ol>
<ol>
<li>4.1. &nbsp;For arrays of basic types (integer and float), access to an array’s elements.</li>
<li>4.2. &nbsp;For arrays of objects, access to an array’s element’s data members.</li>
<li>4.3. &nbsp;For objects, access to members of basic types.</li>
<li>4.4. &nbsp;For objects, access to members of array or object types.</li>
</ol>
<ol>
<li>5.1. &nbsp;Computing the value of an entire complex expression.</li>
<li>5.2. &nbsp;Expression involving an array factor whose indexes are themselves expressions.</li>
<li>5.3. &nbsp;Expression involving an object factor referring to object members.</li>
</ol>
Notes : (1) Difficulty rating is provided as green: easy, yellow: medium, red: harder. (2) Marking elements with higher marks indicate constructs that are necessary to have in order to demonstrate that the generated code runs correctly. (3) This is the list of code generation elements due for assignment 5. More code generation elements are going to be added on the grading scheme for the final project requirements.

• Output of moon code in a file : The Moon code should be output to a file, including comments in the generated code to highlight the structure of the code generated for each syntactical construct. When compiling a file named, for example, originalfilename.src, the code generator should write the Moon code into a file named originalfilename.moon.

• Test cases : Write a set of source files that enable to test the code generation for all syntactical structures that you can generate code for, including simple cases that test isolated syntactical constructs, and more complex cases that test combinations of syntactical constructs.

• Driver : Include a driver that reads your test cases and generates, for each test case file, the corresponding .moon file.

</div>
</div>
</div>
