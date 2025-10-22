# About:
These are the notes for Lecture 0 of the CS50x course offered by HarvardX OCW. The lecture is titled Scratch.

## What is CS?

Problem solving 
Computational Thinking

### Binary: 
Maximum number of count using 5 fingers in binary is 31

bit = binary digit

Transistors are essentialy light switches. 1's and 0's.

3 bits = 3 transistors for instance. So patterns are 000, 001, 

Using 3 bits, you can count maximum till 7. 000 represents 0. Since we calculate from 0, we have 2^3 patterns hence we can count till 2^3 - 1.

### Base 10:
123 = 1*100 + 2*10 + 3*1
123 = 1*10^2 + 2*10^1 + 3*10^0

### Counting in Binary:

Let's say 3 bits. 

000 = 0
001 = 1
010 = 2
011 = 3
100 = 4
101 = 5
110 = 6
111 = 7

Let's say 4 bits. Adding a bit requires additional memory. Now you can count up till 15 as 16 total combinations are available. 

8 bits = 1 byte.

0 in 1byte: 

00000000

You have 128, 64, 32, 16, 8, 4, 2, 1.

11111111 = 255. With 0, there are 256 possibilities. 

### ASCII

Take alphabets A-Z, and assign them a number. 

Number 65 is A. 

They used 8 bits to represent ASCII. Enough to represent English.

With 32 bits, or 4 bytes, you can represent 4 biliion possible characters.

### Unicode

Be backwards compatible with ASCII. Goal to represent past present and future. Also represent pictograms or emojis. 

### Representing Colors

Use RGB. Allocate bits or bytes to represent a pixel. 3 numbers in total. 3 bytes used. 24 bits in total. 

Since each byte used for each of the RGB colors, there are total 256 possible values for each color. 0 - 255. 
 
### Algoirthm

Step-by-step instruction to solve some problem. 

Computer takes input, uses algoirthm, and gives an output.

Algorithm is a "precise" instruction. Step-by-step.

Efficient algorithms minimize the time required to do a task. 

Example given of phone book:
To find a name, we can flip through each page. A faster algorithm would be to flip 2 pages at a time and subtract 1.
Or we can split it in half and discard the side it's not on. 

First algorithm is O(n). Second algorithm is O(n/2). Third algoirhtm is O(log base 2 of n).

### Pseudocode

Almost english. Say what you mean. Say it succinctly. Step-by-step.

The pseudocode for the final algorithm would be:
1. Pick up Phone Book.
2. Open to the center of the book.
3. Look at page
4. If person on page, 
5.      call person. 
6. Else if person is earlier in the book, 
7.      Open to middle of the left of the book.
8.      Go back to line 3.
9. Else if person is later in the book,
10.     Open to middle of the right of the book.
11.     Go back to line 3.
12. Else:
13.     Quit.


**Functions** are actions or verbs. In this example, "pick up", "open to", "call", "quit."

**Conditionals** are "if", "else if", "else". They are based on boolean expressions that have a strict yes or no answer. Proverbial forks.
Named after mathematician Bool.

Indentation matters in that pseudocode. 

"Go back to" is a **Loop**.

Artificial Intelligence. 

Train it based on a lot of data. LLMs trained on Neural Networks. So that AI can figure out the if conditionals. As it is impossible to code all conditionals. 

## Scratch:

A GUI based programming language developed by MIT Open Course Ware (OCW). IT works by dragging and dropping blocks. 

Note: C is popular and omnipresent, incredibily fast, and makes devices operate quickly. It provides a conceptual foundation on top which new langauages such as Python will be introduced by abstracting some of the things and provide functionalities for free. 

C looks scary because of the syntax. It comes with time and practice. 

Left side, palatte of puzzle pieces such as motion, looks, sound etc. 

Middle is where we drag and drop the blocks to form code. 

We control 1 or more sprites. Sprites are characters in a game for example.

When green flag clicked: Start.

Top of the character world window, there are green flag symoblizing start and a stop button. 

Purple puzzle pieces are functions. Some functions take an input called parameters. 

Some functions can hand you back a return value. In scratch it is called an "answer." Store the return value as a variable in real code. "Answer" is a return value. 

There are wait blocks under control palette in Scratch.

There are "join" blocks in Operators palette. 

Nesting blocks on top of each other are deliberate such that outputs become the inputs for other functions / algorithms. 

Bottom left has "extensions." Empowered by cloud. For example Text to Speech.

Repeat blocks in Control palette. 

### Abstractions

Why implement meow again? Why go through complexity to build the meow functionality? 

Under "my blocks" palette, create "Make a Block". 

Define "meow". meow is the function name. 

Implementation detail has been abstracted. Meowing has been implemented. Anybody can use the function in the future.

Abstraction is simply the ability to define functions such that the implementation is hidden away for practical future use.

You can add an input to the function if you right click the function and select edit. 

You can add a number or text input. You can add a boolean input. You can also ass a label that simply is a piece of text that allows better readability. 

## Conditionals

In the Control palette, there is a forever block and if conditional blocks. 

Under sensing, there is touching mouise pointer block.

Video sensing extension block available.

## Oscartime. 

Multiple sprites. 





