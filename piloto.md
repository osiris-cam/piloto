# **Introduction to structured programming**
-------------------------------------------------------------------------------------------------------------------------

## What is a paradigm?  

[Structured programming](https://searchsoftwarequality.techtarget.com/definition/structured-programming-modular-programming) sometimes known as modular programmingis a programming paradigm that facilitates the creation of programs with readable code and reusable components. All modern programming languages support structured programming, but the mechanisms of support, like the syntax of the programming languages, varies.

Where modules or elements of code can be reused from a library, it may also be possible to build structured code using modules written in different languages, as long as they can obey a common module interface or application program interface (API) specification. However, when modules are reused, it's possible to compromise data security and governance, so it's important to define and enforce a privacy policy controlling the use of modules that bring with them implicit data access rights.
According with TechTarget:
> Structured programming encourages dividing an application program into a hierarchy of modules or autonomous elements, which may, in turn, contain other such elements. Within each element, code may be further structured using blocks of related logic designed to improve readability and maintainability. These may include case, which tests a variable against a set of values; Repeat, while and for, which construct loops that continue until a condition is met. In all structured programming languages, an unconditional transfer of control, or goto statement, is deprecated and sometimes not even available.    
Programming paradigms are a way to classify programming languages based on their features.

![Varieties of paradigms](https://media.geeksforgeeks.org/wp-content/uploads/1-344.png)

## [Classification of programming paradigms.](https://www.geeksforgeeks.org/introduction-of-programming-paradigms/) 

### Imperative Programming paradigm. 
It performs step by step task by changing state. The main focus is on how to achieve the goal. The paradigm consist of several statements and after execution of all the result is stored.
1. **Procedural programming paradigm:**:
  This paradigm emphasizes on procedure in terms of underlying machine model. It has the ability to reuse the code and it was boon at that time when it was in use because of its reusability.  
BASIC, Pascal and C are examples of this paradigm.  
  
2. **Object Oriented Programming:**
  The program is written as a collection of classes and object which are meant for communication. More emphasis is on data rather procedure. It can handle almost all kind of real life problems which are today in scenario. Examples: Java, JavaScript, Python, C++, Visual Basic, .NET, Ruby, Scala and PHP
  
3. **Parallel Processing approach:**
  Parallel processing is the processing of program instructions by dividing them among multiple processors. A parallel processing system posses many numbers of processor with the objective of running a program in less time by dividing them. This approach seems to be like divide and conquer.

### Declarative Programming paradigm.
Is a style of building programs that expresses logic of computation without talking about its control flow. The focus is on what needs to be done rather how it should be done basically emphasize on what code code is actually doing. It just declare the result we want rather how it has be produced. Here an example in a code:
 ~ ~ ~
 const container = document.getElementById(‘container’);
const btn = document.createElement(‘button’);
btn.className = ‘btn red’;
btn.onclick = function(event) {
 if (this.classList.contains(‘red’)) {
   this.classList.remove(‘red’);
   this.classList.add(‘blue’);
 } else {
   this.classList.remove(‘blue’);
   this.classList.add(‘red’);
 }
};
container.appendChild(btn);
 ~ ~ ~

1. **Logic Programming paradigm:**
  It can be termed as abstract model of computation. It would solve logical problems like puzzles, series etc. In logic programming we have a knowledge base which we know before and along with the question and knowledge base which is given to machine, it produces result.Examples: Mercury, ECLiPSe, QL, PROGOL, etc. 
  
2. **Functional Programming:**
  The functional programming paradigms has its roots in mathematics and it is language independent. The key principal of this paradigms is the execution of series of mathematical functions. The central model for the abstraction is the function which are meant for some specific computation and not the data structure. Examples:Python, Haskell, Lisp, Erlang y Clojure. 
  
3. **Databases Processing approach:**
  This programming methodology is based on data and its movement. Program statements are defined by data rather than hard-coding a series of steps. Examples: SQL.








## Data representations and operators.  

### Data Representation
- [**Identifier**]( http://aboutc.weebly.com/identifiers.html
): is a string of alphanumeric characters that begins with an alphabetic character or an underscore character that are used to represent various programming elements such as variables, functions, arrays, structures, unions and so on.
- [**Variables**](https://press.rebus.community/programmingfundamentals/chapter/constants-and-variables/
):  is a value that can change, depending on conditions or on information passed to the program.
- **Constants**:  is a value that cannot be altered by the program during normal execution.
- [**Reserved Words**](https://www.computerhope.com/jargon/r/reseword.htm
): are terms or phrases appropriated for special use that may not be utilized in the creation of variable names.
- [**Types of data**]( https://dl.sumdu.edu.ua/textbooks/103395/597162/index.html
): is a type together with a collection of operations to manipulate the type.
  - Primitive: are predefined types of data, which are supported by the programming language. 
    - Boolean (e.g. True or False)
    - Character (e.g. abc)
    - Date (e.g. 03/01/2017)
    - Double (e.g. 1.87651234355743E308)
    - Floating-point number (e.g. 1.23)
    - Integer (e.g. 123)
    - Long (e.g. 123456789)
    - Short (e.g. 0)
    - String (e.g. abc)
    - Void (e.g. no data)
  - **Derivied**: is one whose values are composed of component values. One example is an array.
  - **User defined**: are mathematical models of a set of data values or information that share similar behavior or qualities and that can be specified and identified independent of specific implementations. An abstract data type is defined in term of its data items or its associated operations rather than by its implementation.  
   ![data type](https://2.bp.blogspot.com/-vKeEhq3QPvA/Wvv5BGg8g1I/AAAAAAAAMSQ/-iBoXVQcI0g0tCVuMSA5IlvqqeqxQ1hjgCLcBGAs/s1600/1.jpeg)
- [**Memory space for each data type**](https://www.tutorialspoint.com/cprogramming/c_data_types.htm
):
  - Character: 1 byte
  - Unsigned character: 1 byte
  - Signed Character: 1 byte
  - Integer: 2 or 4 bytes
  - Unsigned Integer: 2 or 4 bytes
  - Short: 2 bytes
  - Unsigned Short: 2 bytes
  - Long: 8 bytes
  - Unsigned Long: 8 bytes
- [Range of values of each data type](https://xcbiology.files.wordpress.com/2015/07/table-e1438380260928.png):
  - Character: -128 to 127 or 0 to 255
  - Unsigned character: 0 to 255
  - Signed Character: -128 to 127
  - Integer: -32,768 to 32,767 or -2,147,483,648 to 2,147,483,647
  - Unsigned Integer: 0 to 65,535 or 0 to 4,294,967,295
  - Short: -32,768 to 32,767
  - Unsigned Short: 0 to 65,535
  - Long: -9223372036854775808 to 9223372036854775807
  - Unsigned Long: 0 to 18446744073709551615
- [**Data type conversion**](https://developerinsider.co/type-casting-c-programming/
): refers to either implicitly or explicitly changing a value from one data type storage format to another, e.g. a 16-bit integer to a 32-bit integer.  
Continued there is a graphic representation about data types from [Xin's story](https://datachenblog.com/2015/07/31/cc-data-type-and-memory-management/)

![C/ c++ data types and memory](https://xcbiology.files.wordpress.com/2015/07/table-e1438380260928.png)

### Operators
- ***Conditional***: is an operator that returns one of two values depending on the result of an expression. It is represent with **“?:”**
- ***Logical***: Returns the result of a boolean operation.
  - Negation: It represents with **!**.
  - AND: It represents with **&&**.
  - Inclusive Or: It represents with **||**.
- ***Relationship***: are used to compare values of two variables.
  - Greater than >.
  - Greater than or equal to **>=**
  - Less than <
  - Less than or equal to **<=**
  - Equal to **==**
  - Not equal to **!=**
  
  Below is a descriptive image taken from the National Institute of [Open Schooling](http://oer.nios.ac.in/wiki/index.php/List_of_operators_used_in_JavaScript)
  ![List of operators in c](https://lh3.googleusercontent.com/proxy/UtM0k2eyWDmdXxG5bV7e7sxtpvYMghuY18pxA8-IzV6T3w5aJ1R0xZr5c6hD5Oo0Nw5hPYwg_v6j6D31iXG2MwQvZMPWvmrbBwCLHvAB)
  
  ## Version control.  
  
[Version control](https://www.git-tower.com/learn/git/ebook/en/command-line/basics/what-is-version-control) is a piece of software that allows a person to manage the various changes made to a file. In other words, the version control tool is used to encode versions, binary and digital files.
Version control is sometimes called revision control and is a priority component in software configuration management. 

### How Does Version Control Work?
This tool allows many developers to work together on the same protector. This happens when the project becomes more complex and there is a need to handle multiple versions.

Version control is important for all code, files, and assets that multiple team members will collaborate on. Using version control software helps you keep track of changes and keep every team member working off the latest version. 
It needs to do more than just manage and track files. It should help you develop and ship products faster. 

That’s because using the right one:  
- Improves visibility. 
- Helps teams collaborate around the world. 
- Accelerates product delivery.  

![How does it work](https://miro.medium.com/max/1248/1*l08qyjBnX7K12p4DcINn3w.png)

#### Varieties: Distributed and centralized version control.
According with Michael Ernst, [there are two types of version control](https://homes.cs.washington.edu/~mernst/advice/version-control.html), **centralized** and **distributed**. **Distributed** is  much faster to execute because it has more functions. All developers have their own copy of the repository, with all versions and all history. Of course, as they develop and make changes, their sources and versions are different from each other. However it is a little more complex and there is no main repository.  

![Distributed](https://homes.cs.washington.edu/~mernst/advice/version-control-fig3.png)  

##### Examples:
1. Git.
2. Baazaar.
3. Mercurial.
4. Darcs.  

On the other hand, in the **centralized** all the sources and their versions are stored in a single directory, which is called the source repository, of a computer (server). For this reason, developers who want to work with those fonts should ask the version control system for a local copy to work with.  

![Centralized](https://homes.cs.washington.edu/~mernst/advice/version-control-fig2.png)

##### Examples:
1. CVS.
2. Subversion.


## ***Equipo***:
1. Osiris Cámara Salinas.
2. Victor Uribe Hernandez. 
