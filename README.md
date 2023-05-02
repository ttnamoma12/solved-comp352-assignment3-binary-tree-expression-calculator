Download Link: https://assignmentchef.com/product/solved-comp352-assignment3-binary-tree-expression-calculator
<br>
A company is involved in shipping large number of containers at a dock. Containers are classified into three categories:

<u>Category 1:</u> containers need to be accessed by their indices:  <em>lookup</em>, <em>set</em>, <em>add</em> and <em>remove</em> from Category 1. <u>Category 2:</u> containers need to be <em>add</em> and <em>remove</em> before or after certain position including the first and last position of the Category 2.

<u>Category 3:</u> containers need to be <em>add </em>and<em> remove</em> in a sorted alphabetical order of their destination and any new added container need to follow that order of the Category 3.

From the three linear ADTs: List, Positional and Sequence covered in class. discuss which ADT to choose and its underlying implementation for the above containers’ categories.

Question 2

<ol>

 <li>Draw a single binary tree that gave the following traversals:</li>

</ol>

Inorder:       C   O   P   Y   R   I   G   H   T   A   B   L   E               Postorder:   C   P   O   R   G   I   T   H   B   A   E   L   Y

<ol>

 <li>Assume that the binary tree from part (a) of this question is stored in an array-list as a complete binary tree as discussed in class. Specify the contents of such an array-list for this tree.</li>

</ol>

<strong>Question 3 </strong>

<ol>

 <li>Given a tree T, where <em>n </em>is the number of nodes of <em>T</em>.</li>

</ol>

Give an algorithm for computing the depths of all the nodes of a tree T. What is the complexity of your algorithm in terms of Big-O?

<ol>

 <li>We say that a node in a binary search tree is full if it has both a left and a right child.</li>

</ol>

Write an algorithm called <em>Count-Full-Nodes(t)</em> that takes a binary search tree rooted at node t, and returns the number of full nodes in the tree. What is the complexity of your solution?

<strong> </strong>

<strong> </strong>

<h1>Question 4</h1>

<strong> </strong>

<ol>

 <li>Draw the min-heap that results from the bottom-up heap construction algorithm on the following list of values:</li>

</ol>

20, 12, 35, 19, 7, 10, 15, 24, 16, 39, 5, 19, 11, 3, 27.




Starting from the bottom layer, use the values from left to right as specified above. Show immediate steps and the final tree representing the min-heap. Afterwards perform the operation removeMin 6 times and show the resulting min-heap after each step.




<ol>

 <li>Create again a min-heap using the list of values from the above part (a) of this question but this time you have to insert these values step by step using the order from left to right (i.e. insert 20, then insert 12, then 35, etc.) as shown in the above question. Show the tree after each step and the final tree representing the min-heap.</li>

</ol>

<strong><u>Note:</u> </strong>You must submit the answers to all the questions above. However, only one or more questions, possibly chosen at random, will be corrected and will be evaluated to the full 50 marks.

<strong><u>Programming Questions (50 marks):</u></strong>

In class, we discussed evaluating arithmetic expressions using a binary tree, this binary tree has leaves that are associated with variables or constants, and whose internal nodes are associated with one of the operators: +,-,* and /.  You can assume parentheses are well-matched, and the only binary operations allowed are +, -, *, and /. In this programming assignment, you will design, using pseudo code, and implementation in Java code, a new version of arithmetic calculators that uses expression trees. Your solution should perform the following:

<ol>

 <li>read valid arithmetic expressions (parentheses are well-matched), where each expression is in a single line. Each arithmetic expression with operands (variables and/or constants) and operators.</li>

 <li>then convert it to an arithmetic expression in a binary tree structure, where each, internal node represents an operator, and its subtrees represent operands. All operators are binary, so every operator has both a left and a right operand. Leaf nodes represent either integers or variables.</li>

 <li>use a node in an expression tree. Nodes could be, a <em>leaf</em> node just contains a value (integer or variable); or an <em>internal</em> node has an operator and two Nodes representing its operands.</li>

 <li>if the expression contains operand variables, it should prompt the user with those variables to set their values in order to evaluate the expressions.</li>

</ol>




<ol>

 <li>Briefly explain the time and space complexity for the binary tree arithmetic expressions calculator. You can write your explanation in a separate file.</li>

 <li>Provide test logs for <u>at least 10 different</u> and <u>sufficiently complex</u> arithmetic expressions that use any of +, -, *, and / operators (including parentheses) in varying combinations, and operand both as variables and constants.</li>

</ol>




you are required to submit:

<ol>

 <li>the pseudo code.</li>

 <li>a fully commented Java source files (.java files), and the explanation text file.</li>

</ol>

<ul>

 <li>and your experimental results.</li>

</ul>




<strong><u>Important Notes</u></strong>

<strong>The programming part can be done in groups of two students maximum.  </strong>

<strong>For the Java programs, you must submit the source(.java) files. The solutions to all the questions should be zipped together into one .zip or .tar.gz file and submitted the EAS folder/ Moodle Dropbox. You must upload at most one file (even if working in a team, here is what you need to do:  </strong>

<ul>

 <li>Create <strong>one </strong>zip file, containing the necessary files (.java, .doc, .html, etc.). Please name your file following this convention:</li>

</ul>

If the work is done by 1 student: Your file should be called <em>a#_studentID</em>, where # is the number of the assignment <em>studentID </em>is your student ID number.

If the work is done by 2 students: The zip file should be called <em>a#_studentID1_studentID2</em>, where <em># </em>is the number of the assignment, and <em>studentID1 </em>and <em>studentID2 </em>are the ID numbers of each student.

<ul>

 <li>If working in a group, only one of the team members can submit the programming part. Do not upload 2 copies.</li>

</ul>

<strong> </strong>

<strong><u>Important:</u></strong> for the programming part of the assignment, a demo is required (please refer to the courser outline for full details). The marker will inform you about the demo times. <strong>Please notice that failing to demo your assignment will result in zero mark regardless of your submission.</strong> If working in a team, both members of the team must be present during the demo.