Download Link: https://assignmentchef.com/product/solved-ad-homework1-algorithm-design
<br>
<h1>Exercise 1</h1>

You are given a long string of letters, <em>w </em>= (<em>w</em><sub>1</sub><em>,…,w<sub>n</sub></em>). You are interested in the longest palindrome, i.e. the longest sequence <em>P </em>= (<em>w<sub>i</sub>,…,w<sub>j</sub></em>) that is the same forwards and backwards, meaning (<em>w<sub>i</sub>,w<sub>i</sub></em><sub>+1</sub><em>,w<sub>i</sub></em><sub>+2</sub><em>,…,w<sub>j</sub></em><sub>−1</sub><em>,w<sub>j</sub></em>) = (<em>w<sub>j</sub>,w<sub>j</sub></em>−<sub>1</sub><em>,w<sub>j</sub></em>−<sub>2</sub><em>,…,w<sub>i</sub></em><sub>+1</sub><em>,w<sub>i</sub></em>).

<ol>

 <li>Give an algorithm that in <em>O</em>(<em>n</em><sup>2</sup>) time outputs the longest palindrome, and prove its running time.</li>

 <li>Give an algorithm for the case that the palindrome does not have to be a continuous subsequence of <em>w</em>, i.e. the case that it is any sequence <em>P </em>= (<em>w<sub>i</sub></em><sub>1</sub><em>,w<sub>i</sub></em><sub>2</sub><em>,…,w<sub>i</sub></em><em><sub>j</sub></em>) for which (<em>w<sub>i</sub></em><sub>1</sub><em>,w<sub>i</sub></em><sub>2</sub><em>,…,w<sub>i</sub></em><em><sub>j</sub></em>) = (<em>w<sub>i</sub></em><em><sub>j</sub></em><em>,w<sub>i</sub></em><em><sub>j</sub></em><sub>−1</sub><em>,…,w<sub>i</sub></em><sub>1</sub>) and <em>i</em><sub>1 </sub><em>&lt; i</em><sub>2 </sub><em>&lt; </em>·· <em>&lt; i<sub>j</sub></em>. Show that the algorithm solves the problem in time <em>O</em>(<em>n</em><sup>3</sup>).</li>

</ol>

<h1>Exercise 2</h1>

You are organizing an event where investors can meet founders of young startups during an evening of interesting presentations and good food. You plan to equip the room with round tables of at least three people each, and to enable fruitful conversations, you plan on arranging the seating such that each investor <em>i </em>∈ <em>I </em>has only founders <em>f </em>∈ <em>F </em>as neighbors and vice versa. At the same time, since you know the interests of each investor, you have narrowed down the <em>good </em>pairs (<em>i,f</em>) into a list <em>P </em>⊆ <em>I </em>×<em>F</em>. Design a flow network <em>N </em>such that finding a maximum flow in <em>N </em>solves the problem of whether it is possible to find a seating arrangement with only <em>good </em>pairings. Make sure you give a formal definition of the vertex and edge set of <em>N</em>, and show the correctness of your construction.

<h1>Exercise 3</h1>

As a freelance programmer, you work via a website that offers projects. The website has <em>n </em>projects <em>p </em>∈ <em>P </em>that currently interest you, but in order to work on each, you need to have a certain <em>credit score </em><em>c<sub>p </sub></em>to demonstrate the suitability of your skills. Your current score is <em>C</em>. However, working on each project will also influence your credit by some amount <em>b<sub>p </sub></em>(positive or negative), so after doing one project, your suitability for some of the others might have changed. You can assume that for any <em>p</em>, <em>c<sub>p </sub></em>+ <em>b<sub>p </sub></em>≥ 0. Give an algorithm that finds out whether you can do all <em>n </em>projects in <em>P </em>in some order, or not. Your algorithm must run in time <em>O</em>(<em>n</em>log<em>n</em>). Prove your algorithm’s correctness and running time.

<h1>Exercise 4</h1>

You are tasked with finding the best COVID-19 cure. So far, <em>n </em>candidates have been developed, with codenames <em>c</em><sub>1</sub><em>,c</em><sub>2</sub><em>,…,c<sub>n</sub></em>. To test a single cure, you can add a small amount of it to a vial containing a viral solution. All of them are somewhat effective, but might require a different dose to kill the virus: for example, it could take <em>a</em><sub>4 </sub>= 42 units of <em>c</em><sub>4 </sub>but only <em>a</em><sub>31 </sub>= 6 units of <em>c</em><sub>31</sub>. After putting a certain amount of a cure in a test vial, to decide if the virus has been eliminated you need to perform a complicated test which requires rare and expensive reagents. Since the world will need a very large amount of the cure, you want to find the most effective one with high precision: i.e., you want the cure <em>c<sub>i </sub></em>∈ {<em>c</em><sub>1</sub><em>,…,c<sub>n</sub></em>} such that <em>a<sub>i </sub></em>is minimal. Specifically, you already know that <em>d </em>units of any cure will kill the virus and want to find the best one. Describe an algorithm to solve this task, using as few tests as possible.

<ol>

 <li>Find a deterministic algorithm that uses <em>O</em>(<em>n</em>log<em>d</em>).</li>

 <li>Find a randomized algorithm that uses <em>O</em>(<em>n </em>+ log<em>n </em> log<em>d</em>) tests.</li>

</ol>