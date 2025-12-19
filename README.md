# Welcome to Python Programming!

Welcome to my Python learning repository!  
This repository contains each topic notes and examples to help you understand Python programming from basics to advanced topics.  
Here, you'll learn Python step by step, from basics to advanced concepts.

---

## 🛣️ Python Roadmap

<details>
  <summary><strong>1. Basic Python</strong></summary>
  <ul>
    <li><strong>Installation of Python</strong> – Learn what Python is and why it’s popular.</li>
    <li><strong>Introduction to Python</strong> – How to install Python on Windows, macOS, or Linux.</li>
    <li><strong>Comments</strong> - Lines that explain the code and are ignored by Python. </li>
     <li><strong>Print Statement</strong> -used to display output on the screen </li>
    <li><strong>Variables</strong> – Store and manipulate data.</li>
    <li><strong>Data Types</strong> – <code>int</code>, <code>float</code>, <code>str</code>, <code>bool</code>, etc.</li>
    <li><strong>Type Conversion</strong> – Convert between different data types.</li>
    <li><strong>Operators</strong> – Symbols that perform operations on variables and values</li>
    <li><strong>Print Statement</strong> – Display output using <code>print()</code>.</li>
    <li><strong>Libraries</strong> – Introduction to Python libraries.</li>
    <li><strong>Built-in Functions</strong> – Explore Python’s built-in functions.</li>
    <li><strong>Strings</strong> – Manipulate text data.</li>
    <li><strong>Lists</strong> – Ordered, mutable collections.</li>
    <li><strong>Tuples</strong> – Ordered, immutable collections.</li>
    <li><strong>Sets</strong> – Unordered collections of unique elements.</li>
    <li><strong>Dictionaries</strong> – Key-value data structures.</li>
  </ul>
</details>

<details>
  <summary><strong>2. Intermediate Python</strong></summary>
  <ul>
    <li><strong>Control Statements</strong> – <code>if</code>, <code>else</code>, <code>elif</code> usage.</li>
    <li><strong>Conditional Statements</strong> – Decision making in code.</li>
    <li><strong>Jump Statements</strong> – <code>break</code>, <code>continue</code>, <code>pass</code>.</li>
    <li><strong>Functions</strong> – Define and call reusable code blocks.</li>
    <li><strong>Lambda Functions</strong> – Anonymous one-line functions.</li>
    <li><strong>Map, Filter, Reduce</strong> – Functional programming tools.</li>
    <li><strong>Recursion</strong> – Functions calling themselves.</li>
    <li><strong>Comprehensions</strong> – List, dictionary, and set comprehensions.</li>
    <li><strong>File Handling</strong> – Read from and write to files.</li>
  </ul>
</details>

<details>
  <summary><strong>3. Advanced Python</strong></summary>
  <ul>
    <li><strong>Exception Handling</strong> – Manage errors using <code>try</code>, <code>except</code>, <code>finally</code>.</li>
    <li><strong>Object-Oriented Programming (OOP)</strong> – Classes, objects, inheritance, polymorphism.</li>
    <li><strong>Processes</strong> – Process creation and management.</li>
    <li><strong>Threading</strong> – Concurrent execution with threads.</li>
    <li><strong>Multithreading</strong> – Run multiple threads in parallel.</li>
    <li><strong>Multiprocessing</strong> – Run multiple processes for CPU-bound tasks.</li>
    <li><strong>Libraries</strong> – Work with popular libraries:
      <ul>
        <li><code>NumPy</code> – Numerical computations</li>
        <li><code>Pandas</code> – Data analysis and manipulation</li>
        <li><code>Matplotlib</code> – Data visualization</li>
        <li><code>Seaborn</code> – Statistical data visualization</li>
      </ul>
    </li>
  </ul>
</details>

---
<body>
Start from **Basic Python**, gradually move to **Intermediate**, and finally explore **Advanced Python** concepts.  
Happy Learning! 💻

<h1>1. Basic Python</h1>

<h2>Installation of Python</h2>
<p>Download Python from <a href="https://www.python.org/downloads/" target="_blank">python.org</a> and install it.</p>
<p>Verify installation:</p>
<pre><code>python --version</code></pre>


<h2>Introduction to Python</h2>
<div class="box">
<p>Python is a high-level, interpreted, object-oriented, and beginner-friendly programming language created by <b>Guido van Rossum</b>. It is widely used in web development, data science, machine learning, automation, software development, and many other fields.</p>

<p>Python focuses on readability and simplicity, making it easy for beginners to learn and use. It allows you to write code quickly and efficiently, and its large community support ensures plenty of resources and libraries are available.</p>
</div>

<h3>📌Why Learn Python?</h3>
<div class="box">
<ul>
    <li>Easy to write and read</li>
    <li>Large community support</li>
    <li>Used in Data Science, AI, ML, Web Development</li>
    <li>Huge number of built-in libraries</li>
    <li>Useful for automation and scripting</li>
</ul>
</div>

<h3>📌Features of Python</h3>
<div class="box">
<ul>
    <li>Simple and readable syntax</li>
    <li>Platform independent</li>
    <li>Supports Object-Oriented Programming</li>
    <li>Large standard library</li>
    <li>Supports multiple programming paradigms</li>
    <li>Fast development</li>
</ul>
</div>

<h2>Comments in Python</h2>

<p>In Python, comments are used to explain code or make it more readable. Python ignores comments when running the program.</p>

<h3>1️⃣ Single-line Comments</h3>
<p>Use the <code>#</code> symbol. Everything after <code>#</code> is ignored by Python.</p>

<pre>
<code># This is a single-line comment
print("Hello, World!")  # This prints a message
</code>
</pre>

<h3>2️⃣ Multi-line Comments</h3>
<p>Python doesn't have a specific multi-line comment syntax, but you can use triple quotes <code>'''</code> or <code>"""</code> to create a comment block.</p>

<pre>
<code>'''
This is a multi-line comment.
It can span multiple lines.
Useful for explaining code blocks.
'''
print("Python comments example")
</code>
</pre>

<h2>Print Statement in Python</h2>

<h3>1. Basic print()</h3>
<p><strong>Purpose:</strong> To display any message or text on the screen.</p>
<p><strong>Example:</strong><br>
<code>print("Hello Python")</code></p>

<hr>

<h3>2. Printing Numbers</h3>
<p><strong>Purpose:</strong> To show numeric values or results of calculations.</p>
<p><strong>Example:</strong><br>
<code>print(10 + 20)</code></p>

<hr>

<h3>3. Printing Multiple Values</h3>
<p><strong>Purpose:</strong> To print different items in one line separated by space (default).</p>
<p><strong>Example:</strong><br>
<code>print("Age:", 20)</code></p>

<hr>

<h3>4. Using <code>sep</code> (Separator)</h3>
<p><strong>Purpose:</strong> To change the separator between printed values. Default is a space.</p>
<p><strong>Example:</strong><br>
<code>print(1, 2, 3, sep="-")</code></p>

<hr>

<h3>5. Using <code>end</code> (Ending Character)</h3>
<p><strong>Purpose:</strong> To change what happens at the end of a print statement. Default is a new line.</p>
<p><strong>Example:</strong><br>
<code>
print("Hello", end=" ")<br>
print("World")
</code></p>

<hr>

<h3>6. Printing Variables</h3>
<p><strong>Purpose:</strong> To display the values stored inside variables.</p>
<p><strong>Example:</strong><br>
<code>
name = "C"<br>
print(name)
</code></p>

<hr>

<h3>7. f-Strings</h3>
<p><strong>Purpose:</strong> To format strings easily and include variables inside text.</p>
<p><strong>Example:</strong><br>
<code>
name = "C"<br>
print(f"My name is {name}")
</code></p>

<hr>

<h3>8. Escape Characters</h3>
<p><strong>Purpose:</strong> To format text with special characters like new line, tab, etc.</p>
<p><strong>Examples:</strong><br>
<code>
print("Hello\nPython")  &nbsp;&nbsp;# New line <br>
print("Hello\tPython")  &nbsp;&nbsp;# Tab space
</code></p>


<h2>Variables in Python</h2>

<p>
A <b>variable</b> is a name that stores a value in Python. 
It works like a container that holds data such as numbers, strings, lists, etc.
</p>

<h3>📌 What is a Variable?</h3>
<div class="box">
    A variable stores information so it can be used later in the program.
    <pre>
x = 10
name = "John"
    </pre>
</div>
<h3>📌 How Do Variables Work?</h3>
<div class="box">
    When you assign a value:
    <pre>a = 5</pre>
    Python creates the value in memory and connects the name <code>a</code> to that value.
</div>

<h3>📌 Rules for Creating Variables</h3>
<div class="box">
    <ul>
        <li>Must start with a letter or underscore</li>
        <li>Cannot start with a number</li>
        <li>No spaces allowed</li>
        <li>Case sensitive (age and Age are different)</li>
    </ul>
    <pre>
    # Valid
age = 25
first_name = "John"
num1 = 100

# Invalid
1name = "John"
first name = "A"
class = 10
    </pre>
</div>

<h3>📌 Assigning Multiple Values</h3>
<div class="box">
    <pre>
a, b, c = 10, 20, 30
x = y = z = 100
    </pre>
</div>

<h3>📌 Updating Variable Values</h3>
<div class="box">
    <pre>
x = 10
x = 20   # updated value
    </pre>
    </div>

<h3>📌 Checking Data Type of Variable</h3>
<div class="box">
    <pre>
x = 50
print(type(x))     # Output: &lt;class 'int'&gt;
    </pre>
</div>

<h3>📌 Why Do We Use Variables?</h3>
<div class="box">
A variable is like a container that stores data. Instead of typing the same value repeatedly, we store it in a variable and use the variable name wherever needed.
    <ol>
        <li>Store data for reuse</li>
        <li>Improve code readability</li>
        <li>Easier to update values</li>
        <li>Support for dynamic calculations</li>
        <li>Makes programs flexible</li>
    </ol>
</div>
<h2>Data Types in Python</h2>

<h3>➡️ What is a Data Type?</h3>
<p>A data type tells Python what kind of value a variable is storing.</p>

<p>Just like we identify objects in real life (example: number, name, price, true/false), Python also identifies the type of data so it knows:</p>
<ul>
    <li>how much memory to use</li>
    <li>what operations are allowed</li>
    <li>how the value should behave in a program</li>
</ul>

<p>Example:</p>
<ul>
    <li>You can add two numbers</li>
    <li>But you cannot add a number and a string → Python will give an error</li>
</ul>
<p>This is because their data types are different.</p>

<h3>➡️ How Do Data Types Work in Python?</h3>
<p>Python automatically detects the data type when you assign a value.</p>
<pre><code>
x = 10        # int
y = 3.14      # float
name = "John" # string
active = True # boolean
</code></pre>

<p>Python checks the value and assigns the correct data type.  
You can also check the type using:</p>
<pre><code>print(type(x))</code></pre>

<p>Output:</p>
<pre><code>&lt;class 'int'&gt;</code></pre>

<h3>➡️ How Many Data Types Are There in Python?</h3>
<p>Python has several built-in data types. They are grouped into categories:</p>

<h4>📁 1. Numeric Types</h4>
<table border="1" cellpadding="5" cellspacing="0">
    <tr>
        <th>Type</th>
        <th>Example</th>
        <th>Meaning</th>
    </tr>
    <tr>
        <td>int</td>
        <td>10</td>
        <td>Whole numbers</td>
    </tr>
    <tr>
        <td>float</td>
        <td>3.14</td>
        <td>Decimal numbers</td>
    </tr>
    <tr>
        <td>complex</td>
        <td>5 + 3j</td>
        <td>Real + imaginary part</td>
    </tr>
</table>

<h4>📁 2. String Type</h4>
<table border="1" cellpadding="5" cellspacing="0">
    <tr>
        <th>Type</th>
        <th>Example</th>
        <th>Meaning</th>
    </tr>
    <tr>
        <td>str</td>
        <td>"Hello"</td>
        <td>Text values</td>
    </tr>
</table>

<h4>📁 3. Boolean Type</h4>
<table border="1" cellpadding="5" cellspacing="0">
    <tr>
        <th>Type</th>
        <th>Example</th>
        <th>Meaning</th>
    </tr>
    <tr>
        <td>bool</td>
        <td>True / False</td>
        <td>Represents truth values</td>
    </tr>
</table>
<h4>Boolean in Python</h4>

<p>Python treats values as <strong>True</strong> or <strong>False</strong> in a Boolean context:</p>

<ul>
  <li><strong>False values:</strong> 0, 0.0, "" (empty string), [], {}, set(), None</li>
  <li><strong>Everything else is True</strong></li>
</ul>

<p>Examples:</p>

<pre><code>print(bool(0))      # False
print(bool(42))     # True
print(bool(""))     # False
print(bool("Hi"))   # True
print(bool([]))     # False
</code></pre>


<h4>📁 4. Sequence Types</h4>
<table border="1" cellpadding="5" cellspacing="0">
    <tr>
        <th>Type</th>
        <th>Example</th>
        <th>Meaning</th>
    </tr>
    <tr>
        <td>list</td>
        <td>[1, 2, 3]</td>
        <td>Ordered & changeable</td>
    </tr>
    <tr>
        <td>tuple</td>
        <td>(1, 2, 3)</td>
        <td>Ordered & unchangeable</td>
    </tr>
    <tr>
        <td>range</td>
        <td>range(5)</td>
        <td>Sequence of numbers</td>
    </tr>
</table>

<h4>📁 5. Mapping Type</h4>
<table border="1" cellpadding="5" cellspacing="0">
    <tr>
        <th>Type</th>
        <th>Example</th>
        <th>Meaning</th>
    </tr>
    <tr>
        <td>dict</td>
        <td>{"name": "John"}</td>
        <td>Key-value pairs</td>
    </tr>
</table>

<h4>📁 6. Set Types</h4>
<table border="1" cellpadding="5" cellspacing="0">
    <tr>
        <th>Type</th>
        <th>Example</th>
        <th>Meaning</th>
    </tr>
    <tr>
        <td>set</td>
        <td>{1, 2, 3}</td>
        <td>Unordered, unique values</td>
    </tr>
    <tr>
        <td>frozenset</td>
        <td>frozenset({1, 2, 3})</td>
        <td>Immutable set</td>
    </tr>
</table>

<h2>Type Conversion in Python</h2>

<p>Type conversion (or typecasting) is the process of converting a variable from one data type to another.</p>

<h3>1️⃣ Implicit Type Conversion</h3>
<p>Python automatically converts one data type to another without user input when needed.</p>

<p><strong>Example:</strong></p>

<pre>
<code>x = 5       # int
y = 2.5     # float

z = x + y   # int is converted to float automatically
print(z)    # 7.5
print(type(z))  # &lt;class 'float'&gt;
</code>
</pre>

<p>Python converts “lower” types to “higher” types to prevent data loss: <code>int → float → complex</code>.</p>

<h3>2️⃣ Explicit Type Conversion</h3>
<p>You manually convert one type to another using built-in functions: <code>int()</code>, <code>float()</code>, <code>str()</code>, <code>bool()</code>, <code>list()</code>, <code>tuple()</code>, <code>set()</code>.</p>

<p><strong>Examples:</strong></p>

<pre>
<code># Numbers
x = int(3.9)     # 3
y = float(5)     # 5.0

# Strings
z = str(100)     # '100'

# Boolean
a = bool(0)      # False
b = bool(42)     # True

# Collections
t = (1, 2, 3)
l = list(t)      # [1, 2, 3]

l = [4, 5, 6]
t = tuple(l)     # (4, 5, 6)

l = [1, 2, 2, 3]
s = set(l)       # {1, 2, 3}
</code>
</pre>

<h2>Python Operators</h2>
<p> Operators are special symbols in Python used to perform operations on variables and values. Python has several types of operators:</p>

<h3>1️⃣ Arithmetic Operators</h3>
<p><strong>Purpose:</strong> Perform mathematical operations like addition, subtraction, multiplication, etc.</p>
<table>
  <tr><th>Operator</th><th>Purpose</th><th>Example</th><th>Result</th></tr>
  <tr><td>+</td><td>Add two numbers</td><td>5 + 3</td><td>8</td></tr>
  <tr><td>-</td><td>Subtract one number from another</td><td>5 - 3</td><td>2</td></tr>
  <tr><td>*</td><td>Multiply numbers</td><td>5 * 3</td><td>15</td></tr>
  <tr><td>/</td><td>Divide numbers</td><td>5 / 2</td><td>2.5</td></tr>
  <tr><td>//</td><td>Floor division (quotient without remainder)</td><td>5 // 2</td><td>2</td></tr>
  <tr><td>%</td><td>Find remainder</td><td>5 % 2</td><td>1</td></tr>
  <tr><td>**</td><td>Exponentiation (power)</td><td>5 ** 2</td><td>25</td></tr>
</table>

<h3>2️⃣ Assignment Operators</h3>
<p><strong>Purpose:</strong> Assign or update values of variables.</p>
<table>
  <tr><th>Operator</th><th>Purpose</th><th>Example</th></tr>
  <tr><td>=</td><td>Assign value to a variable</td><td>x = 5</td></tr>
  <tr><td>+=</td><td>Add and assign</td><td>x += 3  (x = x + 3)</td></tr>
  <tr><td>-=</td><td>Subtract and assign</td><td>x -= 3  (x = x - 3)</td></tr>
  <tr><td>*=</td><td>Multiply and assign</td><td>x *= 3  (x = x * 3)</td></tr>
  <tr><td>/=</td><td>Divide and assign</td><td>x /= 3  (x = x / 3)</td></tr>
  <tr><td>//=</td><td>Floor divide and assign</td><td>x //= 3</td></tr>
  <tr><td>%=</td><td>Modulus and assign</td><td>x %= 3</td></tr>
  <tr><td>**=</td><td>Exponentiate and assign</td><td>x **= 3</td></tr>
</table>

<h3>3️⃣ Comparison Operators</h3>
<p><strong>Purpose:</strong> Compare values and return <code>True</code> or <code>False</code>.</p>
<table>
  <tr><th>Operator</th><th>Purpose</th><th>Example</th><th>Result</th></tr>
  <tr><td>==</td><td>Check equality</td><td>5 == 3</td><td>False</td></tr>
  <tr><td>!=</td><td>Check inequality</td><td>5 != 3</td><td>True</td></tr>
  <tr><td>></td><td>Greater than</td><td>5 > 3</td><td>True</td></tr>
  <tr><td><</td><td>Less than</td><td>5 < 3</td><td>False</td></tr>
  <tr><td>>=</td><td>Greater than or equal</td><td>5 >= 5</td><td>True</td></tr>
  <tr><td><=</td><td>Less than or equal</td><td>5 <= 3</td><td>False</td></tr>
</table>

<h3>4️⃣ Logical Operators</h3>
<p><strong>Purpose:</strong> Combine multiple conditions and return Boolean results.</p>
<table>
  <tr><th>Operator</th><th>Purpose</th><th>Example</th><th>Result</th></tr>
  <tr><td>and</td><td>True if both conditions are True</td><td>True and False</td><td>False</td></tr>
  <tr><td>or</td><td>True if any condition is True</td><td>True or False</td><td>True</td></tr>
  <tr><td>not</td><td>Reverse Boolean value</td><td>not True</td><td>False</td></tr>
</table>

<h3>5️⃣ Identity Operators</h3>
<p><strong>Purpose:</strong> Check if two variables refer to the same object in memory.</p>
<table>
  <tr><th>Operator</th><th>Purpose</th><th>Example</th></tr>
  <tr><td>is</td><td>True if same object</td><td>x is y</td></tr>
  <tr><td>is not</td><td>True if different object</td><td>x is not y</td></tr>
</table>

<h3>6️⃣ Membership Operators</h3>
<p><strong>Purpose:</strong> Test whether a value exists in a sequence (like list, string, tuple).</p>
<table>
  <tr><th>Operator</th><th>Purpose</th><th>Example</th></tr>
  <tr><td>in</td><td>True if value exists</td><td>'a' in 'apple'</td></tr>
  <tr><td>not in</td><td>True if value does not exist</td><td>'b' not in 'apple'</td></tr>
</table>


<h2>Bitwise Operators in Python</h2>
<p>Bitwise operators work on the <strong>binary representation</strong> of integers. They are useful for low-level programming, optimization, and certain algorithmic tasks.</p>

<h3>1️⃣ Bitwise AND (&)</h3>
<p><strong>Purpose:</strong> Result is 1 if both bits are 1, otherwise 0.</p>
<p><strong>Example:</strong> 5 & 3</p>
<p>Binary: 5 → 101, 3 → 011 → Result: 001 → 1</p>

<h3>2️⃣ Bitwise OR (|)</h3>
<p><strong>Purpose:</strong> Result is 1 if at least one bit is 1.</p>
<p><strong>Example:</strong> 5 | 3</p>
<p>Binary: 5 → 101, 3 → 011 → Result: 111 → 7</p>

<h3>3️⃣ Bitwise XOR (^)</h3>
<p><strong>Purpose:</strong> Result is 1 if bits are different, 0 if they are the same.</p>
<p><strong>Example:</strong> 5 ^ 3</p>
<p>Binary: 5 → 101, 3 → 011 → Result: 110 → 6</p>

<h3>4️⃣ Bitwise NOT (~)</h3>
<p><strong>Purpose:</strong> Flips all bits (0 → 1, 1 → 0). In Python, result is -n-1 because of 2's complement.</p>
<p><strong>Example:</strong> ~5</p>
<p>Binary: 5 → 00000101 → Result: 11111010 → -6</p>

<h3>5️⃣ Left Shift (<<)</h3>
<p><strong>Purpose:</strong> Shifts bits to the left, adding 0 on the right. Equivalent to multiplying by 2ⁿ.</p>
<p><strong>Example:</strong> 5 << 1</p>
<p>Binary: 5 → 101 → Shift left → 1010 → Result: 10</p>

<h3>6️⃣ Right Shift (>>)</h3>
<p><strong>Purpose:</strong> Shifts bits to the right. Equivalent to integer division by 2ⁿ.</p>
<p><strong>Example:</strong> 5 >> 1</p>
<p>Binary: 5 → 101 → Shift right → 10 → Result: 2</p>

<h2>Python Libraries</h2>

<p>A <strong>library</strong> is a collection of modules, and a <strong>module</strong> is a file containing Python definitions and functions. Libraries help you perform specific tasks without writing code from scratch.</p>

<h3>Common Python Libraries</h3>
<ul>
  <li><strong>math</strong> – Mathematical operations  
    <br>Example: <code>import math</code>  
    <code>math.sqrt(16) → 4.0</code>
  </li>
  <li><strong>random</strong> – Random number generation  
    <br>Example: <code>import random</code>  
    <code>random.randint(1,10) → 5</code>
  </li>
  <li><strong>datetime</strong> – Date & time manipulation  
    <br>Example: <code>import datetime</code>  
    <code>datetime.datetime.now()</code>
  </li>
  <li><strong>os</strong> – Operating system operations  
    <br>Example: <code>import os</code>  
    <code>os.getcwd() → current directory</code>
  </li>
  <li><strong>sys</strong> – System-specific parameters  
    <br>Example: <code>import sys</code>  
    <code>sys.version → Python version</code>
  </li>
  <li><strong>json</strong> – JSON handling  
    <br>Example: <code>import json</code>  
    <code>json.loads('{"a":1}') → {'a':1}</code>
  </li>
  <li><strong>re</strong> – Regular expressions  
    <br>Example: <code>import re</code>  
    <code>re.findall(r'\d+', 'abc123') → ['123']</code>
  </li>
  <li><strong>statistics</strong> – Statistical calculations  
    <br>Example: <code>import statistics</code>  
    <code>statistics.mean([1,2,3]) → 2</code>
  </li>
</ul>

<h3>Example: Using the math Library</h3>
<pre><code>import math

print(math.sqrt(25))     # Square root → 5.0
print(math.factorial(5)) # Factorial → 120
print(math.pi)           # Pi value → 3.141592653589793
</code></pre>

<h2>Built-in Functions in Python</h2>

<p>Built-in functions are functions available by default in Python. You don’t need to import any library to use them.</p>

<h3>Common Built-in Functions</h3>
<ul>
  <li><strong>print()</strong> – Print output  
    <br>Example: <code>print("Hello") → Hello</code>
  </li>
  <li><strong>len()</strong> – Length of object  
    <br>Example: <code>len([1,2,3]) → 3</code>
  </li>
  <li><strong>type()</strong> – Type of object  
    <br>Example: <code>type(5) → &lt;class 'int'&gt;</code>
  </li>
  <li><strong>int(), float(), str()</strong> – Type conversion  
    <br>Example: <code>int("5") → 5</code>
  </li>
  <li><strong>sum()</strong> – Sum of iterable  
    <br>Example: <code>sum([1,2,3]) → 6</code>
  </li>
  <li><strong>max(), min()</strong> – Maximum & minimum value  
    <br>Example: <code>max([1,2,3]) → 3, min([1,2,3]) → 1</code>
  </li>
  <li><strong>sorted()</strong> – Sorted list  
    <br>Example: <code>sorted([3,1,2]) → [1,2,3]</code>
  </li>
  <li><strong>abs()</strong> – Absolute value  
    <br>Example: <code>abs(-5) → 5</code>
  </li>
  <li><strong>round()</strong> – Round number  
    <br>Example: <code>round(3.14159,2) → 3.14</code>
  </li>
  <li><strong>input()</strong> – User input  
    <br>Example: <code>input("Enter: ")</code>
  </li>
</ul>

<h3>Example: Built-in Functions</h3>
<pre><code>numbers = [10, 20, 30]

print(len(numbers))       # 3
print(sum(numbers))       # 60
print(max(numbers))       # 30
print(min(numbers))       # 10
print(sorted(numbers))    # [10, 20, 30]
print(abs(-50))           # 50
</code></pre>

<h1>📝 Strings in Python</h1>

<p>A string is a sequence of characters enclosed in:</p>

<ul>
    <li>Single quotes → <code>'hello'</code></li>
    <li>Double quotes → <code>"hello"</code></li>
    <li>Triple quotes → <code>'''hello'''</code> or <code>"""hello"""</code> (for multi-line strings)</li>
</ul>

<p>Strings are used to store text data like names, messages, etc.</p>

<hr>

<h2>✔️ Creating Strings</h2>

<pre><code>s1 = 'Hello'
s2 = "Python"
s3 = '''This is
a multiline
string'''
</code></pre>

<hr>

<h2>✔️ Accessing Characters (Indexing)</h2>

<p>Each character has a position (index).</p>

<pre><code>name = "Chaithu"
print(name[0])   # C
print(name[3])   # i
print(name[-1])  # u  (negative index → from last)
</code></pre>

<hr>

<h2>✔️ Slicing Strings</h2>

<pre><code>text = "Python"
print(text[0:3])   # Pyt
print(text[2:])    # thon
print(text[:4])    # Pyth
print(text[-3:])   # hon
</code></pre>
<h2>🧵 Are Strings Mutable or Immutable in Python?</h2>

<h3>✔️ Strings are Immutable</h3>

<p>Once a string is created, you cannot change (modify) it directly.</p>

<hr>

<h3>🔹 Example</h3>

<pre><code>name = "Chaithu"
name = "J" + name[1:]
print(name)
</code></pre>

<hr>

<h3>🔍 Step-by-step Explanation</h3>

<ul>
    <li>Original string → <code>"Chaithu"</code></li>
    <li><code>name[1:]</code> means substring from index 1 onward → <code>"haithu"</code></li>
    <li><code>"J" + "haithu"</code> → <code>"Jhaithu"</code></li>
</ul>

<p><b>✅ Output:</b></p>

<pre><code>Jhaithu
</code></pre>

<hr>

<h3>❌ Immutable Example (Error)</h3>

<pre><code>name = "Chaithu"
name[0] = "J"     # ❌ Error: strings are immutable
</code></pre>

<p>This gives:</p>

<pre><code>TypeError: 'str' object does not support item assignment
</code></pre>

<hr>

<h3>✔️ What Actually Happens?</h3>

<p>If you try to “change” a string, Python creates a new string instead of modifying the old one.</p>

<pre><code>name = "Chaithu"
name = "J" + name[1:]
print(name)    # Jhaithu
</code></pre>

<hr>
<h1>🔥 Important String Methods in Python</h1>

<h3>📌 1. upper()</h3>
<p><b>Purpose:</b> Converts all characters to uppercase.</p>
<pre><code>"hello".upper()
# Output: "HELLO"
</code></pre>

<h3>📌 2. lower()</h3>
<p><b>Purpose:</b> Converts all characters to lowercase.</p>
<pre><code>"HELLO".lower()
# Output: "hello"
</code></pre>

<h3>📌 3. title()</h3>
<p><b>Purpose:</b> Converts first letter of each word to uppercase.</p>
<pre><code>"python programming".title()
# Output: "Python Programming"
</code></pre>

<h3>📌 4. capitalize()</h3>
<p><b>Purpose:</b> Converts only the first character to uppercase.</p>
<pre><code>"hello world".capitalize()
# Output: "Hello world"
</code></pre>

<h3>📌 5. strip()</h3>
<p><b>Purpose:</b> Removes spaces from both sides.</p>
<pre><code>"  hi  ".strip()
# Output: "hi"
</code></pre>

<h3>📌 6. lstrip() / rstrip()</h3>
<p><b>Purpose:</b> Removes spaces from left/right side.</p>
<pre><code>"  hi".lstrip()     # "hi"
"hi  ".rstrip()     # "hi"
</code></pre>

<h3>📌 7. replace(old, new)</h3>
<p><b>Purpose:</b> Replace part of a string.</p>
<pre><code>"banana".replace("a", "o")
# Output: "bonono"
</code></pre>

<h3>📌 8. split(separator)</h3>
<p><b>Purpose:</b> Converts string → list.</p>
<pre><code>"a,b,c".split(",")
# Output: ['a', 'b', 'c']
</code></pre>

<h3>📌 9. join(iterable)</h3>
<p><b>Purpose:</b> Converts list → string.</p>
<pre><code>",".join(['a', 'b', 'c'])
# Output: "a,b,c"
</code></pre>

<h3>📌 10. startswith()</h3>
<p><b>Purpose:</b> Checks if string starts with given substring.</p>
<pre><code>"python".startswith("py")
# Output: True
</code></pre>

<h3>📌 11. endswith()</h3>
<p><b>Purpose:</b> Checks if string ends with given substring.</p>
<pre><code>"python".endswith("on")
# Output: True
</code></pre>

<h3>📌 12. find()</h3>
<p><b>Purpose:</b> Returns index of first occurrence; returns -1 if not found.</p>
<pre><code>"hello".find("l")
# Output: 2
</code></pre>

<h3>📌 13. index()</h3>
<p><b>Purpose:</b> Same as find(), but gives error if not fou

   





</body>     
<hr>
<h2>👨‍💻 Author</h2>

<p><strong>Chaithanya Gollapalli</strong><br>
Maintains this repository as part of continuous Python development practice.<br>
📧 <strong>Email:</strong> chaithanyagollapalli08@gmail.com
</p>

