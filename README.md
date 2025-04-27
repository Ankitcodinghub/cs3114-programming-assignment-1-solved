# cs3114-programming-assignment-1-solved
**TO GET THIS SOLUTION VISIT:** [CS3114 PROGRAMMING ASSIGNMENT #1 Solved](https://www.ankitcodinghub.com/product/cs3114-programming-assignment-1-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;52947&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;5&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (5 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS3114   PROGRAMMING ASSIGNMENT #1 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (5 votes)    </div>
    </div>
Background: Many applications areas such as computer graphics, geographic information systems, and VLSI design require the ability to store and query a collection of rectangles. In 2D, typical queries include the ability to find all rectangles that cover a query point or query rectangle, and to report all intersections from among the set of rectangles. Adding and removing rectangles from the collection are also fundamental operations.

&nbsp;

For this project, you will create a simple spatial database for handling inserting, deleting, and performing queries on a collection of rectangles. The data structure used to store the collection will be the Binary Search Tree (BST, see Section 7.11 of the OpenDSA textbook for more information about BST).

&nbsp;

<strong>Invocation and I/O Files: </strong>

&nbsp;

The name of the program is Rectangle1 (this is the name where Web-CAT expects the main class to be). There is a single command line parameter that specifies the name of the command file. So, the program would be invoked from the command-line as:

java Rectangle1 {command-file}

Your program will read a series of commands from the command file, with one command per line. No command line will require more than 80 characters. Each command requires certain outputs, whose details will be described by sample test file outputs that we will post. The formats for the commands are as follows. The commands are free-format in that any number of spaces may come before, between, or after the command name and its parameters. All coordinates will be signed values small enough to fit in a 32-bit int variable.

&nbsp;

<h1>insert name x y w h</h1>
Insert a rectangle named name with upper left corner (x, y), width w and height h. It is permissible for two or more rectangles to have the same name, and it is permissible for two or more rectangles to have the same spatial dimensions and position. The name must begin with a letter, and may contain letters, digits, and underscore characters. Names are case sensitive. A rectangle should be rejected for insertion if its height or width are not greater than 0. All rectangles must fit within the “world box” that is 1024 by 1024 units in size and has upper left corner at (0, 0). If a rectangle is all or partly out of this box, it should be rejected for insertion.

&nbsp;

<h1>remove name</h1>
Remove the rectangle with name <em>name</em>. If two or more rectangles have the same name, then any one such rectangle may be removed. If no rectangle exists with this name, it should be so reported.

&nbsp;

<h1>remove x y w h</h1>
Remove the rectangle with the specified dimensions. If two or more rectangles have the same dimensions, then any one such rectangle may be removed. If no rectangle exists with these dimensions, it should be so reported.

&nbsp;

<h1>regionsearch x y w h</h1>
Report all rectangles currently in the database that intersect the query rectangle specified by the <em>regionsearch</em> parameters. For each such rectangle, list out its name and coordinates. A <em>regionsearch</em> command should be rejected if the height or width is not greater than 0. However, it is (syntactically) acceptable for the <em>regionsearch</em> rectangle to be all or partly outside of the 1024 by 1024 world box.

&nbsp;

<strong><em>intersections </em></strong>

Report all pairs of rectangles within the database that intersect.

&nbsp;

<h1>search name</h1>
Return the information about the rectangle(s), if any, that have name <em>name</em>. If there are more than one rectangle with the same name, you should return the info for all of them.

&nbsp;

<h1>dump</h1>
Return a “dump” of the BST. The BST dump should print out each BST node (use the in-order traversal). For each BST node, print that node’s depth and value (rectangle info). At the end, please print out the size of the BST.

&nbsp;

<strong>Implementation and Design Considerations: </strong>

The rectangles will be maintained in a BST, sorted by the name. Use compareTo() to determine the relative ordering of two names, and to determine if two names are identical. You are using the BST to maintain your list of rectangles, but the BST is a general container class. Therefore, it should not be implemented to know anything about rectangles.

&nbsp;

Be aware that for this project, the BST is being asked to do two things. First, the BST will handle searches on rectangle name, which acts as the record’s key value. The BST can do this efficiently, as it will organize its records using the name as the search key. But you also need to do several things that the BST cannot handle well, including removing by rectangle shape, doing a region search, and computing rectangle intersections. So you will need to add functions to the BST to handle these actions. You should design in anticipation of adding a second data structure in Project 2 to handle these actions. Make sure you handle these actions in a general way that does not require the BST to understand its data type.

&nbsp;

The biggest implementation difficulty that you are likely to encounter relates to traversing the BST during the intersections command. The problem is that you need to make a complete traversal of the BST for each rectangle in the BST (comparing it to all of the other 2 rectangles). The leads to the question of how do you remember where you are in the “outer loop” of the operation during the processing of the “inner loop” of the operation. One design choice is to augment the BST with an iterator class. An iterator object tracks a current position within the BST, and has a method that permits the position of the iterator object within the BST to move forward. In this way, one iterator object can be tracking the current rectangle in the “outer loop” of the process, while a second iterator can be used to track the current rectangle for the “inner loop”. For the <em>regionsearch</em> and <em>intersections</em> commands, you need to determine intersections between two rectangles. Rectangles whose edges abut one another, but which do not overlap, are not considered to intersect. For example, (10, 10, 5, 5) and (15, 10, 5, 5) do NOT overlap, while (10, 10, 5, 5) and (14, 10, 5 5) do overlap. Note that rectangles (10, 10, 5, 5) and (11, 11, 1, 1) also overlap.

&nbsp;

<strong>Programming Standards: </strong>

You must conform to good programming/documentation standards. Web-CAT will provide feedback on its evaluation of your coding style, and be used for style grading. Some additional specific advice on a good standard to use:

_ You should include a header comment, preceding main(), specifying the compiler and operating system used and the date completed.

_ Your header comment should describe what your program does; don’t just plagiarize language from this spec.

_ You should include a comment explaining the purpose of every variable or named constant you use in your program.

_ You should use meaningful identifier names that suggest the meaning or purpose of the constant, variable, function, etc. Use a consistent convention for how identifier names appear, such as “camel casing”.

_ Always use named constants or enumerated types instead of literal constants in the code. _ Precede every major block of your code with a comment explaining its purpose. You don’t have to describe how it works unless you do something so sneaky it deserves special recognition.

_ You must use indentation and blank lines to make control structures more readable.

_ Precede each function and/or class method with a header comment describing what the function does, the logical significance of each parameter (if any), and pre- and post-conditions.

&nbsp;

We can’t help you with your code unless we can understand it. Therefore, you should no bring your code to the TAs for debugging help unless it is properly documented and exhibits good programming style. Be sure to begin your internal documentation right from the start. You may only use code you have written, either specifically for this project or for earlier programs, or the codebase provided by the instructor. Note that the textbook code is not designed for the specific purpose of this assignment, and is therefore likely to require modification. It may, however, provide a useful starting point.

&nbsp;

<strong>Deliverables: </strong>

You will implement your project using Eclipse, and you will submit your project using the Eclipse plugin to Web-CAT. Links to the Web-CAT client are posted at the class website. If you make multiple submissions, only your last submission will be evaluated. There is no limit to the number of submissions that you may make.

&nbsp;

You are not required to submit your own test cases with your program. Of course, your program must pass your own test cases. Your grade will be fully determined by test cases that are provided by the graders (TAs). Web-CAT will report to you which test files have passed correctly, and which have not. Note that you will not be given a copy of these test files, only a brief description of what each accomplished in order to guide your own testing process in case you did not pass one of our tests.

&nbsp;

When structuring the source files of your project, use a directory structure; that is, your source files will all be contained in the project “src” directory. Any subdirectories in the project will be ignored.

&nbsp;

You are permitted (and encouraged) to work with a partner on this project. When you work with a partner, then only one member of the pair will make a submission. Both names and emails <strong>must</strong> be included in the documentation and selected on any Web-CAT submission. The last submission from either of the pair members is will be graded.

&nbsp;

&nbsp;

<strong>Pledge: </strong>

Your project submission must include a statement, pledging your conformance to the Honor Code requirements for this course. Specifically, you must include the following pledge statement near the beginning of the file containing the function main() in your program. The text of the pledge will also be posted online.

&nbsp;

// On my honor:

//

// – I have not used source code obtained from another student, // or any other unauthorized source, either modified or // unmodified.

//

// – All source code and documentation used in my program is // either my original work, or was derived by me from the // source code published in the textbook for this course.

//

// – I have not discussed coding details about this project with

// anyone other than my partner (in the case of a joint

// submission), instructor, ACM/UPE tutors or the TAs assigned

// to this course. I understand that I may discuss the concepts

// of this program with other students, and that another student

// may help me debug my program so long as neither of us writes

// anything during the discussion or modifies any computer file // during the discussion. I have violated neither the spirit nor // letter of this restriction.

Programs that do not contain this pledge will not be graded.

&nbsp;
