# Welcome to Python Programming!

Welcome to my Python learning repository!  
This repository contains notes and examples to help you understand Python programming from basics to advanced topics.  
Here, you'll learn Python step by step, from basics to advanced concepts.

---

## 🛣️ Python Roadmap

<details>
  <summary><strong>1. Basic Python</strong></summary>
  <ul>
    <li><strong>Installation of Python</strong> – Learn what Python is and why it’s popular.</li>
    <li><strong>Introduction to Python</strong> – How to install Python on Windows, macOS, or Linux.</li>
    <li><strong>Variables</strong> – Store and manipulate data.</li>
    <li><strong>Data Types</strong> – <code>int</code>, <code>float</code>, <code>str</code>, <code>bool</code>, etc.</li>
    <li><strong>Type Conversion</strong> – Convert between different data types.</li>
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


</body>
