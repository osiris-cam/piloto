# **Introduction to structured programming**
-------------------------------------------------------------------------------------------------------------------------

## What is a paradigma?  

[Structured programming](https://searchsoftwarequality.techtarget.com/definition/structured-programming-modular-programming) sometimes known as modular programmingis a programming paradigm that facilitates the creation of programs with readable code and reusable components. All modern programming languages support structured programming, but the mechanisms of support, like the syntax of the programming languages, varies.

Where modules or elements of code can be reused from a library, it may also be possible to build structured code using modules written in different languages, as long as they can obey a common module interface or application program interface (API) specification. However, when modules are reused, it's possible to compromise data security and governance, so it's important to define and enforce a privacy policy controlling the use of modules that bring with them implicit data access rights.
According with TechTarget:
> Structured programming encourages dividing an application program into a hierarchy of modules or autonomous elements, which may, in turn, contain other such elements. Within each element, code may be further structured using blocks of related logic designed to improve readability and maintainability. These may include case, which tests a variable against a set of values; Repeat, while and for, which construct loops that continue until a condition is met. In all structured programming languages, an unconditional transfer of control, or goto statement, is deprecated and sometimes not even available.    
Programming paradigms are a way to classify programming languages based on their features.

![Varieties of paradigms](https://media.geeksforgeeks.org/wp-content/uploads/1-344.png)

## Classification of programming paradigms.  

### Declarative: 
Programming by specifying the result you want, not how to get it. The programmer states only what the result should look like, not how to obtain it. No loops, no assignments, etc. Whatever engine that interprets this code is just supposed go get the desired information, and can use whatever approach it wants.

## Data representations and operators.  

### Data Representation
- **Identifier**: is a string of alphanumeric characters that begins with an alphabetic character or an underscore character that are used to represent various programming elements such as variables, functions, arrays, structures, unions and so on.
- **Variables**:  is a value that can change, depending on conditions or on information passed to the program.
- **Constants**:  is a value that cannot be altered by the program during normal execution.
- **Reserved Words**: are terms or phrases appropriated for special use that may not be utilized in the creation of variable names.
- **Types of data**: is a type together with a collection of operations to manipulate the type.
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
- **Memory space for each data type**:
  - Character: 1 byte
  - Unsigned character: 1 byte
  - Signed Character: 1 byte
  - Integer: 2 or 4 bytes
  - Unsigned Integer: 2 or 4 bytes
  - Short: 2 bytes
  - Unsigned Short: 2 bytes
  - Long: 8 bytes
  - Unsigned Long: 8 bytes
- Range of values of each data type:
  - Character: -128 to 127 or 0 to 255
  - Unsigned character: 0 to 255
  - Signed Character: -128 to 127
  - Integer: -32,768 to 32,767 or -2,147,483,648 to 2,147,483,647
  - Unsigned Integer: 0 to 65,535 or 0 to 4,294,967,295
  - Short: -32,768 to 32,767
  - Unsigned Short: 0 to 65,535
  - Long: -9223372036854775808 to 9223372036854775807
  - Unsigned Long: 0 to 18446744073709551615
- Data type conversion: refers to either implicitly or explicitly changing a value from one data type storage format to another, e.g. a 16-bit integer to a 32-bit integer.  
Continued there is a graphic representation about data types from [Xin's story](https://datachenblog.com/2015/07/31/cc-data-type-and-memory-management/)

![C/ c++ data types and memory](https://xcbiology.files.wordpress.com/2015/07/table-e1438380260928.png)

### Operators
- Conditional: is an operator that returns one of two values depending on the result of an expression. It is represent with “?:”.
- Logical: Returns the result of a boolean operation.
  - Negation: It represents with “!”.
  - AND: It represents with “&&”.
  - Inclusive Or: It represents with “l l”.
- Relationship: are used to compare values of two variables.
  - Greater than “>”
  - Greater than or equal to “>=”
  - Less than “<”
  - Less than or equal to “<=”
  - Equal to “==”
  - Not equal to “!=”
  
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
-Improves visibility. 
-Helps teams collaborate around the world. 
-Accelerates product delivery.  

#### Varieties: Distributed and centralized version control.
According with Michael Ernst, [there are two types of version control](https://homes.cs.washington.edu/~mernst/advice/version-control.html), **centralized** and **distributed**. **Distributed** is  much faster to execute because it has more functions. All developers have their own copy of the repository, with all versions and all history. Of course, as they develop and make changes, their sources and versions are different from each other. However it is a little more complex and there is no main repository.  

![Distributed](https://homes.cs.washington.edu/~mernst/advice/version-control-fig3.png)  

##### Examples:
1. Git.
2. Baazaar.
3. Mercurial.
4. Darcs.  

On the other hand, in the **centralized** all the sources and their versions are stored in a single directory, which is called the source repository, of a computer (server). For this reason, developers who want to work with those fonts should ask the version control system for a local copy to work with.  

[Centralized](https://homes.cs.washington.edu/~mernst/advice/version-control-fig2.png)

##### Examples:
1. CVS.
2. Subversion.


## ***Equipo***:
1. Osiris Cámara Salinas.
2. Victor Uribe Hernandez. 
