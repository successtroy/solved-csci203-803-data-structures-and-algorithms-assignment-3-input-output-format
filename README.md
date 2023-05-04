Download Link: https://assignmentchef.com/product/solved-csci203-803-data-structures-and-algorithms-assignment-3-input-output-format
<br>
&#x2714;&#x2714;&#x2714;&#x2714;&#x2714;

<strong><u>Input</u></strong>

You program should read an <strong>input</strong> <strong>file name</strong> from the <strong>command line</strong> and uses the adjacency matrix read from the input file with a format as follows.

<ul>

 <li>The integer number of vertices in the graph.</li>

 <li>The positive real number weights of one vertex per line, delimited by a space. The value 0.0 is used as no connection.</li>

</ul>




A sample input file can be created using the provided program, <strong>generateAdjM.cpp</strong>. You may use the program directly, or adapt it, to create graphs for your algorithms without modifying the output format. If you adapt the program to generate adjacency matrices of different characteristics, you should add a header to the code to explain what you have modified.  <strong><u>Output</u></strong>

 MST output

The MST from each algorithm should be saved in a text output file named with prefix, <strong>output_mst_*.txt</strong>, that contains the edges of MST as a sequence of <strong><em>edges</em></strong>, in selected order using the <strong>algorithm *</strong> from <strong>node 1</strong>, each edge and its weight per line and the <strong><em>minimal weight</em></strong> at the last line. <strong>Algorithm 1</strong> is always for the brute-force algorithm and <strong>algorithm 2</strong> and so on for your other algorithms. For instance,

1-4 2.3

4-3 1.9

4-2 3.2  …

4-2 3.2

45.6

 Statistics output

The output should be displayed to <strong>standard output</strong>. For each algorithm, the output should consist of the following data, clearly labelled: (CSCI203 students only have one output for Prim’s algorithm.)

Number of vertices: **

<ol>

 <li>Brute-force algorithm 1: *** (time unit)</li>

 <li>Prim’s algorithm 2 (matrix): *** (time unit)</li>

 <li>Prim’s algorithm 3 (heaps): *** (time unit)</li>

</ol>

You may save this information to a file for your analysis and easy plotting later.