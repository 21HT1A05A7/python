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

<h2>🎯 Purpose</h2>
<ul>
  <li>Learn Python step-by-step</li>
  <li>Practice core concepts</li>
  <li>Prepare for interviews</li>
</ul>

<h2>🤝 Contributions</h2>
<p>Contributions are welcome. Feel free to fork and submit pull requests.</p>
