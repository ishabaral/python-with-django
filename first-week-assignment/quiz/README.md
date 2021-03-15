## Test Your Knowledge: Quiz
1. What are the six main reasons that people choose to use Python?
   > The main reasons to choose python are:
   >   1. Code is easy to read, use and maintain
   >   2. Supports multiple programming paradigms i.e Procedural programming, Object-oriented programming and functional programming
   >   3. Compatible with major operating systems like Windows, Linux, macOS, etc. and architectures like Intel *86, PPC64, etc.
   >  4. Large standard library
   >  5. Cost-effective approach
   >  6. Simplifies the complexities of software development

2. Name four notable companies or organizations using Python today.
   > - Google
   > - Netflix
   > - Dropbox
   > - Instagram 

3. Why might you not want to use Python in an application?
   >- Slower than C or C++
   >- Not a very good language for mobile development
   >- Not a good choice for memory intensive tasks
   >- Python's database access layer is found to be a bit underdeveloped and primitive compared to JDBC AND ODBC

4. What can you do with Python?
   >- Web Development with frameworks like Django and Flask
   >- Data Science — including machine learning, data analysis, and data visualization
   >- Creating bots
   >- Scraping websites
   >- Game development with Pygame
   >- Mobile apps with frameworks like Kivy

5. What’s the significance of the Python import this statement?
   > The Python programming language comes with a variety of built-in functions like print(), abs(), int(), len(), etc. <br/>
  However these built-in functions are limited, and we can make use of `modules` to make more sophisticated programs. <br/>
  Python code in one module gains access to the code in another module by the process of importing it. <br>
  Modules are Python .py files that consist of Python code. Any Python file can be referenced as a module. A Python file called hello.py has the module name of hello that can be imported into other Python files or used on the Python command line interpreter.

6. Why does “spam” show up in so many Python examples in books and on the Web?
   > Spam is a common variable name in Python scripts. It is a piece of Python software built upon NumPy and SciPy for the analysis and manipulation of 3D and 2D data sets in material science. So they appear in Python examples.

7. What is your favorite color?
   > My favorite color is orange.

## Test Your Knowledge: Quiz

1. What is the Python interpreter?
   >The Python interpreter is a virtual machine, meaning that it is software that emulates a physical computer. The Python interpreter is a bytecode interpreter: its input is instruction sets called bytecode. When you write Python, the lexer, parser, and compiler generate code objects for the interpreter to operate on.

2. What is source code?
   >Source code is the sequence of programming language statements written by a programmer. It can be read and easily understood by a human being. After compiling source code, byte code is generated.

3. What is byte code?
   >The bytecode is a low-level platform-independent representation of your source code, however, it is not the binary machine code and cannot be run by the target machine directly. In fact, it is a set of instructions for a virtual machine which is called the Python Virtual Machine (PVM).

4. What is the PVM?
   >The PVM (Python Virtual Machine) is an interpreter that runs the bytecode and is part of the Python system. The bytecode is platform-independent, but PVM is specific to the target machine. After compilation, the bytecode is sent for execution to the PVM.
   PVM is also called Python Interpreter and this is the reason Python is called an Interpreted language.

5. Name two or more variations on Python’s standard execution model.
   >- CPython
   >- Jython(JPython)
   >- IronPython

6. How are CPython, Jython, and IronPython different?
   > | CPython | Jython | IronPython |
   > | --- | --- |--- |
   > | Compiles python code into bytecode. But it doesnot translate Python code to C | Compiles Python code into Java bytecode so that you can run your Python code on the Java Platform or JVM | Compiles the code to Common Language Runtime (CLR)
   > | It provides the highest level of compatibility with Python packages and C extension modules | Using Jython it is possible to call Java library functions from Python itself. and also call Python functions from Java | Using IronPython flavour, you can use .NET framework libraries in Python code. And python code in .Net language


7. What are Stackless and PyPy?
   >Stackless Python is an enhanced version of the Python programming language. It allows programmers to reap the benefits of thread-based programming without the performance and complexity problems associated with conventional threads. It is originated as an attempt to separate the Python execution engine's stack from that of the underlying implementation (C). <br> <br>
   PyPy is an implementation of the Python programming language written in Python. The Interpreter is written in RPython (a subset of Python). PyPy uses (just-in-time compilation). In simple terms JIT uses compilation methods to make interpreter system more efficient and fast. <br> 
   "If you want your code to run faster, you should probably just use PyPy.” — Guido van Rossum (creator of Python).

## Test Your Knowledge: Quiz

1. How can you start an interactive interpreter session?
   >To start an interactive interpreter session, on macOS or linux, open a terminal and simply type "python". On Windows, bring up the command prompt and type "py". The >>> on the terminal represents the standard prompt for the interactive mode. <br> Alternately, select "Python (command line)", "IDLE", or similar program from the task bar/app menu. 

2. Where do you type a system command line to launch a script file?
   >- Open a command-line and type in the word python or py/python3. The >>> on the terminal represents the standard prompt for the interactive mode. Now after >>> type python3 followed by your script file name. e.g. >>>python3 hello.py.

3. Name four or more ways to run the code saved in a script file.
   >1. Interactive Mode
   >2. Command Line
   >3. Text Editor (VS Code)
   >4. IDE (PyCharm)

4. Name two pitfalls related to clicking file icons on Windows.
   >- Desktop icons not responding on first click, opening other icons
   >- The file icons blinking problem

5. Why might you need to reload a module?
   >For efficiency, a module is only loaded once per interpreter session. That’s fine for function and class definitions, which typically make up the bulk of a module’s contents. <br>
   But a module can contain executable statements as well, usually for initialization. Be aware that these statements will only be executed the first time a module is imported. <br>
   If you make a change to a module and need to reload it, you need to either restart the interpreter or use a function called reload() from module importlib.

6. How do you run a script from within IDLE?
   >To execute a file in IDLE, select Run → Run Module from the menu bar. Either option will restart the Python interpreter and then run the code that you've written with a fresh interpreter.

7. Name two pitfalls related to using IDLE.
   >- IDLE can still be hung by some types of programs—especially GUI programs that perform multi-threading.  
   >- IDLE has some usability features that can burn you once you leave the IDLE GUI: a script's variables are automatically imported to the interactive scope in IDLE and working directories are changed when you run a file, for instance, but Python itself does not take such steps in general.

8. What is a namespace, and how does it relate to module files?
   > A namespace is a collection of currently defined symbolic names along with information about the object that each name references. <br>
   Each module file is automatically a namespace— that is, a package of variables reflecting the assignments made at the top level of the file. Namespaces help avoid name collisions in Python programs: because each module file is a self-contained namespace, files must explicitly import other files in order to use their names.


## Test Your Knowledge: Quiz

1. Name four of Python’s core data types.
   >- Numbers
   >- Strings
   >- Lists, Dictionaries, Tuples
   >- Files, Sets

2. Why are they called “core” data types?
   >They are known as core data types because they are effectively built into the Python language—this implies that there is a specific syntax for generating most of them. 

3. What does “immutable” mean, and which three of Python’s core types are considered immutable?
   >An "immutable" object is an object that cannot be changed after it is created. <br>
   Numbers, strings, and tuples in Python are immutable.

4. What does “sequence” mean, and which three types fall into that category?
   >A "sequence" is a positionally ordered collection of objects. <br>
   Strings, lists, and tuples are the sequences in Python.

5. What does “mapping” mean, and which core type is a mapping?
   >"Mapping" denotes an object that maps keys to associated values. <br>
   Python's dictionary is the only mapping type in the core type set.

6. What is “polymorphism,” and why should you care?
   >Polymorphism in python defines methods in the child class that have the same name as the methods in the parent class.<br>
   We should care polymorphism because it allows for flexibility and loose coupling so that code can be extended and easily maintained over time.