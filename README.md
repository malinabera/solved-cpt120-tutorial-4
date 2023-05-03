Download Link: https://assignmentchef.com/product/solved-cpt120-tutorial-4
<br>
<ol start="3">

 <li>Follow the materials under Canvas→<a href="https://rmit.instructure.com/courses/56609/modules">Modules→Week 4</a><a href="https://rmit.instructure.com/courses/56609/modules">…</a></li>

</ol>

<table width="741">

 <tbody>

  <tr>

   <td width="741">5.1 Extend the CPT120GradeMaker (refer to solution from last week, if necessary) so that the user enters how many marks they would like to process. Your program should then use a while-loop in the format of ‘scenario 1’ under Modules→Week 4 lesson PDF to achieve this functionality. Explain in comments what your code would do if the number of marks entered is negative (you can assume only integers will be entered by the user).</td>

  </tr>

  <tr>

   <td width="741">5.2 After completing 5.1 above, make a copy of your main method and rename one of the copies to main51 (so that it does not run as the default main method). Please refer to Gayan’s Monday lectures if you are not familiar with this approach.The copy that was not renamed, which we will use for 5.2, should remain as main, so that it will run when the program is run. Now change the code in the main method to repeat indefinitely (see ‘scenario 2’ under Modules→Week 4 lesson PDF). The rationale is not require the user to enter how many marks they would like to process beforehand.This approach requires you to decide “when to keep repeating”. E.g. after a user enters a particular student’s mark, you can ask the user if they wish to process another student and then repeat the code. Alternatively, you can tell the user to select the ‘cancel’ button (on JOptionPane) or enter an blank string (suitable for Scanner, see String class documentation) or either to finish the processing.In CPT120 Introduction To Programming, you must only use while-loops unless otherwise required by a question. Your while-loop’s condition must eventually fail. The condition must be descriptive of when the loop will continue (e.g. saying while(keepGoing==true) is not an example of a descriptive condition; have the continuation criteria in the condtion as shown in ‘scenario 2’ of the week 4 modules lesson PDF. You must not use break, continue, return, System.exit, etc. or similar <a href="https://docs.oracle.com/javase/tutorial/java/nutsandbolts/branch.html">branching</a> in the middle of methods, loops, if-statements, etc. as doing so is referred to as <a href="https://en.wikipedia.org/wiki/Spaghetti_code">spaghetti code</a><a href="https://en.wikipedia.org/wiki/Spaghetti_code">.</a><strong>Optional: </strong>Validate the inputs so that negative values are rejected (e.g. see “age” validation example in week 4 modules lesson PDF).You may assume that the user will only enter values in the requested data type (e.g. will not enter text when a int is asked for, etc.).</td>

  </tr>

 </tbody>

</table>