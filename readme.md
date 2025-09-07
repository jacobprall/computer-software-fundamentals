# A crash course on software:

## Chapter 1: Fundamentals

### Part 1: Basics

#### What is a computer?
A computer is composed of two core pieces of functionality: 
- Performing calculations
- Storing data

The computer's **processor** performs calculations using logic gates and Boolean logic. For example, "add two numbers together".

The computer's **memory** keeps the instructions and current state of the running calculations. The processor can access data in memory very quickly, but data stored in memory does not persist when the device is turned off.

The computer's **storage** (aka "hard drive", "disk drive", "floppy disk", etc) persists the results of the ongoing calculations in the physical world for later retrieval and use.

The physical components that make up a computer are referred to as "hardware".

### What is software?
"Software" (aka "code", "programs", "scripts") are the set of instructions written by software engineers (aka "software developers") to be executed by a computer processor. 

The instructions are first written in a programming language. Programming languages are human readable and provide simplified interfaces to interact with the underlying computer hardware (processor, memory, and storage). 

Here is an example of the JavaScript programming language:

```js
// <- these backslashes tell the computer not to read what follows  
// the below line of code initializes a place in computer memory for
//  the string value "Jacob" to live, referenced as the variable "firstName" in the program
var firstName = "Jacob"
var lastName = "Prall"
var fullName = firstName + " " + lastName // concatenate a string with the + operator, save the result to variable labeled "fullName"
print(firstName, lastName, fullName) // send "Jacob", "Prall", "Jacob Prall" to the user
```

If this is in a file and is executed as javascript, it is a program. Most programs in the real world are 10ks, 100k, millions or more lines of code. 
