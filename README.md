Download Link: https://assignmentchef.com/product/solved-cpe434-lab1-overview-of-os-model-and-programming-tools
<br>
The goal of this lab is to familiarize you with your work environment for using the operating systems and to get started with linux processes.

For the most part these notes will apply to whichever environment you are using but you may have as yet unexpected issues with non windows10-wsl2-ubuntu configurations. Please contact the TA’s or myself if issues arise.

You will not have any physical access to UAH computers.  You will have to use them remotely. The only computers authorized for this course are the special ones we are setting up for scheduled, remote access to win10-wsl2-ubuntu

PartI: Entering, Compiling and Running a short program in Lab

For editing and preparing programs, the following notes will present an introduction to the <em>vi </em>text editor and the GNU C++ compiler. There is also a handout. There are several other editors available that you may wish to use instead of <em>vi</em>.

Type the following in terminal. <em>vi </em><em>ﬁ</em><em>lename.cpp </em>(starts the editor) <em>i </em>(enter insert mode)

Following is the code that you will insert in your ﬁle:

<h1>Demo Code</h1>

<h2>Demo Code 1</h2>

<table>

 <tbody>

  <tr>

   <td width="81"></td>

  </tr>

  <tr>

   <td></td>

   <td></td>

  </tr>

 </tbody>

</table>

<strong> </strong>

<strong>Press: [ESC]-colon-wq-[Enter] </strong>after you are done typing the code. This will close the <em>vi </em>editor and save your work.

In terminal, <strong>g++ </strong><strong>ﬁ</strong><strong>lename.cpp -o </strong><strong>ﬁ</strong><strong>lename </strong>[Enter]




The above statement tells gnu compiler to compile your program into ﬁlename which is an executable

In terminal, <strong>/</strong><strong>ﬁ</strong><strong>lename </strong>[Enter] should run the executable

Within <em>vi</em>, you can enter command mode at any time (escape-colon). You can move the cursor with either the j-down, l-left, h-right, k-up keys, or sometimes, but not always, with the cursor keys. A good thing to remember is escape-colon-quit-! which gets you out of the editor without saving the ﬁle (a good thing when something bad has happened).

To understand any command in linux, you can generally execute the <em>man </em>command, for example:

<strong><em>man fork</em></strong>

This should print the man page for fork,. If you are not sure of the command you want to use, you might try the command “apropos searchword”, which looks up commands which have searchword in the man page. Alternatively, you might want to buy a book on linux for a few dollars at the bookstore. Old books are generally ok for understanding commands.

<h1>Extra Demo Codes</h1>

<h2>Demo Code 2</h2>

The following code forks and prints the value of x from both the processes along with their process id.

<table>

 <tbody>

  <tr>

   <td width="81"></td>

  </tr>

  <tr>

   <td></td>

   <td></td>

  </tr>

 </tbody>

</table>




<h3>Assignment 1</h3>




Analyze the output for the demo code above in terms of order in which output statements are printed.

<h2>Demo Code 3</h2>

<table>

 <tbody>

  <tr>

   <td width="81"></td>

  </tr>

  <tr>

   <td></td>

   <td></td>

  </tr>

 </tbody>

</table>

<strong> </strong>

<h3>Assignment 2</h3>

Hoe many processes are created from the above demo code? Explain

<h1>Demo Code 4</h1>

<table>

 <tbody>

  <tr>

   <td width="81"></td>

  </tr>

  <tr>

   <td></td>

   <td></td>

  </tr>

 </tbody>

</table>







<strong> </strong>

<h2>Assignment 3</h2>

What is orphan process? Is there any orphan process in above code? What is pid of orphan process if any is present?

<h1>Part II (Expanding the program in Demo 1)</h1>

<h2>Assignment 4</h2>

For homework, write a program that forks oﬀ 10 children, each of which will print out its pid and its serial number (1,2,3,4,5…10).

<h1>Report Format</h1>

Background (as instructed)

Procedure and Results (what I did −− and what happened when I did it!) Go through the lab step by step and describe what happens as you progress through it. Go idea to have another window open where you can record what is going on as it happens. Make sure to answer any questions that are asked and perform any procedure that is asked of you. These are often underlined. You can capture any output from the program by using the UNIX redirect operator that sends data that normally goes to the screen to a text ﬁle. This can be merged into your report.

Conclusion: Brief statement on what you believe was the major item(s) that you were able to learn and/or demonstrate.