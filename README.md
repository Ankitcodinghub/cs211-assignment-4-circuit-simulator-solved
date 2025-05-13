# cs211-assignment-4-circuit-simulator-solved
**TO GET THIS SOLUTION VISIT:** [CS211 Assignment 4-Circuit Simulator Solved](https://www.ankitcodinghub.com/product/cs211-assignment-4-circuit-simulator-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;93357&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS211 Assignment 4-Circuit Simulator Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
4: Circuit Simulator

Introduction

You have to write a circuit simulator. One of the inputs to your program will be a circuit description file that will describe a circuit using various directives. Your program will print the output of the circuit for all possible input values.

1 Circuit Description Directives

The input variables used in the circuit are provided using the INPUTVAR directive. The INPUTVAR directive is followed by the number of input variables and the names of the input variables. All the input variables will be named with capitalized identifiers. An identifier consists of at least one character (A-Z) followed by a series of zero or many characters (A-Z) or digits (0-9). For example, some identifiers are IN1, IN2, and IN3. An example specification of the inputs for a circuit with three input variables: IN1, IN2, IN3 is as follows:

INPUTVAR 3 IN1 IN2 IN3

The outputs produced by the circuit is specified using the OUTPUTVAR directive. The OUTPUTVAR directive is

followed by the number of outputs and the names of the outputs.

An example specification of the circuit with output OUT1 is as follows:

OUTPUTVAR 1 OUT1

The circuits used in this assignment will be built using the following building blocks: NOT, AND, OR, NAND,

NOR, and XOR.

The building blocks can produce temporary variables as outputs, and can use either the input variables or

temporary variables as input. Output variables will never be used as inputs in a building block.

All the temporary variables will also be named with lower case identifiers (i.e., temp1, temp2, temp3, …). The specification of each building block is as follows:

<ul>
<li>NOT: for example, NOT IN1 OUT1</li>
<li>AND: for example,
<pre>     AND IN1 IN2 OUT1
</pre>
</li>
<li>OR: for example,
<pre>     OR IN1 IN2 OUT1
</pre>
</li>
<li>NAND: for example,</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
2

</div>
</div>
<div class="layoutArea">
<div class="column">
•

•

</div>
<div class="column">
NAND IN1 IN2 OUT1 NOR: for example, NOR IN1 IN2 OUT1 XOR: for example, XOR IN1 IN2 OUT1

Describing Circuits using the Directives

</div>
</div>
<div class="layoutArea">
<div class="column">
It is possible to describe any combinational circuit using the above set of directives. For example, the circuit OUT1 = IN1.IN2 + IN1.IN3 can be described as follows:

<pre>INPUTVAR 3 IN1 IN2 IN3
OUTPUTVAR 1 OUT1
AND IN1 IN2 temp1
AND IN1 IN3 temp2
</pre>
OR temp1 temp2 OUT1

Note that OUT1 is the output variable. IN1, IN2, and IN3 are input variables. temp1 and temp2 are temporary

variables.

A circuit description is a sequence of directives. You can assume that every temporary variable occurs as a output variable in the sequence before occurring as an input variable.

Note: A temporary variable can occur as an output variable in at most one directive.

3 Format of the Input Files

Your program will be given one file as input, containing the description of a circuit using the directives described above.

For example:

<pre>INPUTVAR 3 IN1 IN2 IN3
OUTPUTVAR 1 OUT1
AND IN1 IN2 temp1
AND IN1 IN3 temp2
</pre>
<pre>OR temp1 temp2 OUT1
</pre>
4 The problem

You have to write a program called first as described above. You are guaranteed that the circuit descriptions given as input to your program will be sorted. Let’s look at an example we have encountered before.

Example Execution

Supposeacircuitdescriptionfilenamedcircuit.txthasthedescriptionforthecircuitOUT1 = IN1.IN2 + IN1.IN3

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
<pre>INPUTVAR 3 IN1 IN2 IN3
OUTPUTVAR 1 OUT1
AND IN1 IN2 temp1
AND IN1 IN3 temp2
</pre>
<pre>OR temp1 temp2 OUT1
</pre>
Then, on executing the program with the above circuit description file, your program should produce the following output:

./first circuit.txt 0000

0010

0100

0110 1000 1011 1101 1111

The output of the first three columns are INPUTVAR IN1, IN2, and IN3 respectively. And the last column denotes the OUTPUTVAR OUT1.

Note: the values of the input and output variables should be space separated and be in the same order as the output variables in the INPUTVAR and OUTPUTVAR directive, e.g., if the circuit description file has the directive INPUTVAR 3 IN1 IN2 IN3, and OUTPUTVAR 3 OUT1 OUT2 OUT3, then the first values should be those of the input variables IN1, IN2, and IN3, and output variable OUT1, followed by that of OUT2, and then that of OUT3.

</div>
</div>
</div>
