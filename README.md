Download Link: https://assignmentchef.com/product/solved-file-based-calc
<br>
This week we will write modify the memory calculator from 06. Sixth Assignment – Memory Calculator to be able to save all of the calculations done to a file. There are multiple ways to do this, but I suggest creating an ArrayList of String objects. Each time the user performs an operation (add, subtract, multiply, divide, or clear), add a new String. For instance, if the current value is 6 and the user chooses to add 2, you would create a new String “6 + 2 = 8” and add that String to the ArrayList. You will also need to add a new “Save” item to the menu. When the user chooses this option, you should call a method that displays a JFileChooser dialog to the user, allow them to select where to save the data, and then write all of the strings from the ArrayList to that file. Be sure to handle exceptions gracefully.

Sample output:

The current value is 0.0

Menu

<ol>

 <li>Add</li>

 <li>Subtract</li>

 <li>Multiply</li>

 <li>Divide</li>

 <li>Clear</li>

 <li>Save</li>

 <li>Quit</li>

</ol>

What would you like to do? 1

What is the second number? 5

The current value is 5.0




Menu

<ol>

 <li>Add</li>

 <li>Subtract</li>

 <li>Multiply</li>

 <li>Divide</li>

 <li>Clear</li>

 <li>Save</li>

 <li>Quit</li>

</ol>

What would you like to do? 2

What is the second number? 3

The current value is 2.0




Menu

<ol>

 <li>Add</li>

 <li>Subtract</li>

 <li>Multiply</li>

 <li>Divide</li>

 <li>Clear</li>

 <li>Save</li>

 <li>Quit</li>

</ol>

What would you like to do? 3

What is the second number? 5

The current value is 10.0







Menu

<ol>

 <li>Add</li>

 <li>Subtract</li>

 <li>Multiply</li>

 <li>Divide</li>

 <li>Clear</li>

 <li>Save</li>

 <li>Quit</li>

</ol>

What would you like to do? 4

What is the second number? 0

The current value is NaN




Menu

<ol>

 <li>Add</li>

 <li>Subtract</li>

 <li>Multiply</li>

 <li>Divide</li>

 <li>Clear</li>

 <li>Save</li>

 <li>Quit</li>

</ol>

What would you like to do? 5

The current value is 0.0




Menu

<ol>

 <li>Add</li>

 <li>Subtract</li>

 <li>Multiply</li>

 <li>Divide</li>

 <li>Clear</li>

 <li>Save</li>

 <li>Quit</li>

</ol>

What would you like to do? 6

The current value is 0.0




Menu

<ol>

 <li>Add</li>

 <li>Subtract</li>

 <li>Multiply</li>

 <li>Divide</li>

 <li>Clear</li>

 <li>Save</li>

 <li>Quit</li>

</ol>

What would you like to do? 7

Goodbye!




The data in the file should look like this:

Initial value is 0

0.0 + 5.0 = 5.0

5.0 – 3.0 = 2.0

2.0 * 5.0 = 10.0

10.0 / 0.0 = NaN

Cleared




You will be graded according to the following rubric:

<ul>

 <li>A save option has been added to the menu: 1 point</li>

 <li>The save option calls a method that displays a JFileChooser dialog and allows the user to select a file: 2 points</li>

 <li>The save method writes to the selected file: 1 point</li>

 <li>The information written to the selected file is correct: 2 points</li>

 <li>Exceptions are handled gracefully (i.e. nice error messages are displayed to the user rather than the stack trace): 1 point</li>

 <li>Your program compiles: 1point</li>

 <li>Your program runs: 1 point</li>

 <li>You follow standard coding conventions (e.g. variable names, indentation, comments, etc.): 1 point</li>

 <li>Note: If your program does not compile, you will receive a score of 0 on the entire assignment</li>

 <li>Note: If you program compiles but does not run, you will receive a score of 0 on the entire assignment</li>

 <li>Note: I your Eclipse project is not exported and uploaded to the eLearn drop box correctly, you will receive a score of 0 on the entire assignment</li>

</ul>