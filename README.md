<h1>🐍 Python Basics & Core Concepts</h1>

<p>
This repository covers <b>Python fundamental concepts</b> with simple explanations and examples.
It is useful for beginners, students, and interview preparation.
</p>

<hr>

<h2>📌 Topics Covered</h2>

<h3>1. Data Types</h3>
<p>Python supports different built-in data types such as:</p>
<ul>
  <li>int – Integer values</li>
  <li>float – Decimal numbers</li>
  <li>str – Text data</li>
  <li>bool – True / False</li>
  <li>NoneType</li>
</ul>

<pre><code>a = 10
b = 2.5
name = "Python"
is_active = True
</code></pre>

<h3>2. Variables</h3>
<p>Variables are used to store data values.</p>

<pre><code>x = 5
y = "Hello"
</code></pre>

<h3>3. Operators</h3>
<ul>
  <li>Arithmetic Operators (+, -, *, /, %)</li>
  <li>Comparison Operators (==, !=, &gt;, &lt;, &gt;=, &lt;=)</li>
  <li>Logical Operators (and, or, not)</li>
  <li>Assignment Operators (=, +=, -=)</li>
</ul>

<h3>4. Type Conversions</h3>
<p>Convert one data type into another.</p>

<pre><code>a = "10"
b = int(a)
</code></pre>

<h3>5. Print Statement</h3>

<pre><code>print("Welcome to Python")
</code></pre>

<h3>6. Strings</h3>

<pre><code>name = "Python"
print(name.upper())
</code></pre>

<h3>7. List</h3>
<p>Ordered and mutable collection.</p>

<pre><code>numbers = [1, 2, 3, 4]
</code></pre>

<h3>8. Tuple</h3>
<p>Ordered and immutable collection.</p>

<pre><code>t = (10, 20, 30)
</code></pre>

<h3>9. Set</h3>
<p>Unordered collection of unique elements.</p>

<pre><code>s = {1, 2, 3}
</code></pre>

<h3>10. Dictionary</h3>
<p>Stores data in key-value pairs.</p>

<pre><code>student = {"name": "Ram", "age": 20}
</code></pre>

<h3>11. Conditional Statements</h3>

<pre><code>if a &gt; b:
    print("A is greater")
else:
    print("B is greater")
</code></pre>

<h3>12. Control Statements</h3>
<ul>
  <li>break</li>
  <li>continue</li>
  <li>pass</li>
</ul>

<h3>13. Loops</h3>

<pre><code>for i in range(5):
    print(i)
</code></pre>

<pre><code>while x &lt; 5:
    x += 1
</code></pre>

<h3>14. Functions</h3>

<pre><code>def add(a, b):
    return a + b
</code></pre>

<h3>15. Lambda Function</h3>

<pre><code>square = lambda x: x * x
</code></pre>

<h3>16. map(), filter(), reduce()</h3>

<pre><code># map
nums = [1, 2, 3]
result = list(map(lambda x: x * 2, nums))

# filter
even = list(filter(lambda x: x % 2 == 0, nums))

# reduce
from functools import reduce
total = reduce(lambda x, y: x + y, nums)
</code></pre>

<hr>

<h2>📘 Python Advanced Topics</h2>

<h3>🔹 Comprehensions</h3>
<p>
Comprehensions provide a concise way to create collections like lists and dictionaries.
They make the code more readable and efficient.
</p>

<h4>• List Comprehensions</h4>
<p>
List comprehensions are used to create new lists from existing iterables in a single line.
They can include conditions and expressions.
</p>

<h4>• Dictionary Comprehensions</h4>
<p>
Dictionary comprehensions allow creating dictionaries dynamically using key-value pairs
derived from iterables.
</p>

<hr>

<h3>📂 File Handling</h3>
<p>
File handling in Python is used to create, read, write, and append data to files.
Python provides built-in functions to handle files easily.
</p>

<h4>• Write Mode (<code>w</code>)</h4>
<p>
Opens a file for writing. If the file exists, it overwrites the content.
If the file does not exist, it creates a new file.
</p>

<h4>• Read Mode (<code>r</code>)</h4>
<p>
Opens a file for reading. This is the default mode.
It raises an error if the file does not exist.
</p>

<h4>• Append Mode (<code>a</code>)</h4>
<p>
Opens a file for appending data at the end of the file
without deleting existing content.
</p>

<hr>

<h3>⚠️ Exception Handling</h3>
<p>
Exception handling is used to handle runtime errors gracefully.
It prevents the program from crashing and allows custom error messages.
</p>

<hr>

<h3>🏗️ Object-Oriented Programming (OOPS)</h3>
<p>
OOPS is a programming paradigm based on objects and classes.
It helps in code reusability, modularity, and maintainability.
</p>

<h4>• Class & Object</h4>
<p>
A class is a blueprint for creating objects.
An object is an instance of a class.
</p>

<h4>• <code>self</code> Keyword</h4>
<p>
The <code>self</code> keyword refers to the current object.
It is used to access variables and methods of a class.
</p>

<h4>• Constructor</h4>
<p>
A constructor is a special method that is automatically executed
when an object is created. It is used to initialize object data.
</p>

<hr>

<p><b>✅ This repository covers Python concepts from basics to advanced topics with examples.</b></p>


<h2>🎯 Purpose</h2>
<ul>
  <li>Learn Python step-by-step</li>
  <li>Practice core concepts</li>
  <li>Prepare for interviews</li>
</ul>

<h2>🤝 Contributions</h2>
<p>Contributions are welcome. Feel free to fork and submit pull requests.</p>
