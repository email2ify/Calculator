<h1>#Plain Calculator</h1>
This calculator is created to have a simple and plain arithmetic calculator operator using the python language.
It is a simple basic calculator for online users for quick access to calculate numbers when they have no direct handy calculator nearby. The functions of this calculator applied are addition, subtraction, division, and multiplication for the performance of mathematical online computations.

![image](/docs/python2.PNG)

<h2><Strong>Main Image:</strong></h2>

<li>Main Image: </li>
</ul>

<p> This image is the heruko front page of the plain calculator and it is showing the starting image.

![image](/docs/python1.PNG)



<h2><Strong>Features:</strong></h2>

<li>Addition function: </li>
</ul>

<p> This operation is in which the sum of two numbers or quantities is calculated positively. Joining two objects together typically gives it larger value.
An example of addition is the following: 5 + 3 = 8. 
The indicated symbol in the function is +

<li> Subtraction function: </li>
</ul>

<p> A user can use this subtraction function in the calculator to subtract a group or number of things. When you subtract, what is left in the group becomes less. An example of subtraction is the following: 5 - 3 = 2.
The indicated symbol in the function is -

<li> Division function: </li>
</ul>

<p> The state of having a given number divided to give an equal number or products shared. An example of division is the following: 10 / 2 = 5.
The indicated symbol in the function is /

<li> Multiplication function: </li>
</ul>

<p> The multiplying or the condition of being multiplied and its operation is extended to other numbers according to the multiplication function of integers. An example of multiplication is the following: 10 * 2 = 20. 
The indicated symbol in the function is *

<li>Addition image</li>
</ul>

![image](/docs/plus.PNG)


<li>Substration image</li>
</ul>

![image](/docs/substraction.PNG)


<li>Division Image</li>
</ul>

![image](/docs/divide.PNG)


<li>Multiplication image</li>
</ul>

![image](/docs/multiplication.PNG)






<li>Validator Syntax checker</li>
</ul>


<p>Python errors free and pass through the Python Validator Syntax checker. Below is the outcome.

  
  <h4><Strong>For Python code Validator result</strong></h4>

-[Python Syntax Checker](https://extendsclass.com/python-tester/#validate_by_input/)



![image](/docs/new%20checker.PNG)

 <h2><Strong>Technologies</strong></h2>

  
-[Python](https://python.org/)

 
 -[Heroku](https://heroku.com/)
  
 
  
  


<h2><Strong>Testing:</strong></h2>




<li>In this arithmetic calculator, the operational functions are displayed and I was asked to "Enter a number within the operation: (1/ 2/ 3/ 4)" showing a blank space to input a digit within the operational number.
The operations are 1, 2, 3 and 4 digits, the multiplication operation, additional operation, subtraction operation, and divisional operation representing 
the 1,2,3 and 4 digits displayed.</li>
</ul>

<li> I have tested all the operations by inputting one after the other from 1 to 4 to see their functionalities on the blank space, and also the statement given "Enter digit within operation:" with a blank space and after inputting one of the preferred operation between 1/2/3/4, a respond was given to "Enter first number:" with an input blank space and when I inputted number 1 digit, another respond was given to "Enter the second number:" with an input blank space in which number 3 was inputted, inorder to calculate the correct answer. An example: 1 within the operation, 2 for the first input blank space, 3 for the second input blank space then the calculator to calculate the sum of both numbers and the correct answers were given e.g 2.0 - 3.0 =-1 as expected</li>


<li>Each time a calculation is executed, a "Try again? (y/n):" question statement is given if you want to continue with a new calculation with a 'y'(Yes) or 'n'(No) feedback and If 'y'(yes) the calculator will be given a statement as "Enter first number:" and if 'n'(no) a respond message will display "Goodbye and have a nice day."</li>


<li>I have also tried to input a different number outside the operational digit between 1/2/3/4 and the operational loop repect itself for me to "Enter digit within operation: 1/2/3/4. And when I entered digit within the preferred operation the loop continue with "Enter first number" and when I inputted a number, it continued again with the loop "Enter second number" to calculate their values.

<li>I also tested the ZeroDivision on the division arithmetic function by dividing a number with zero and the function loop breaks with an Error code showing "Error: dividing by zero!.</li>

<li>I tested to input unexpected characters, words or number on the input blank space of "TRY again? (y/n):", the loop breaks with a message informing me that it is “invalid input” and asking me to “try again? (y/n)” But when "y"(yes) is specified the loops continue with a message "Enter first number:" again as expected</li>


<li>In conclusion: The overall functions and all element work as expected with no bugs.</li>

<h4><Strong>Image testing page</strong></h4>


![image](/docs/new%20pic%20herok.PNG)


 
 
<h2><Strong>Goals</strong></h2>

 <ul>
<li>The application can also be used to show how python is used to create a simple calculator from a command line.
</ul>
  
  
  
 
   <h2><Strong>Bugs & Fixes</strong></h2>

<ul>
<p>I had bugs, and trailing white spaces, blank errors, missing last line after the function was called. But I was able to figure out the errors by carefully following the intructions of the error lines and the loops. </p>
</ul>
  
  
  <h2><Strong>Unfixed Bugs</strong></h2>

<ul>
<p>None</p>
</ul>


<h2><Strong>Deployment:</h2>
 
-[Heroku](https://www.heroku.com/github-students/signup)

  
  
 </p>
</ul>
<ul>
<p>Make sure the code is ready for deployment.</p>
 <p>Log into Heroku</p>
</ul>
<ul>
<p>From Dashboard click on "New" and select "create new app" from the drop-down menu.</p>
</ul>

<ul>
<p>Choose available name or a special name for your app and select your region.</p>
</ul>
  
</ul>
<ul>
<p>Click "Create App".</p>
 <p>Navigate to "Settings" and scroll down to "build packs".</p>
</ul>
<ul>
<p>Click on "build packs" and then click both "python" and "node.js". Node.js is needed for the mock terminal and must be BELOW python on the list and they can be clicked and dragged to move up or down.</p>
</ul>

<ul>
<p>Navigate to the "Deploy" section.</p>
</ul>
  
  <ul>
<p>Scroll down to "Deployment Method" and select "GitHub".</p>
</ul>
  
  <ul>
<p>Authorize the connection of Heroku to GitHub.</p>
</ul>
  
  <ul>
<p>Search for your GitHub repository name, and select the repository name .</p>
</ul>
  
  <ul>
<p>For Deployment there are two options,  Manual or Automatic Deployments .</p>
</ul>
  <ul>  
(Manual Deployment: This will allow Heroku to build your app when you manually tell it to do so.)
(Automatic Deployment: This will allow Heroku to re-build your app each time you push your code to GitHub.)

</ul></p>

-[GitHub](https://github.com/)

 </p>
</ul>
<ul>
<p>A source code is hosted on GitHub and deployed using Git Pages.</p>
 <p>Used to commit and push code during the development on the Website</p>
</ul>
<ul>
<p>Open the GitHub and then you go to the setting tap and from the setting tap to the pages, select the main or master work</p>
</ul>

 <h2><Strong>Credits</strong></h2>


-[W3School](https://www.w3schools.com/python/gloss_python_arithmetic_operators.asp) Arithmetic operators

-[Code Institute](https://www.youtube.com/watch?v=_gujNhpc0HQ&t=1s) Simple function tutorial using arithmetic

-[YouTube](https://www.youtube.com/watch?v=5_CAo_C523g)  Calculator made easy tutoria
