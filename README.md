Download Link: https://assignmentchef.com/product/solved-csce-a351-assignment-3
<br>
Provide code in a programming language you choose so you can make your point in terms of average and worst-time complexity for the following problems. Provide a write-up analyzing the performance of your code in average and worst-case scenarios as well.

<ol>

 <li>Implement naive multi-occurrence string search: given a string, in the form of a data-structure that allows each of the characters of the string to be accessed in O(1), called the haystack, and another string called the needle, the function computes all indices <em>i </em>such that the needle appears as a substring of the haystack, starting at the <em>i</em>-th character of the haystack. Return the set of such indices <em>i </em>in the form of an array of booleans.</li>

</ol>

In C, your function could have the following signature:

<strong>void </strong>matchStrings(<strong>char </strong>*res, <strong>const char </strong>*haystack, <strong>const char </strong>*needle);

<ol start="2">

 <li>Implement Rabin-Karp multi-occurrence string search. This function does the same thing as the naive multi-occurrence string search specified above but uses Rabin’s and Karp’s sliding-window hashing and hash-update technique, which we discussed in class. If you use C as a programming language, you may start your code from the boilerplate code provided on Blackboard.</li>

 <li>Implement Knuth-Morris-Pratt multi-occurrence string search. This function does the same thing as the naive multi-occurrence string search specified above but uses the Knuth-Morris-Pratt implicit finite-automaton technique described in the textbook.</li>

 <li>Implement a test driver. If you use C as a programming language, you can utilize the test driver posted on Blackboard.</li>

 <li>Run your three different implementations on various examples, showcasing their average and worstcase complexity.</li>

</ol>

1