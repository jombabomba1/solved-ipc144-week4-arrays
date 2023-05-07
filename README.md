Download Link: https://assignmentchef.com/product/solved-ipc144-week4-arrays
<br>
In this workshop, you will code a user-friendly C-language program with an array data structure that processes the elements of the array logically

<strong>LEARNING OUTCOMES </strong>

Upon successful completion of this workshop, you will have demonstrated the abilities:

<ul>

 <li>to store data of common type using an array structure</li>

 <li>to associate related data using parallel arrays</li>

 <li>to process the elements of an array using an iteration construct</li>

 <li>to describe to your instructor what you have learned in completing this workshop</li>

</ul>




<strong>IN-LAB:</strong>

Download or clone workshop 4 (<strong>WS04</strong>) from <a href="https://github.com/Seneca-144100/IPC-Workshops">https://github.com/Seneca</a><a href="https://github.com/Seneca-144100/IPC-Workshops">144100/IPC</a><a href="https://github.com/Seneca-144100/IPC-Workshops">–</a><a href="https://github.com/Seneca-144100/IPC-Workshops">Workshops</a> <strong> </strong>

Code a program in a file called <strong>temps2.c</strong> that does the following:

<ol>

 <li>All temperatures entered by the user must be stored in matching (parallel) arrays.</li>

 <li>Print the title of the application.</li>

</ol>

&gt;—=== IPC Temperature Calculator V2.0 ===—&lt;

<ol start="3">

 <li>Prompt the user to enter the number of days for which the temperature will be tracked. The value entered must be between 3 and 10, inclusive.</li>

</ol>




Please enter the number of days, between 3 and 10, inclusive:




<ol start="4">

 <li>If the user does not enter a value in the correct range, print the following error message:</li>

</ol>




Invalid entry, please enter a number between 3 and 10, inclusive:




Keep doing this until a valid number is input by the user.

<ol start="5">

 <li>Using a for loop, prompt the user to enter the high and low temperature until data is entered for the required number of days, store the values entered in matching (parallel) arrays:</li>

</ol>




<table width="98">

 <tbody>

  <tr>

   <td width="98">Day 1 – High</td>

  </tr>

  <tr>

   <td width="98">Day 1 – Low:</td>

  </tr>

 </tbody>

</table>

: (read user input from stdin*)

(read user input from stdin*)




*stdin: what the user types in (keyboard)




<ol start="6">

 <li>When the process is finished, display the values entered.</li>

</ol>




Output example:

—=== IPC Temperature Calculator V2.0 ===—

Please enter the number of days, between 3 and 10, inclusive: <strong>2</strong>

Invalid entry, please enter a number between 3 and 10, inclusive: <strong>4</strong>




Day 1 – High: <strong>6</strong>

<a href="#_Toc7065">Day 1 – Low:——————————————————– <strong>2 </strong></a>

<a href="#_Toc7066">Day 2 – High: <strong>8</strong> —————————————————– </a>

<a href="#_Toc7067">Day 2 – Low: <strong>-1</strong> Day 3 – High: <strong>7</strong> Day 3 – Low:———————— <strong>3 </strong></a>

<a href="#_Toc7068">Day 4 – High: <strong>9</strong> —————————————————– </a>

<a href="#_Toc7069">Day 4 – Low:——————————————————– <strong>4 </strong></a>




<h1><a name="_Toc7065"></a>Day  Hi  Low</h1>

<ul>

 <li>6 -2</li>

 <li>8 -1</li>

 <li>7 -3</li>

 <li>9 -4</li>

</ul>




<strong>IN_LAB SUBMISSION: </strong>

To test and demonstrate execution of your program use the same data as the output example above, including the erroneous entries (the mistakes).

If not on matrix already, upload your <strong>temps2.c</strong> to your matrix account. Compile and run your code and make sure everything works properly.

Then run the following script from your account and follow the instructions (replace profname.proflastname with your professors Seneca userid and <u>replace</u> <strong>SAA</strong> with <u>your</u> section):

<strong> </strong>

<strong>~profname.proflastname/submit 144SAA_w4_lab &lt;ENTER&gt;  </strong>

<strong> </strong>

<strong><u>Please Note</u></strong>

<ul>

 <li>A successful submission does not guarantee full credit for this workshop.</li>

 <li>If the professor is not satisfied with your implementation, your professor may ask you to resubmit. Resubmissions will attract a penalty.</li>

</ul>

<strong> </strong>

<strong>AT_HOME: (30%) </strong>

After completing the <strong>in_lab</strong> section, upgrade your code in <strong>temps2.c</strong> to:

<ul>

 <li>Display the highest temperature, and the day on which it occurred</li>

 <li>Display the lowest temperature, and the day on which it occurred</li>

 <li>Calculate and display the mean (average) temperature for a period entered by the user, until the user enters -1.</li>

</ul>




Output Example

<strong> </strong>

<strong>—=== IPC Temperature Calculator V2.0 ===—</strong>

<strong>Please enter the number of days, between 3 and 10, inclusive: </strong><strong>11</strong><strong>  </strong>

<strong>Invalid entry, please enter a number between 3 and 10, inclusive: </strong><strong>5</strong><strong>  </strong>

<strong>Day 1 – High: </strong><strong>6</strong>

<strong>Day 1 – Low: </strong><strong>-2</strong>

<h1><a name="_Toc7066"></a>Day 2 – High: 9</h1>

<h1><a name="_Toc7067"></a>Day 2 – Low: -1</h1>

<strong>Day 3 – High: </strong><strong>7</strong>

<strong>Day 3 – Low: </strong><strong>-3</strong>

<h1><a name="_Toc7068"></a>Day 4 – High: 8</h1>

<h1><a name="_Toc7069"></a>Day 4 – Low: -9</h1>

<strong>Day 5 – High: </strong><strong>5</strong>

<strong>Day 5 – Low: </strong><strong>-8</strong>

<strong> </strong>

<strong>Day  Hi  Low</strong>

<ul>

 <li><strong>6 -2</strong></li>

 <li><strong>9 -1</strong></li>

 <li><strong>7 -3</strong></li>

 <li><strong>8 -9</strong></li>

 <li><strong>5 -8</strong></li>

</ul>

<strong> </strong>

<strong>The highest temperature was 9, on day 2</strong>

<strong>The lowest temperature was -9, on day 4</strong>

<strong> </strong>

<strong>Enter a number between 1 and 5 to see the average temperature for the entered number of days, enter a negative number to exit: </strong><strong>6</strong>

<strong> </strong>

<strong>Invalid entry, please enter a number between 1 and 5, inclusive: </strong><strong>7</strong>

<strong> </strong>

<strong>Invalid entry, please enter a number between 1 and 5, inclusive: </strong><strong>3</strong>

<strong> </strong>

<strong>The average temperature up to day 3 is: 2.67</strong>

<strong> </strong>

<strong>Enter a number between 1 and 5 to see the average temperature for the entered number of days, enter a negative number to exit: </strong><strong>0</strong>

<strong> </strong>

<strong>Invalid entry, please enter a number between 1 and 5, inclusive: </strong><strong>0</strong><strong>  </strong>

<strong>Invalid entry, please enter a number between 1 and 5, inclusive: </strong><strong>1</strong><strong>  </strong>

<strong>The average temperature up to day 1 is: 2.00</strong>

<strong> </strong>

<strong>Enter a number between 1 and 5 to see the average temperature for the entered number of days, enter a negative number to exit: </strong><strong>2</strong>

<strong> </strong>

<strong>The average temperature up to day 2 is: 3.00</strong>

<strong> </strong>

<strong>Enter a number between 1 and 5 to see the average temperature for the entered number of days, enter a negative number to exit: </strong><strong>5</strong>

<strong> </strong>

<strong>The average temperature up to day 5 is: 1.20</strong>

<strong> </strong>

<strong>Enter a number between 1 and 5 to see the average temperature for the entered number of days, enter a negative number to exit: </strong><strong>-8</strong>

<strong> </strong>

<strong>Goodbye!</strong>                                                                 <strong> </strong>




<strong>AT-HOME REFLECTION</strong>

Please provide answers to the following in a text file named <strong>reflect.txt.</strong>

In three or more paragraphs, explain what you learned while doing this workshop.  <strong>Your answer should <u>at least include the following</u></strong>:

<ul>

 <li>What was good about using arrays – what were the alternatives (how else could you have done it)?</li>

 <li>Comment on the use of parallel (matching) array’s. In what ways were they good and/or bad?</li>

 <li>Iterating (looping) through arrays is a common practice; why is it a best practice to initialize iterator variables to a value of zero (0)?</li>

</ul>

<strong>Reflections will be graded on clarity of thought, correctness of statements made, grammar and spelling.</strong>

<strong><u>Note</u></strong><strong>: when completing the workshop reflection it is a violation of academic policy to cut and paste content from the course notes or any other published source, or to copy the work of another student. </strong>




<strong>AT-HOME SUBMISSION  </strong>

To test and demonstrate execution of your program use the same data as the output example above.

If not on matrix already, upload <strong>temps2.c, </strong>and <strong>reflect.txt</strong> to your matrix account. Compile and run your code and make sure everything works properly.

Then run the following script from your account and follow the instructions (replace profname.proflastname with your professors Seneca userid and <u>replace</u> <strong>SAA</strong> with <u>your</u> section):

<strong>~profname.proflastname/submit 144SAA_w4_home &lt;ENTER&gt;  </strong>

<strong><u>Please Note</u></strong>

<ul>

 <li>A successful submission does not guarantee full credit for this workshop.</li>

 <li>If the professor is not satisfied with your implementation, your professor may ask you to resubmit. Resubmissions will attract a penalty.</li>

</ul>


