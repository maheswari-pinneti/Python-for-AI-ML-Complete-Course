# **01 – Introduction to Python**



Complete Notes: Basic to Advanced

Module 01



**Subject:** Python Programming\
**Level:** Beginner → Intermediate → Advanced\
**Purpose:** Teaching notes, practical understanding, interview preparation and industry applications.

# **1.1 Introduction to Programming**

### **What is Programming?**

**Definition:** Programming is the process of writing instructions that tell a computer how to perform a particular task.

In simple words, programming means communicating with a computer through instructions.

**Real-time example:**

Imagine you want a computer to calculate an employee's monthly salary.

1. Take the employee's basic salary.
2. Add allowances.
3. Subtract deductions.
4. Calculate the final salary.
5. Display the result.

These instructions are called a program when written in a programming language.

**Example:**

```
basic_salary = 30000allowance = 5000deduction = 2000net_salary = basic_salary + allowance - deductionprint(net_salary)
```

Output:

```
33000
```

### **Important terminology**

| Term                 | Definition                                             |
| -------------------- | ------------------------------------------------------ |
| Program              | Set of instructions given to a computer                |
| Programmer           | Person who writes programs                             |
| Programming Language | Language used to communicate instructions to computers |
| Source Code          | Instructions written by a programmer                   |
| Execution            | Running a program                                      |
| Output               | Result produced by a program                           |
| Debugging            | Finding and fixing errors                              |
| Algorithm            | Step-by-step procedure to solve a problem              |
| Flowchart            | Visual representation of an algorithm                  |

# **1.2 What is Python?**

### **Definition**

Python is a high-level, general-purpose, interpreted programming language known for its simple syntax and readability.

It is used in:

- Software development
- Web development
- Artificial Intelligence
- Machine Learning
- Data Analytics
- Data Science
- Automation
- Cybersecurity
- Scientific computing
- API development

**Simple explanation:**

Python is a programming language that allows us to write instructions for computers using simple, readable code.

**Example:**

```
print("Hello, World!")
```

Output:

```
Hello, World!
```

Here, Python displays the message on the screen.

### **What, Why, When, Where, Who and How?**

| Question | Explanation                                                                    |
| -------- | ------------------------------------------------------------------------------ |
| What?    | Python is a programming language.                                              |
| Why?     | To develop applications and solve problems.                                    |
| When?    | When we need to automate, calculate, analyze or develop software.              |
| Where?   | IT companies, startups, research organizations and businesses.                 |
| Who?     | Developers, data scientists, AI engineers, testers and security professionals. |
| How?     | Write Python code and execute it using a Python implementation.                |

# **1.3 History of Python**

[Guido van Rossum - Brief Bio](https://images.openai.com/static-rsc-4/kgUrhOUZwP_oWdXoXVfwqTL-kCiveknLdiA1S_qZvodMVJxPXoAuwuavPu3m_zpICVUK5Katc6L2-osqktZxT3LrRin8dM6JUib2CzC9sFqVO6ZJSzydGU5m0zVKJE_hGWH3YgbGxrkzZ1lAjuocyyQJ0zXGWaWtnvNGfMzTB1Y?purpose=inline)

**Creator: Guido van Rossum**

Python was created by Guido van Rossum. Development began in December 1989, and the first public release was in 1991.

### **Important historical milestones**

| Year    | Event                                             |
| ------- | ------------------------------------------------- |
| 1989    | Python development started                        |
| 1991    | First public release                              |
| 2000    | Python 2.0 released                               |
| 2008    | Python 3.0 released                               |
| 2020    | Python 2 officially reached end of life           |
| Present | Python 3 is the actively maintained major version |

**Remember:**

- Creator – Guido van Rossum.
- Started – 1989.
- First public release – 1991.
- Python 2.0 – 2000.
- Python 3.0 – 2008.

# **1.4 Why is Python popular?**

Python is popular because it is relatively easy to learn, readable and supported by a large ecosystem.

### **Main reasons**

**1. Simple syntax**

Python code is easy to read.

```
print("Welcome to Python")
```

**2. Open source**

Python is freely available to use, modify and distribute under its license.

**3. Cross-platform**

Python works on Windows, Linux and macOS.

**4. Large library ecosystem**

Python provides thousands of third-party packages.

**5. Versatile**

One programming language can be used in different technical fields.

**6. Community support**

Developers can access documentation, tutorials and community discussions.

**7. Rapid development**

Python allows developers to build prototypes and applications with relatively little code.

# **1.5 Features of Python**

| Feature                     | Definition                                 | Example / Explanation |
| --------------------------- | ------------------------------------------ | --------------------- |
| High-level                  | Hides many low-level hardware details      | Easy-to-read code     |
| Interpreted                 | Executed through a language implementation | Python runtime        |
| Dynamically typed           | Types are determined at runtime            | `x = 10`              |
| Object-oriented             | Supports classes and objects               | `class Student:`      |
| Open source                 | Available under an open-source license     | Free to use           |
| Portable                    | Runs on multiple operating systems         | Windows/Linux         |
| Extensible                  | Can integrate with other languages         | C/C++ extensions      |
| Large libraries             | Supports reusable modules and packages     | NumPy, Pandas         |
| Automatic memory management | Manages object memory automatically        | Garbage collection    |
| Case-sensitive              | Uppercase and lowercase identifiers differ | `name` ≠ `Name`       |

### **Understand important features with examples**

**A. Dynamically typed**

```
x = 100print(x)x = "Python"print(x)
```

Output:

```
100
Python
```

Python allows the variable name `x` to refer to objects of different types at different times.

**B. Case-sensitive**

```
name = "Rahul"Name = "Arun"print(name)print(Name)
```

Output:

```
Rahul
Arun
```

**C. Automatic memory management**

Python manages the memory used by objects and can reclaim memory when objects are no longer needed.

# **1.6 Types of Programming Languages**

Programming languages can be broadly categorized according to their abstraction level.

**1. Low-level languages**

- Machine language
- Assembly language

**2. High-level languages**

- Python
- Java
- JavaScript
- C#
- Ruby
- PHP

### **Difference between low-level and high-level languages**

| Low-level                             | High-level                        |
| ------------------------------------- | --------------------------------- |
| Closer to hardware                    | Closer to human-readable language |
| More hardware-specific                | Generally more portable           |
| Requires more technical understanding | Easier to learn                   |
| Example: Assembly                     | Example: Python                   |

**Important:** Python is a high-level programming language.

# **1.7 Where is Python used?**

Python has applications across many industries.

[React Python Django Fullstack Development | Codebetter](https://images.openai.com/static-rsc-4/Tlq-JJOIZuK3iTEzSVi-mpj5NLLI70FIuD1s4JcQsIxEE4IQpB9pHIXGXJRCjzZ5sOA6VThyzIEVmmwqCgVFbrw6iN0oIDrFDhV1Z5gPkuo9KcqYBYIfhvBh_KvxpxsKlN6Hd1nKi-UsGsfG2YMrMZ0qLw7CJiVE2QdQuqGGnDs?purpose=inline)

**1. Web Development**

Developing websites, web applications, backend services and APIs.

Tools: Django, Flask, FastAPI.

[Kurumsal Eğitim, Makine Öğrenmesi Algoritmaları | Vebende A.Ş. - Kurumsal Özel Eğitim ve Danışmanlık Hizmetleri](https://images.openai.com/static-rsc-4/USkFbXNTEOH-c3BdAC7udZAgls3tDcZhIKNojzIm-M6K3GCLMtQSe9yMXHGE5TSHcK0t915Z4hPfjzhOEVUqG62y-BVXeHOe6WHshscq3l_Tu0I2gnhyj73AhGKGgjUpL1zRQAXSfD6trMdk--FCV22_mGzvTnJ3yDH-RuCKRY4?purpose=inline)

**2. Artificial Intelligence and Machine Learning**

Building prediction models, chatbots, recommendation systems and intelligent applications.

Tools: Scikit-learn, TensorFlow, PyTorch.

[What Is Data Analytics: Everything You Need to Know](https://images.openai.com/static-rsc-4/zbI6dR6Umv7qb12qKOrFlZ9TabqhhHq2sLTc6Y3HQmuOTF1q9-7X0i4mBBDxJEJ_tL2V-uLPUGxXefMquJnGeq2YoBBFHHlkvuCD5cRdXhDX8Cd17pObvrZynyVZCNapP6Z1JinWpQq6dDE8I6-0UyQb8f_2Iv26_nEBiIvoZec?purpose=inline)

**3. Data Analytics**

Processing business data, finding trends and preparing reports.

Tools: Pandas, NumPy, Matplotlib.

[AI-powered cybersecurity ushers in a new era for security operations centers			| 			DigitalShield](https://images.openai.com/static-rsc-4/dCqlj5hOnwhAuJuQI7NFBmXDXQYCdj5Pgfzd66SO9UvGF7j_Jkhm5qawJdIKbsalJdawHfkAQzoc3h7lLnurNlguDnvI3KSARUhgoorFYBqGTJOL94YXKK26nBFpkD6vCoYSA2Hhm4iF9cKb8U-ZMqWdJP6NX3XKAEMTujoADfI?purpose=inline)

**4. Cybersecurity**

Security log analysis, automation, network monitoring and authorized security testing.

Tools: Scapy, Requests, Python standard library.

[Office tasks automation by python by Alexander_z22 | Fiverr](https://images.openai.com/static-rsc-4/_CrBYa4NjgSpD4OSC8P6pdHPNqB_K6kiUdmcGzp-7b7drPUY-T6Y8-w35SWcLw5qIbT0aRSXP6P7-0hehhD3hlwVXqxEhO5by8zHSwTN_oom-SJVEW-rOSWEjcmBtyUNGzpIEW3Z0Zp3y_sMctIKeRyla284VuMINrKqQENJvgo?purpose=inline)

**5. Automation**

Automating repetitive tasks, file handling, Excel reports and browser testing.

Tools: Selenium, PyAutoGUI, openpyxl.

# **1.8 Python vs Other Programming Languages**

| Feature    | Python                  | Java                    | JavaScript         | C                            |
| ---------- | ----------------------- | ----------------------- | ------------------ | ---------------------------- |
| Level      | High                    | High                    | High               | Low-level relative to Python |
| Typing     | Dynamic                 | Static                  | Dynamic            | Static                       |
| Syntax     | Simple                  | More verbose            | Flexible           | More manual                  |
| Execution  | Python implementation   | JVM                     | JavaScript runtime | Compiled                     |
| Common use | AI, automation, backend | Enterprise applications | Web development    | Systems programming          |

### **Example: Display Hello World**

Python:

```
print("Hello World")
```

Java:

```
public class Main {
    public static void main(String[] args) {
        System.out.println("Hello World");
    }
}
```

JavaScript:

```
console.log("Hello World");
```

C:

```
#include <stdio.h>

int main() {
    printf("Hello World");
    return 0;
}
```

**Remember:** Python is popular for its concise syntax, but each language has its own strengths and applications.

# **1.9 How Python Works Internally**

This is an important intermediate-to-advanced concept.

### **Python execution process**

When you write Python code, the typical CPython execution process is:

1. Write source code.
2. Python parses and compiles the code into bytecode.
3. The Python virtual machine executes the bytecode.
4. The program produces the result.

## **Python execution architecture**

**Python Source Code**

hello.py

**Parser and Compiler**

Syntax analysis and bytecode generation

**Python Bytecode**

Intermediate instructions

**Python Virtual Machine**

Executes bytecode instructions

**Program Output**

### **Example**

```
x = 10y = 20print(x + y)
```

Output:

```
30
```

### **What is bytecode?**

Bytecode is an intermediate representation of a program generated by the compiler.

In CPython, bytecode instructions are executed by the Python virtual machine.

### **What is PVM?**

PVM stands for Python Virtual Machine.

It executes Python bytecode.

### **Important terms**

| Term        | Meaning                                                    |
| ----------- | ---------------------------------------------------------- |
| Source code | Original Python program                                    |
| Compiler    | Converts source code into bytecode in CPython              |
| Bytecode    | Intermediate instructions                                  |
| PVM         | Python Virtual Machine                                     |
| Interpreter | Python implementation that processes and executes programs |
| Runtime     | Environment in which a program executes                    |

**Advanced note:** Python is commonly described as interpreted, but CPython uses both compilation to bytecode and virtual-machine execution. Other Python implementations may work differently.

# **1.10 Python Programming Modes**

There are two common ways beginners execute Python programs.

### **A. Interactive Mode**

Interactive mode allows us to execute commands directly in the Python shell.

Example:

```
>>> 10 + 2030>>> print("Hello")Hello>>> 50 * 2100
```

**Advantages:**

- Immediate output.
- Good for testing.
- Useful for learning syntax.

### **B. Script Mode**

Script mode means writing Python code in a file and executing it.

File name: `first_program.py`

```
name = "Maheswari"course = "Python Programming"print("Student Name:", name)print("Course:", course)
```

Run:

```
python first_program.py
```

Output:

```
Student Name: Maheswari
Course: Python Programming
```

**Difference:**

| Interactive Mode             | Script Mode                   |
| ---------------------------- | ----------------------------- |
| Executes individual commands | Executes saved programs       |
| Immediate output             | Output after running the file |
| Suitable for testing         | Suitable for projects         |
| Usually entered in shell     | Written in `.py` files        |

# **1.11 Python Syntax and Basic Structure**

### **What is syntax?**

Syntax refers to the rules for writing valid instructions in a programming language.

Example:

```
print("Hello Python")
```

Explanation:

- `print` – Built-in function.
- `()` – Parentheses.
- `"Hello Python"` – String.
- Complete statement – Displays the message.

### **Python indentation**

Indentation means spaces at the beginning of a code line.

Python uses indentation to define code blocks.

Correct:

```
if True:    print("Welcome")
```

Incorrect:

```
if True:print("Welcome")
```

The second example causes an indentation error.

### **Python comments**

Comments explain code and are not executed as program instructions.

Single-line comment:

```
# This is a commentprint("Hello")
```

Multiline documentation using a docstring:

```
def welcome():    """This function displays a welcome message."""    print("Welcome")
```

# **1.12 Python Built-in Functions – Introduction**

A built-in function is a function already provided by Python.

Some commonly used functions:

| Function  | Purpose                    | Example                 |
| --------- | -------------------------- | ----------------------- |
| `print()` | Display output             | `print("Hello")`        |
| `input()` | Receive user input         | `input("Enter name: ")` |
| `type()`  | Identify data type         | `type(10)`              |
| `len()`   | Count items                | `len("Python")`         |
| `int()`   | Convert to integer         | `int("10")`             |
| `float()` | Convert to decimal         | `float("10.5")`         |
| `str()`   | Convert to string          | `str(100)`              |
| `range()` | Generate integer sequences | `range(5)`              |
| `sum()`   | Calculate total            | `sum([1, 2, 3])`        |
| `max()`   | Find maximum               | `max(10, 20)`           |
| `min()`   | Find minimum               | `min(10, 20)`           |
| `round()` | Round a number             | `round(10.567, 2)`      |

Examples:

```
print("Hello Python")print(type(100))print(len("Programming"))print(max(10, 20, 30))print(sum([10, 20, 30]))
```

Output:

```
Hello Python
<class 'int'>
11
30
60
```

# **1.13 Python Data and Memory – Introduction**

This is a foundation for advanced Python.

### **What is data?**

Data means information that a computer can store and process.

Examples:

- Student name
- Employee ID
- Salary
- Age
- Email address
- Product price

### **What is a variable?**

A variable is a name that refers to an object in Python.

```
name = "Rahul"age = 25salary = 45000
```

Here:

- `name` refers to a string object.
- `age` refers to an integer object.
- `salary` refers to an integer object.

### **What is an object?**

An object is an instance of a Python type that has an identity, a type and a value.

Example:

```
x = 100print(type(x))print(id(x))
```

The `id()` function returns an object's identity value during its lifetime.

### **What is memory management?**

Memory management is the process of allocating and reclaiming memory while a program runs.

Python handles much of this automatically.

We will study variables, objects, memory references and garbage collection in greater depth in their respective modules.

# **1.14 Types of Errors in Python**

An error is a problem that causes a program to fail or produce an incorrect result.

Three important categories:

### **1. Syntax Error**

Occurs when code does not follow Python's syntax rules.

```
print("Hello"
```

### **2. Runtime Error**

Occurs while the program is executing.

```
print(10 / 0)
```

Output:

```
ZeroDivisionError
```

### **3. Logical Error**

The program executes, but the result is incorrect for the intended requirement.

```
a = 10b = 20print(a - b)
```

If the requirement was to add the numbers, this is a logical error.

### **Comparison**

| Error   | When it occurs          | Example          |
| ------- | ----------------------- | ---------------- |
| Syntax  | Code parsing            | Missing bracket  |
| Runtime | During execution        | Division by zero |
| Logical | Incorrect program logic | Wrong formula    |

# **1.15 Python Ecosystem – Libraries and Frameworks**

### **What is a library?**

A library is a collection of reusable code that helps developers perform specific tasks.

### **What is a framework?**

A framework provides a structured foundation for developing applications.

| Technology   | Type                        | Application         |
| ------------ | --------------------------- | ------------------- |
| NumPy        | Library                     | Numerical computing |
| Pandas       | Library                     | Data manipulation   |
| Matplotlib   | Library                     | Visualization       |
| Scikit-learn | Library                     | Machine Learning    |
| TensorFlow   | Framework/library ecosystem | Deep Learning       |
| PyTorch      | Framework                   | Deep Learning       |
| Django       | Framework                   | Web development     |
| Flask        | Web framework               | Backend development |
| FastAPI      | Web framework               | API development     |
| Selenium     | Library/tool                | Browser automation  |

**Remember:**

Library = Reusable tools.

Framework = Structured application foundation.

# **1.16 Practical Programs – Beginner to Intermediate**

These are the first programs students should write independently.

### **Program 1: Hello World**

```
print("Hello World")
```

### **Program 2: Display personal details**

```
print("Name: Rahul")print("Age: 22")print("City: Hyderabad")print("Course: Python")
```

### **Program 3: Addition**

```
a = 10b = 20result = a + bprint("Addition:", result)
```

### **Program 4: Basic calculator**

```
a = 20b = 10print("Addition:", a + b)print("Subtraction:", a - b)print("Multiplication:", a * b)print("Division:", a / b)
```

### **Program 5: Employee information**

```
print("EMPLOYEE DETAILS")print("Employee ID: EMP101")print("Name: Arun")print("Department: IT")print("Designation: Developer")print("Salary: 45000")
```

### **Program 6: Shopping bill**

```
product = "Laptop"price = 50000discount = 5000final_amount = price - discountprint("Product:", product)print("Original Price:", price)print("Discount:", discount)print("Final Amount:", final_amount)
```

### **Program 7: Calculate average**

```
a = 80b = 90c = 70average = (a + b + c) / 3print("Average Marks:", average)
```

### **Program 8: Print a simple timetable**

```
print("PYTHON CLASS TIMETABLE")print("Monday: Introduction")print("Tuesday: Installation")print("Wednesday: Variables")print("Thursday: Operators")print("Friday: Conditions")print("Saturday: Practice")
```

# **1.17 Real-Time Industry Applications**

Understand how the concepts learned in this module connect to actual business systems.

| Industry      | Python application     | Example                     |
| ------------- | ---------------------- | --------------------------- |
| Banking       | Transaction processing | Account transaction reports |
| Healthcare    | Data processing        | Patient data analysis       |
| E-commerce    | Backend services       | Product and order APIs      |
| Education     | Automation             | Student result generation   |
| IT            | Software development   | Backend applications        |
| Cybersecurity | Security automation    | Log monitoring              |
| Finance       | Data analysis          | Expense reports             |
| AI            | Predictive models      | Customer recommendations    |

### **Real-time scenario: Employee Management System**

Imagine a company has 1,000 employees.

The company needs software to manage:

- Employee details.
- Employee salaries.
- Attendance.
- Leave management.
- Department information.
- Performance reports.

Python can be used to develop backend APIs and business logic for this application.

Example:

```
employee_name = "Rahul"employee_id = "EMP101"department = "Development"salary = 45000print("Employee Details")print("Name:", employee_name)print("ID:", employee_id)print("Department:", department)print("Salary:", salary)
```

This is a basic demonstration. A real employee management system would use databases, APIs, authentication and other components.

# **1.18 Interview Questions – Basic to Advanced**

### **Beginner-level questions**

**1. What is Python?**

Python is a high-level, general-purpose programming language known for its simple syntax and readability.

**2. Who developed Python?**

Guido van Rossum.

**3. When was Python first released?**

**4. Is Python case-sensitive?**

Yes. Uppercase and lowercase identifiers are treated differently.

**5. What is the extension of Python files?**

`.py`

**6. Is Python open source?**

Yes.

**7. What is the use of print()?**

It displays information on the output screen.

**8. What is a comment?**

A comment is a note in the source code that is not executed as a program instruction.

**9. What is an interpreter?**

A Python implementation processes and executes Python programs.

**10. What is indentation?**

Indentation means spaces at the beginning of a code line, used to define code blocks.

### **Intermediate-level questions**

**11. Is Python compiled or interpreted?**

Python is commonly described as interpreted. CPython also compiles source code into bytecode before executing it using its virtual machine.

**12. What is bytecode?**

Bytecode is an intermediate representation generated from Python source code.

**13. What is PVM?**

PVM stands for Python Virtual Machine. It executes Python bytecode in CPython.

**14. What is dynamic typing?**

Dynamic typing means the type associated with an object is determined at runtime, without requiring explicit variable type declarations.

**15. What is the difference between a library and a framework?**

A library provides reusable functionality, while a framework provides a structured foundation for building applications.

**16. What is the difference between interactive and script mode?**

Interactive mode executes commands directly, while script mode executes code saved in a file.

**17. What is debugging?**

Debugging is identifying and correcting errors in a program.

### **Advanced-level questions**

**18. How does CPython execute Python code internally?**

CPython parses source code, compiles it into bytecode and executes that bytecode using its virtual machine.

**19. What is garbage collection?**

Garbage collection is a memory-management mechanism that helps reclaim memory used by objects that are no longer needed.

**20. What is the Global Interpreter Lock (GIL)?**

In conventional GIL-enabled CPython builds, the Global Interpreter Lock restricts how multiple threads execute Python bytecode simultaneously. Free-threaded CPython builds are also available.

**21. What is the difference between Python and CPython?**

Python is the language and its broader ecosystem. CPython is the standard and most widely used implementation of Python, written primarily in C.

**22. What is portability?**

Portability means software can run on different operating systems with little or no modification, subject to dependencies and platform-specific behavior.

**23. Why is Python popular in AI and ML?**

Python provides a readable syntax and an extensive ecosystem of libraries for data processing, model development and deployment.

**24. What is the difference between source code and bytecode?**

Source code is the original human-readable Python program. Bytecode is an intermediate representation produced by a Python implementation such as CPython.

**25. Why is Python called a high-level language?**

Because it abstracts many hardware and low-level implementation details, allowing developers to focus on application logic.

# **1.19 Practical Assignments and Homework**

Ask the student to solve these without looking at the examples.

**15 assignments**

0/15 completed

1\. Write your first Hello World program.

2\. Display your complete personal information.

3\. Write a program to display five programming languages.

4\. Create a simple employee information program.

5\. Create a shopping bill.

6\. Write a program to calculate the total of three numbers.

7\. Write a program to calculate the average of five subjects.

8\. Create a weekly class timetable.

9\. Write a program demonstrating comments.

10\. Write a program demonstrating Python's case sensitivity.

11\. Explain how Python executes a program.

12\. Explain the difference between an error and debugging.

13\. List 10 real-world applications of Python.

14\. Compare Python, Java, and JavaScript.

15\. Explain the difference between libraries and frameworks.

# **1.20 Quick Revision – Remember Everything**

| Question                             | Answer                                  |
| ------------------------------------ | --------------------------------------- |
| What is Python?                      | High-level programming language         |
| Who created Python?                  | Guido van Rossum                        |
| When was it first released?          | 1991                                    |
| File extension?                      | `.py`                                   |
| Display function?                    | `print()`                               |
| Input function?                      | `input()`                               |
| Single-line comment?                 | `#`                                     |
| Python is case-sensitive?            | Yes                                     |
| Python is dynamically typed?         | Yes                                     |
| Bytecode?                            | Intermediate representation             |
| PVM?                                 | Python Virtual Machine                  |
| Python's most common implementation? | CPython                                 |
| What is debugging?                   | Finding and fixing errors               |
| What is syntax?                      | Rules for writing code                  |
| What is indentation?                 | Leading whitespace defining code blocks |

## **1.21 Teaching Strategy – How to make students remember**

Use this five-step teaching method for every concept:

1. **Explain:** Give the definition in simple English.
2. **Relate:** Connect the concept to a daily-life example.
3. **Demonstrate:** Write and execute the code.
4. **Practice:** Ask the student to write the code independently.
5. **Recall:** Ask the student to explain the concept without reading notes.

**Important teaching rule:** Don't ask students to memorize programs line by line. Make them understand why each instruction is written and what happens when they change it.

Module 01 – Complete

# **Introduction to Python**

**Learning outcomes**

After completing this module, the student should understand:

- Programming fundamentals.
- Python history and features.
- Python applications.
- Python execution architecture.
- Interactive and script modes.
- Python syntax and indentation.
- Built-in functions.
- Basic errors and debugging.
- Python ecosystem and industry applications.

**Next module in your curriculum:**

02 – Python Installation and Setup

This will be a separate set of detailed notes, covering installation, environment configuration, VS Code, IDLE, terminal commands, PATH, pip and virtual environments.
