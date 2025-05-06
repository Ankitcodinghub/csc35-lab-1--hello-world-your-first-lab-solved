# csc35-lab-1--hello-world-your-first-lab-solved
**TO GET THIS SOLUTION VISIT:** [CSC35 Lab 1 -Hello World… Your first “lab” Solved](https://www.ankitcodinghub.com/product/csc35-lab-1-hello-world-your-first-lab-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;89198&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;4&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (4 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSC35 Lab 1 -Hello World... Your first \u0026quot;lab\u0026quot; Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
            5/5 - (4 votes)    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Lab 1 – Hello World… Your first “lab”

</div>
</div>
<div class="layoutArea">
<div class="column">
Overview

</div>
</div>
<div class="layoutArea">
<div class="column">
It is finally time for your first lab,

Anyway, it is a long-standing tradition in computer science that your first program displays “Hello World” to the screen. This dates back to the first message sent over ARPANET – the predecessor to the Internet.

This week, you will basically get your feet wet with assembly programming. On the next page of this handout, there is a very basic “Hello World” program. Essentially, your only task for this lab is to print the traditional “Hello World!” to the screen followed by some other information.

Connecting to the Server

To do your labs, you need to use your ECS Account. If you don’t have one yet, then I will show you how to create one. Unfortunately, you probably won’t be able to work on your lab today, but you have a week to finish it.

Step 1 – Windows

The three servers that we use to do our labs cannot be accessed from off campus – at least directly. To connect these computers, first connect to Athena using Putty.

Step 1 – Macintosh

Open the Terminal program. This is the same UNIX prompt that you get when you connect to Athena. Mac-OS X is a version of UNIX. Neat! Once at the prompt, type the following where username is your ECS username.

Step 2 – Secure Shell to SP1, SP2, or SP3

Once you are connected, you need to Secure Shell (SSH) to one of the SP computers. Basically, you will connect to Athena and it will connect you to the SP computer. This example uses SP2. You will have to enter your password again and (maybe) have to manually type “yes”.

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>athena.csus.edu
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
ssh username@athena.csus.edu

</div>
</div>
<div class="layoutArea">
<div class="column">
ssh sp2

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
Creating a new file

</div>
</div>
<div class="layoutArea">
<div class="column">
To run nano, type “nano” following by the name of the file you either want to create or edit:

nano lab1.s

Hints

<ul>
<li>First type in the program at the end of this handout verbatim. Then see if you can it to assemble, link, and execute. You don’t have to type the comments, but I recommend it.</li>
<li>Now work on each of the requirements below one at a time. You will turn in the final program, but incremental design is best for labs.Hello World On x86 Linux
Pressley the Lab was helpful enough to write the following program for you! She’s a good doggy!
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
Requirements

</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
<div class="layoutArea">
<div class="column">
You must think of a solution on your own. The requirements are as follows:

1. Print “hello world” to the screen. You can make it “howdy” or any type of greeting you like. This is pretty much done for you already in the sample code.

2. Print the text “My name is” and your full name to the screen.

Do not use the same string as in #1. Create a new label and ASCII text. 3. Print a quote from someone. It can be funny or inspirational.

Do not use the same string as in #1 or #2. Create a new label and ASCII text.

4. Print off the text “I will graduate in year from Sacramento State!” The year must be printed using the PrintInt

subroutine.

Submitting Your Lab

To submit your lab, you must use Alpine – an easy-to-use application much like Nano. However, if your ECS account existed before Fall 2017, you need to configure it to work on SP1, SP2, and SP3. To do this, please type the following verbatim and hit enter. You will only need to do this once.

No space before the period. There is a space before the tilde.

Afterwards, run Alpine by typing the following and, then, enter your username and password.

Please send an e-mail to yourself (on your Outlook, Google account) to check if Alpine is working. To submit your lab, send the assembly file (not a.out or the object file) to:

UNIX Commands

Editing

</div>
</div>
<div class="layoutArea">
<div class="column">
cp /netdisk/skel/.pinerc ~

</div>
</div>
<div class="layoutArea">
<div class="column">
alpine

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>dcook@csus.edu
</pre>
</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Action

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Command

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Notes

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Edit File

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
nano filename

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
“Nano” is an easy to use text editor.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
E-Mail

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
alpine

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
“Alpine” is text-based e-mail application. You will e-mail your assignments it.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Assemble File

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
as -o object source

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Don’t mix up the objectfile and asmfile fields. It will destroy your program!

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Link File

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
ld -o exe object(s)

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Link and create an executable file from one (or more) object files

</div>
</div>
</td>
</tr>
</tbody>
</table>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
Folder Navigation

</div>
</div>
<div class="layoutArea">
<div class="column">
4

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Action

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Command

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Description

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Change current folder

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
cd foldername

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
“Changes Directory”

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Go to parent folder

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
cd ..

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Think of it as the “back button”.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Show current folder

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
pwd

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Gives a file path

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
List files

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
ls

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Lists the files in current directory.

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
File Organization

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Action

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Command

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Description

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Create folder

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
mkdir foldername

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Folders are called directories in UNIX.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Copy file

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
cp oldfile newfile

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Make a copy of an existing file

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Move file

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
mv filename foldername

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Moves a file to a destination folder

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Rename file

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
mv oldname newname

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Note: same command as “move”.

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Delete file

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
rm filename

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Remove (delete) a file. There is no undo.

</div>
</div>
</td>
</tr>
</tbody>
</table>
</div>
