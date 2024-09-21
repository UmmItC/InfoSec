---
title: "L1 - Introduction to Computer Programming"
date: 2024-09-20T18:23:32+0800
tags: ["Computer Programming", "Basic Concept", "L1", "School Course"]
lastmod: 2024-09-21T21:49:50+0800
---

## Learing Objectives

The typical objectives of computer have `Hardware` and `Software`.

## Programming Languages

There are many programming languages, such as `Python`, `Java`, `C++`, `C#`, `JavaScript`, etc.

### Low-level Programming Languages

- `Machine Code`
- `Assembly Language`
- `C` Programming Language

### High-level Programming Languages

- `Python`
- `Java`
- `C++`
- `C#`

They also provide the object-oriented programming (OOP) features.

### Issues Related to Programming languages

For the programming languages, there are some issues related to them, like:

- Data structures and Algorthms
- The softwarre development process
- Design and development

How to manage the software development process is very important. Since the software development process is very complex, we need to have a good design and development process.

How did you mange your code, work with your team members, and how to make the software development process more efficient. This is the key point of the software development process.

## Central Processing Unit, as known as CPU

The Central Processing Unit (CPU) serves as the brain of a computer, executing instructions from programs by performing various operations, including arithmetic and logical functions, as well as input and output tasks.

Each CPU is designed to understand and execute a specific set of instructions known as its instruction set, with the program codes at this level referred to as machine code, which is written in machine language. Typically, CPUs are built as a single microchip, commonly referred to as a microprocessor.

### CPU major units

The Central Processing Unit (CPU) has two main parts:

- Control Unit
- Arithmetic and Logic Unit (ALU). 

The Control Unit manages and oversees the computer's overall operation, keeping track of where the next instruction is stored in memory.

The ALU is responsible for performing calculations and comparisons, such as addition and subtraction. 

It takes two types of inputs: the `opcode`, which tells it what operation to perform (like adding numbers), and the `operand`, which is the data it needs to work with (like the two numbers to add).

### Main Memory Unit

The Main Memory Unit is the computer's primary storage area, where data and instructions are stored for processing. It is also known as Random Access Memory (RAM).

Main memory stores data and instructions necessary for a computer to run programs. For a program to operate, it must first be loaded into main memory. The data and instructions in memory are organized with unique addresses, much like room numbers in a large building. 

There are two main types of memory: 

1. **Random Access Memory (RAM)**: This type allows any section of memory to be accessed at random. However, it is volatile, meaning that any data stored in RAM is lost when the power is turned off.

2. **Read-Only Memory (ROM)**: Unlike RAM, ROM is non-volatile, so the data remains even when the power is off. While it can be difficult to modify, ROM is often used to store the programs needed for starting up the computer.

## Secondary Storage and Input / Ouput Units

### Secondary Storage

Secondary storage is used for permanent storage of programs and data. Examples include:

- **Hard Disks**
- **Optical Disks**

### Input/Output Units

The Input/Output (I/O) Unit provides access to the computer, allowing it to input and output data. It serves as the interface for peripheral devices, such as:

- **Keyboards**
- **Mice**
- **Monitors**
- **Printers**

## Computer Software

Computer software is a collection of programs and related data that instructs a computer on what tasks to perform and how to do them.

### Application Software

- **Definition**: Programs designed to perform specific tasks for users.
- **Development**: Most software developers and programmers focus on creating application software, including beginners and learners.

### System Software

- **Definition**: A collection of programs that allow the computer to operate effectively.
  
  - **Operating System**: A crucial type of system software that manages hardware and software resources, enabling multitasking and overall control of the computer.
  
  - **Other System Software**: Includes hardware device drivers, such as printer drivers, which help the operating system communicate with hardware devices.

## Data Representation

Computers do not store and access data using the same symbols that humans typically use, such as text. Instead, they fundamentally work with binary data, consisting of just two values: 0 and 1.

### Binary Data

- **Binary Bit**: The smallest unit of data in a computer, which can represent:
  - 0 or 1
  - OFF or ON
  - FALSE or TRUE
  - Open or closed switch

### Bytes

- **Grouping**: Eight bits combine to form a larger unit called a byte (8 bits = 1 Byte).
- **Representation**: One byte can represent one of 256 distinct patterns, corresponding to values ranging from 0 to 255.

### Character Codes

Collections of binary patterns (0s and 1s) are used to represent letters, digits, and other characters. These are known as character codes:

- **ASCII**: The American Standard Code for Information Interchange, originally based on the English alphabet.
- **Unicode**: An international standard that supports most writing systems in the world, beginning with ASCII as a part of its encoding scheme.

### ASCII code example (Decimal)

Just like the following example:

- **A**: 65
- **B**: 66
- **C**: 67
- **D**: 68
- **E**: 69
- **F**: 70
- **"**: 34
- **'**: 39
- **@**: 64

## Programming Languages

**Programming** is the process of creating and developing instructions, programs, or software in a specific programming language that a computer can understand. This process includes designing, writing, testing, debugging, and maintaining the source code of computer programs. Programming for specific tasks often requires expertise in various subjects, including knowledge of the application domain, specialized algorithms, and formal logic.

A **programming language** is a set of instructions used to construct programs. These languages can be broadly categorized into:

- **Low-Level Languages**: This includes machine languages and assembly languages.
- **High-Level Languages**: Generally regarded as more user-friendly and abstracted from the hardware.

## Machine Language

**Machine language** is the set of instructions executed directly by a computer's hardware (the CPU), represented in binary form. 

- This language is specific to the computer’s hardware and can be directly understood and executed by the CPU.
- Programs written in machine language are called **executable programs** (e.g., *.exe files on Windows).
  
### Components of Machine Language

- **Opcode (Operation Code)**: Specifies the operation to be performed.
- **Operands**: One or more data elements on which the operation acts.

**Example Instruction**:
- An instruction to move a value to a register might look like this:
  - `1011 0000` (opcode, indicating the operation)
  - `0110 0001` (operand, indicating the hexadecimal value 61)

## Assembly Language

**Machine code** is challenging for human developers to read and modify because it consists of binary numbers representing opcodes. To make it easier to work with, assembly language substitutes these opcodes and binary values with more human-readable symbols, often resembling words.

### Key Features

- **Human-Readable**: Assembly language uses symbols and mnemonics that are easier for programmers to understand compared to raw binary.
- **Translation Requirement**: An **assembler**, a special program, is needed to convert an assembly language program into machine language. This translation is necessary before the program can be executed directly by the computer. 

By using assembly language, developers can write programs in a format that is simpler to read and modify while still being close to the machine code that the CPU understands.

If you good at Assembly, you can say everything is open source for you.

## Low-Level and High-Level languages

Machine languages and assembly languages are low-level programming languages, meaning they are closely related to the hardware and are more challenging for humans to read and write. In contrast, high-level programming languages are designed to be more user-friendly and abstracted from the hardware.

### Low-Level Languages

- **Machine Languages** and **Assembly Languages** are considered low-level programming languages because their instructions are directly tied to specific types of computer hardware.
- These languages are challenging for human developers to code, read, and modify, particularly when dealing with complex programs.

### High-Level Languages

- All other programming languages that offer higher abstraction levels compared to machine and assembly languages are classified as high-level languages.
- Programs written in a specific high-level language are referred to as **source programs** or **source code**.
- Files containing these source programs are known as **source code files**.

### Translation Process

- In high-level programming languages, a **compiler** or **interpreter** is used to translate the source code into lower-level code, such as machine language, so that it can be executed by the computer.

### Compiler and Interpreter

**Compiler**  
- A **compiler** is a program that translates an entire source program into machine language as a complete unit before any part of the program is executed.
- The output generated by compilers is known as an **object program**, which is the machine language version of the source code.
- Programming languages that utilize a compiler are referred to as **compiled languages**, with examples including C and C++.

**Interpreter**  
- An **interpreter** translates each statement in a high-level source program and executes it immediately after translation.
- Programming languages that rely on an interpreter are known as **interpreted languages**. An example of this is the Python programming language.

## Compiled language and Interpreted language

Compiled languages are typically faster than interpreted languages because the entire program is translated into machine code before execution. However, interpreted languages offer greater flexibility and ease of use, as they can execute code line by line.

As for the example of between `C` and `Python`, `C` is a compiled language, and `Python` is an interpreted language.

`Python` is a non-compiled language, which means that it is not necessary to compile the code before running it. The Python interpreter reads and executes the code line by line, which makes it easier to debug and test the code.

`C` is a compiled language, which means that the code must be compiled before it can be executed. The C compiler translates the code into machine code, which is then executed by the computer.

### Compiled Language (As C Language)

With C, you need to using like `gcc` to compile the code, and then you can run the compiled code.

As the compiled command for `C` code:

```bash
gcc -o helloworld helloworld.c
```

Then you can run the compiled code:

```bash
./helloworld
```

### Interpreted Language (As Python Language)

With Python, you can run the code directly without compiling it.

As the Python code:

```python
print("Hello, World!")
```

You can run the Python code directly:

```bash
python test.py
```

## Procedural and Object-Oriented Languages

Different programming languages support various programming paradigms or approaches, including **Procedural Programming** and **Object-Oriented Programming (OOP)**.

### Procedural Programming Approach
- **Focus**: The procedural programming approach centers on defining self-contained execution units called **procedures** (also known as functions or methods). These procedures contain instructions to perform specific tasks when called.
- **Input and Output**: Procedures often accept data as input (arguments or parameters), process this data, and produce a specific output. 
- **Abstraction**: Users of a procedure do not need to understand its implementation, as long as they know what it does and how to use it. This is known as **procedural abstraction**. For example, in Python, the code `print("Hello World!")` calls the `print()` function to display `Hello World!` on the console, without needing to know how the function is implemented.

### Object-Oriented Programming (OOP)
- **Focus**: OOP emphasizes defining **classes** of objects, which include associated data attributes (or fields) and operations (or methods).
- **Methods**: The operations (methods) of objects are implemented similarly to procedures in procedural programming.
- **Data Abstraction**: External users of an object do not need to know how it is implemented, as long as they understand what it is and what operations it can perform. This is known as **data abstraction**. 

Programming beginners often start with procedural programming. Notably, Python supports both procedural and object-oriented programming approaches.

## Python – A High-Level Language

**Python** is a popular high-level, interpreted programming language that supports both procedural and object-oriented programming.

- **Functions**: Python includes functions (procedures), such as:
  - `print()`: Displays text or string information on the console.
  - `input()`: Prompts the user to enter text on the console.

- **Objects**: In Python, all data values are treated as objects, in line with OOP principles. For example:
  - The value `1` is an object of class `int`, representing integers.
  - The value `1.1` is an object of class `float`, representing real numbers.
  - The string `"Program is fun."` is an object of class `str`, representing strings.

## First simple program of Python using Print function

We can write a simple program in Python to display a message using the `print()` function. For example:

```python
print("Hello, World!")
```

When you run this program, the message `Hello, World!` will be displayed on the console.

Also, python console also offers the interactive mode, which allows you to run Python code line by line, Also known as the `Interactive mode`.

```python
>>> print("Hello, World!")
Hello, World!
>>>
```
## Input function in python

The `input()` function in Python is used to prompt the user to enter text on the console. For example:

```python
name = input("Enter your name: ")
print("Hello, " + name + "!")
```

When you run this program, it will prompt you to enter your name. After you enter your name, the program will display a message that includes your name.

## Source code file or Script file mode

- **Programming Mode**: In Python, it is common to write software using source code files or script files, which are saved with the `.py` extension. These files contain Python code and are executed by the Python interpreter.
  
- **Modules**: Files with the `.py` extension are referred to as **modules**. They can contain reusable code that can be imported into other Python programs.

- **Top-Level Execution**: When a user runs a module directly to start executing a program, it is called **top-level** or a **script**.

- **Importing Modules**: A module can utilize functions or classes from another module using the `import` statement, allowing for code reuse and better organization.

## Python Implementations

Python is a flexible programming language with several versions for different uses. The two main ones are CPython and Jython.

### CPython

CPython is the official version and the most popular. It’s written in C. When you write a Python program, CPython changes your code (.py files) into bytecode (.pyc files), which is then run by the CPython Virtual Machine (VM). This helps your program run on different platforms and speeds up execution.

### Jython

Jython is made for the Java platform. It’s written in Java and converts Python code into Java bytecode, which can run on the Java Virtual Machine (JVM). This is useful if you want to combine Python with Java applications.

## Other issuses related to programming

When tackling programming tasks, it’s essential to plan how to structure data effectively to ensure the program runs efficiently. This involves two critical aspects: data structures and algorithms.

## Data Structures

Data structures focus on organizing data elements in a way that supports efficient operations. A well-chosen data structure can significantly improve the performance of a program, especially when handling large amounts of data. 

For example, in Python, the built-in list type allows for the creation of a sequential collection of elements. It provides useful operations such as `append()` to add items and `insert()` to place items at specific positions, facilitating effective data management.

## Algorithms

An algorithm is a clear, step-by-step set of instructions for solving a specific problem or performing a task. It outlines how to manipulate data within the chosen data structures to achieve desired outcomes.

Algorithms can be represented in several ways, each suited for different purposes. Here are three common representations:

## Pseudocode

Pseudocode uses English phrases to describe an algorithm in a way that’s easy to understand. It doesn’t follow specific programming syntax, making it an informal way to summarize a program’s steps or workflow. This helps clarify the logic of the algorithm without getting bogged down by coding details.

## Flowchart

A flowchart visually represents an algorithm using defined shapes and arrows. Each shape corresponds to a specific type of action or decision, helping to illustrate the flow of the process. Flowcharts are useful for visual learners and can make complex algorithms easier to grasp at a glance.

## Formula

In some cases, algorithms can be expressed using mathematical formulas. These equations succinctly describe the operations involved in the algorithm, making them particularly useful for mathematical or computational tasks.

## Software Development Process

The software development process involves designing, creating, and maintaining software applications. It encompasses various stages, from initial planning to final deployment, and requires collaboration among team members with diverse skills.

- Program requirements
- Analyze the Problem
- Select an Overall Solution algorithms
- Write the program
- Test and debug more and more

And repeat the above steps.

## Artificial Intelligence (AI)

Artificial intelligence (AI) refers to the simulation of human intelligence processes by machines, particularly computer systems. This encompasses a range of applications, including expert systems, natural language processing, speech recognition, and machine vision.

The term `artificial intelligence` was coined in the 1950s and has since evolved to cover a dynamic set of capabilities as technology advances. Key technologies under the AI umbrella include machine learning and deep learning, which enable machines to learn from data and improve their performance over time.

# Machine Learning vs. Deep Learning

## Machine Learning

Machine learning helps software applications get better at predicting outcomes without needing specific programming for each task. It uses past data to make predictions about new situations and works best with large amounts of data.

## Deep Learning

Deep learning is a type of machine learning that uses artificial neural networks to find complex patterns in data. This approach has led to significant advancements in technologies like self-driving cars and chatbots, such as ChatGPT.

## Artificial Narrow Intelligence (ANI): Weak AI

ANI refers to systems designed to perform specific tasks, like playing chess or translating languages. These systems are trained on large datasets to work accurately. Examples include:

- **Speech Recognition** (e.g., Siri, Alexa)
- **Self-Driving Cars**
- **Fraud Detection Systems**

While these systems have achieved many breakthroughs, they are limited to narrow tasks.

## Artificial General Intelligence (AGI): Strong AI

AGI is a theoretical future stage of AI where machines could perform any intellectual task that humans can do. This level of AI is still a concept and not yet a reality.

## Artificial Super Intelligence (ASI)

ASI is the idea of AI that would surpass human intelligence in every way. Such systems could excel in creativity and problem-solving, raising important ethical questions.

### Key Skills in AI Programming

AI programming focuses on several important skills:

- **Learning**: Gaining data and creating rules (algorithms) to turn it into useful information.
- **Reasoning**: Choosing the right algorithm to get the desired results.
- **Self-Correction**: Continuously improving algorithms to make them more accurate.
- **Creativity**: Using different techniques to generate new images, text, and music.

These skills help AI systems perform tasks more effectively and adapt to new challenges.

## Big Data

Big data refers to extremely large datasets that are too complex and massive for traditional data processing systems to manage effectively. These datasets can come in various forms and are generated from multiple sources, such as:

- Social media
- E-commerce platforms
- Sensors
- Government databases
- Financial data
- Telecommunications
- Gaming industries
- System and software logs

### Types of Data

Big data can be classified into three main types:

#### Structured Data

Structured data is well-organized and follows a specific format, such as tables, spreadsheets, and databases. This type of data is easy to enter, query, and analyze.

#### Unstructured Data

Unstructured data does not fit into predefined categories or structures. Examples include text from social media posts, images, videos, and emails. This data can be more challenging to process and analyze due to its varied formats.

Overall, big data encompasses both structured and unstructured data, requiring advanced tools and techniques for effective analysis and utilization.

## The Internet of Things (IoT)

The Internet of Things (IoT) refers to a network of physical objects and devices—like smartphones, smartwatches, home automation controls, and fitness trackers—that can connect and communicate with each other through wired and wireless networks. These devices can generate, exchange, send, and receive data.

### Data Generation

IoT devices produce a large amount of data. When this data is combined with big data, it can be used to train and enhance AI algorithms. This synergy helps improve the efficiency and effectiveness of various applications, making IoT a vital part of the evolving technological landscape.

## Generative AI (GenAI)

Generative AI (GenAI) is a subset of artificial intelligence focused on creating new data or content. This can include:

- **Image and audio synthesis**
- **Text, code, and video generation**
- **Text-to-speech and speech-to-text conversions**

### Applications

Some popular applications of generative AI include ChatGPT, Copilot, POE, LLM, and many others.

### How Does ChatGPT Work?

1. **Input Prompt**: The user provides a prompt or question.
2. **Encoding**: The input is processed and transformed into a format the model can understand.
3. **Attention**: The model assigns weights to different words, determining their importance in the context of the prompt.
4. **Decoding**: The model predicts a sequence of words to form a coherent response.
5. **Output Response**: The generated response is delivered to the user.

This process enables ChatGPT to create relevant and context-aware replies based on the input it receives.
