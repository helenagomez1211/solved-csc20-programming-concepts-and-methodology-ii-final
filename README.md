Download Link: https://assignmentchef.com/product/solved-csc20-programming-concepts-and-methodology-ii-final
<br>
Objective: The objective of this project is to practice using files of objects and gain more experiences in developing interactive GUI using Java Swing and AWT toolkits.

Project description:

In this assignment, you are to design a Java program to maintain a binary file of student records for the class. A student record in the file should include the following information:




. ID number, a 9-digit integer.

. Name, a string of characters

. Gender. a character

. Class level, an integer between 1 and 5.

. Age, an integer less than 100.

. 10 lab scores, integers between 0 and 100.

Your program should allow the instructor to do the following:




<ol>

 <li>Create a new class.</li>

 <li>Load students from a file.</li>

 <li>Add new students.</li>

 <li>View/Delete students</li>

 <li>Enter lab scores.</li>

 <li>Backup Students to a file</li>

 <li>Sort Students (optional)</li>

</ol>

User interface requirement:

Your program should have a GUI closely similar to the following.

To submit your project:

<ol>

 <li>A hardcopy of your Java source code.</li>

 <li>Email a softcopy of your source code.</li>

 <li>Demo your program on Athena before 12/06/2018.</li>

</ol>

Programming hint about your program structure




Array of Students

Programming hint about JLabel: To change the font size of a JLabel.

new JLabel(“&lt;html&gt;&lt;font size=5&gt;&lt;b&gt;JLabel text&lt;/b&gt;&lt;/html&gt;”);




Programming hints about JTable and JScrollPane:

<ol>

 <li>In the main method, create a JScrollPane and add it to the center of a JPanel, viewPane.</li>

</ol>

scrollPane = new JScrollPane(); viewPane.add(scrollPane,BorderLayout.CENTER);

<ol start="2">

 <li>In actionPerformed method,</li>

 <li>Create a 2-D array of strings, data.</li>

 <li>Create a JTable.</li>

</ol>

JTable abtable = new JTable(data,columnName);

<ol>

 <li>Use the JTable to create a temporary JScrollPane.</li>

</ol>

JScrollPane tmp = new JScrollPane(abtable);

<ol>

 <li>Get the viewport from the temporary JScrollPane and add it to the original JScrollPane.</li>

</ol>

scrollPane.setViewport(tmp.getViewport());


