# COMP1511/1911
## Programming Fundamentals
### Lecture 1
	 The Beginning
Welcome!
---
## What is computing?
---
## What is programming?
---
### Today's Lecture
	* Important details about the lecture format
	* How to get help when you need it
	* How COMP1511 works
	* What is programming?
	* Working in Linux
	* A first look at C
---
## Who am I?
	* Programming
	* Tennis UTR 5.0
	* Coffee
	* Favourite languages: Typescript, Python, C!

/assets/73 questions.png
---
# Course admins!
/assets/andrew.jpg
title: Andrew: Campaigned to change the font size on Aldi chicken nuggets (successfully)
/assets/ibrahim.png
title: Ibrahim: 12kg of apples weekly
/assets/grace.png
title: Grace: "Happiest person of the year" 5 times champ
/assets/sofia.png
title: Andrew: Multi-Award winning travel documentarian
---
	### We have Lecture Moderators!
---
/assets/Clipboard.png
/assets/Clipboard_1.png
/assets/Clipboard 2.png
/assets/Clipboard 3.png
/assets/Clipboard 4.png
/assets/Clipboard_6.png
/assets/Clipboard 5.png
/assets/Clipboard 6.png
/assets/Clipboard 7.png
/assets/Clipboard 8.png
/assets/Clipboard 9.png
/assets/Clipboard 11.png
/assets/Clipboard 13.png
---
## And we can't wait to meet you all <3
	Let's take 5 mins to introduce yourself to your neighbours (physical or virtual)
---
### Important Resources
---
## COMP1511 vs COMP1911
---
	 ### The Course page: https://cgi.cse.unsw.edu.au/~cs1511/25T2/
	* All important course information is on this page
	* We don't use Moodle!
---
### Contacts
	* Administration issues: cs1511@unsw.edu.au
	* Enrolment issues: https://nucleus.unsw.edu.au/en/contact-us
	* Equitable Learning Plan: jake.renzella@unsw.edu.au
---
### Getting help with Programming
	#### The Forum
	* https://discourse02.cse.unsw.edu.au/25T2/COMP1511/
	* Post any content-related questions here!
---
	### Details on Help Sessions, Revision Classes, and more coming soon
---
### Course Format
	* Weekly lectures
	* Weekly tutelabs
	* 2x Major Assignments
	* 1x Final Exam
---
## Lecture Format
	* **Monday**: 11:00 - 13:00 in Ainsworth G03 or Youtube Live
	* **Tuesday**: 11:00 - Youtube Live
---
## Tutorials/Labs
	* Tutelabs are scheduled as a single 3-hour block
	* Go further into topics we cover in the lecture
	* hands-on and practical!
---
## Jake's Major Assignment pro-tips
	* Start it as early as possible
	* Don't plagiarise, we'll get ya
	* Assignment 1 - 20% (Monday 8pm Week 7)
	* Assignment 2 - 25% (Friday 8pm Week 10)
---
## What to do if you can't COMP1511
	Feeling unwell? Need to travel back home for an emergency? Dog ate your assignment?
	* **special considerations**: https://student.unsw.edu.au/special-consideration

---
### Code of Conduct
#### We are here to learn
* Anything connected to COMP1511, including social media, will follow respectful behaviour
* No discrimination of any kind
* No inappropriate behaviour
* No harassment, bullying, aggression or sexual harassment
* Full respect for the privacy of others
---
### Plagiarism, Contract Cheating, ChatGPT, My Neighbour worked on a C compiler
---
## Quick break
---
# Programming Fundamentals
---
## Computers, compilers, programs, C, operating systems, UNIX, Linux, Terminal, Files, functions, oh my...
Throughout COMP1511, we will make sense of it all
---
	## What is a computer?
The ultimate tool in its ability to be reconfigured for different purposes.

The key elements:
* A processor to execute commands
* Memory to store information
---
	## What is Programming?
	Producing a set of instructions and/or data to achieve a task
Providing a computer with specific instructions to solve various problems. We need to use specific languages to write those instructions (code).

At the core of it - problem solving!
You may go through many iterations before you get it right - mistakes are good!
---
## Writing a program is like writing a recipe
	* You provide the steps required to solve the task
	* The computer executes the program, completing it step by step
	* Any mistakes in your recipe will alter the final product (and probably ruin it!)

/assets/photo-1466637574441-749b8f19452f.jpg "Photo by Katie Smith on [Unsplash](https://unsplash.com/photos/avocado-tomatoes-eggs-mushrooms-spring-onions-and-leaves-uQs1802D0CQ)"
---
## How do these *programs* run?
	* Computers are made up of many programs, many executing at the same time!
	* Imagine if your kitchen was used to prepare tens, hundreds of recipes all at once
---
/assets/photo-1516775448597-64ce06b9754e.jpg "Photo by Jason Leung on [Unsplash](https://unsplash.com/photos/white-wooden-kitchen-cabinet-7iuasVqkUjs)"

In this analogy, the computer is the kitchen. If all these programs ran uncontrolled, it would be a mess!
---
	## We need a head chef (operating system)!
---
	An Operating System is the interface between the user and the computer hardware
	Operating Systems:
	* Execute user programs
	* Make sure programs do what they're supposed to
	* Schedules access to limited resources (hardware)
	* Make the computer system convenient to use
Basically, an Operating System sits between our code and the computer, providing essential services
---
	# The Linux Operating System
	* A UNIX-based operating system
	* Open-Source, reliable, lightweight and secure

/assets/Clipboard_20.png
size: contain
Operating systems play an important role in computing, and we will talk more about Linux all term
---
## How do programmers interact with a computer?
/assets/Clipboard_21.png
size: contain
/assets/Clipboard_22.png
size: contain
We use the Terminal. Let's discuss why.
1. It's faster - we can describe what we want to achieve and do it at scale
2. It's closer to how computers work - GUI commands are easy but less flexible!
3. More powerful

---
## The Terminal
	* Send text-based commands to our shell
	* Terminal handles user input, rendering shell output
/assets/Screenshot 2023-09-10 at 8.30.37 pm.png
size: contain

---
## The Shell
	The shell, (bash, zsh) is a program that executes commands, and has its own syntax. It returns output which the terminal can display

/assets/Screenshot 2023-09-10 at 8.32.55 pm.png
size: contain
---
## The Prompt
	The prompt is controlled by the shell, and is the line of text which displays some information
/assets/Screenshot 2023-09-10 at 8.34.13 pm.png
size: contain

---
## How do I use this thing?
---
## Important terminal commands
	* `ls`: Lists all the files in the current directory:
	* `mkdir <dir name>`Makes a new directory called directoryName:
	* `cd <dir name>`: Changes the current directory to directoryName:
	* `cd ..`: Moves up one level of directories (one folder level): 
	* `pwd`: Tells you where you are in the directory structure at the moment:
---
## File operations
	* `cp <source> <destination>`: Copy a file from the source to the destination
	* `mv <source> <destination>`: Move a file from the source to the destination (can also be used to rename)
	`rm filename`: Remove a file (delete)
	*The -r tag can be added to cp or rm commands to recursively go through a directory and perform the command on all the files*
	`cp -r <source> <desitnation>`
---
## But Jake! I don't have a Linux computer!!!
	Don't worry! We have one for you <3
---
/assets/Screenshot 2023-09-10 at 8.44.49 pm.png
---
## Let's get set up together
	* Log into VLAB
	* Open the Terminal
	* Run `1511 setup`
---
## Now we have the tools, so can we write out first program yet?
---
	* Computers execute *precise* instructions described in a *native language* to computers
	* This language is not easy for us to understand:
```
00000000: 0100 0000 0000 0000 0000 0000 0000 0000  
00000010: 1011 0110 0000 0000 0000 0000 0000 0010
00000020: 0000 0100 0110 0000 1001 0000 0000 0000 
```
This would be far too difficult for us to write and understand, so we use programming languages to write instructions for the computer to execute. These programming languages are then translated into machine code by a compiler or interpreter.
---
### Computers need precision!
	So machine code is too precise...
	Why can't we just say "Hey computer! Add two numbers together!
So why can't we just describe what we want in very high level terms? Why can't we just say "Hey computer, I want you to add these two numbers together and print the result"? Well, we can, but the computer doesn't understand English, so we need to use a programming language that the computer can understand.

Even if they could understand English, we would need to be very specific about what we want, and we would need to be able to describe every single thing we want the computer to do. This would be very difficult, and would take a long time to write. Programming languages are designed to be easy to write, and easy to understand, and easy to map to machine code.
---
### Programming
	**Precise** enough to be translated to machine code
	**Simple** enough that a human can (sometimes) understand it.
	A *shared* language
---
### Programming in C
	Why C?
---
### And what a beautiful language
```c
#include <stdio.h>

int main(void)
{
    printf("Hello world");
    return 0;
}
```
---
## Demo (follow along if you can)
	1. Create a .c file using the Terminal
	2. Write our hello world program using VSCode
	3. Save it
---
### Let's break it down
```c
// loads the standard input/output library
#include <stdio.h>

// the main function, the starting point of our program
int main(void) {
    // prints the string to the standard output
    printf("Hello world");
    
    // returns 0 to the operating system
    return 0;
}
```

---
### 	`#include <stdio>`
	* Some tasks are so common, that it would be wasteful to have to write them every time
	* Common code is available for us, in the standard C library
	* We need to tell the compiler which libraries to use
---
## 	`#include <stdio>`
	* In this case, we want the Standard Input Output Library
	This allows us to make text appear on the terminal
	Almost every C program you will write in this course will have this line
---
## The main block
	```c
	int main(void) {
		...
	}
	```
	* The **main function**
	* Every C program must have 1 main function! It's where our program starts!
	* Program runs in sequence, line-by-line starting inside the main block
---
## Blocks of code
```c
{ 
	...
}
```
	Between each `{` and `}` are a block, or group of instructions.
	Blocks are very important! They are how we organise code
---
## The `printf`
```c
{
	printf("Hello world!");
}
```
	printf() makes text appear on the screen. It is a function from stdio.h which we included.
---
### `return 0`
	return is a C keyword that tells the computer that we are now delivering the output of a function. 
	A main function that returns 0 is signifying a correct outcome of the program back to the operating system
---
## Comments!
	* We place “comments” in programs explain to our future selves or our colleagues what we intended for this code
	
	`//` in front of a line makes it a comment`
	
	If we use `/*` and `*/` everything between them will be comments
	
	The compiler will ignore comments, so they can be anything you want really!
---
### Compiling
	Remember, C is a shared language, so we can be productive
	Computers can't understand C
	We need to turn our C code into machine code using a compiler
---
### Compilers are programs
	That turn code into machine code.
	```sh
	dcc program.c -o helloWorld
	./helloWorld
	```
	This compiles a C program into an executable called helloWorld, and runs it
---
/assets/Clipboard_23.png
CSIRAC (/ˈsaɪræk/; Commonwealth Scientific and Industrial Research Automatic Computer), originally known as CSIR Mk 1, was Australia's first digital computer, and the fifth stored program computer in the world.
---
	## Modern technology has changed a lot
	But what hasn't changed
---
## Is computers executing instructions described by humans
/assets/Clipboard_24.png
/assets/Clipboard_25.png
/assets/Screenshot 2023-09-10 at 9.22.58 pm.png
/assets/Clipboard_26.png
---
### What will you build?
---
# Lecture Feedback

/assets/Screenshot 2025-06-01 at 8.24.29 pm.png
size: contain





