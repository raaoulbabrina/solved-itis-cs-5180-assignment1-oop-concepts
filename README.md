Download Link: https://assignmentchef.com/product/solved-itis-cs-5180-assignment1-oop-concepts
<br>
In this assignment you will practice using Data Structures and Object Oriented concepts in Java. <strong><em>Your implementation should target the most efficient algorithms and data structures. You will be graded based on the efficiency of your implementation. You will not be awarded any points if you use simple nested loops to implement the below tasks.</em></strong> You should use one or more of the below data structures:

<ul>

 <li>ArrayList :</li>

 <li>JavaDoc: <a href="https://docs.oracle.com/javase/7/docs/api/java/util/ArrayList.html">http://docs.oracle.com/javase/7/docs/api/java/util/ArrayList.html</a> – Tutorial: <a href="https://docs.oracle.com/javase/tutorial/collections/interfaces/list.html">http://docs.oracle.com/javase/tutorial/collections/interfaces/list.html</a> – HashSet :</li>

 <li>JavaDoc: <a href="https://docs.oracle.com/javase/7/docs/api/java/util/HashSet.html">http://docs.oracle.com/javase/7/docs/api/java/util/HashSet.html</a> – Tutorial: <a href="https://docs.oracle.com/javase/tutorial/collections/interfaces/set.html">http://docs.oracle.com/javase/tutorial/collections/interfaces/set.html</a> – HashMap :</li>

 <li>JavaDoc: <a href="https://docs.oracle.com/javase/7/docs/api/java/util/HashMap.html">http://docs.oracle.com/javase/7/docs/api/java/util/HashMap.html</a></li>

 <li>Tutorial: <a href="https://docs.oracle.com/javase/tutorial/collections/interfaces/map.html">http://docs.oracle.com/javase/tutorial/collections/interfaces/map.html</a></li>

</ul>

<h2>Question 1</h2>

You are provided with the Data class that contains a users array (Data.users) which is an array of users. Each element in the array represents a single user record. Each record is a string formatted as : firstname,lastname,age,email,gender,city,state. You are asked to perform the following tasks:

<ol>

 <li>Your implementation for this question should be included in MainPart1.java file.</li>

 <li>Create a User class that should parse all the parameters for each user. <strong>Hint</strong>: extract each value from a user’s record using Java’s String.split() method and set the delimiter to a comma, see provided code below. Each user record should to be assigned to a User object.</li>

 <li>Your goal is to Print out the TOP 10 oldest users.</li>

 <li><strong>Hint</strong>: To sort use the Collections.sort(). <a href="https://docs.oracle.com/javase/6/docs/api/java/util/Collections.html">http://docs.oracle.com/javase/6/docs/api/java/util/ </a><a href="https://docs.oracle.com/javase/6/docs/api/java/util/Collections.html">html</a></li>

</ol>

<h2>Question 2</h2>

Using the same Data.users array. You are asked to perform the following tasks:

<ol>

 <li>Your implementation for this question should be included in MainPart2.java file.</li>

 <li>The goal is to count the number of users living each state. Print out the list of State, Count order in ascending order by count.</li>

</ol>

<h2>Question 3</h2>

This is a simple programming question that focuses on finding the longest increasing subarray. Given the array A = {1,2,3,2,5,2,4,6,7} the longest increasing subarray is {2,4,6,7}, note that the values have to be contiguous. You are asked to perform the following tasks:

<ol>

 <li>Your implementation for this question should be included in MainPart3.java file. Implement the printLongestSequence method. You are provided with example inputs and outputs in the provided Java project.</li>

</ol>

<h2>Question 4</h2>

In this question you will use the Data.users and Data.otherUsers arrays that include a list of users. You are asked to perform the following tasks:

<ol>

 <li>Your implementation for this question should be included in MainPart4Bonus.java.</li>

 <li>The goal is to print out the users that are exist in both the Data.users and Data.otherUsers. Two users are equal if all their attributes are equal.</li>

 <li>Print out the list of users which exist in both Data.users and Data.otherUsers. The printed list of users should be sorted by state in descending order.</li>

</ol>