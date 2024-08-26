## Python Lab: Introduction to Python Programming with PyCharm

### Introduction
This lab introduces you to the PyCharm IDE and basic Python programming concepts. You will practice writing Python code using arithmetic operators, strings, and variables.

### Objectives
* Learn to use the PyCharm IDE for Python development.
* Practice Python programming with basic arithmetic operations and string manipulation.
* Understand the concept of variables and data types.
* Gain experience with version control by pushing code to GitHub.

### Requirements
* PyCharm IDE
* A GitHub account

### Procedure

#### Part 1: Setting up PyCharm
1. **Open PyCharm:** Launch the PyCharm IDE on your computer.
2. **Create a New Project:**
   * Click on "Create New Project".
   * Choose a suitable project name and location.
   * Select "Pure Python" as the project type.
   * Click "Create".
3. **Create a Python File:**
   * Right-click on the project directory in the Project Explorer.
   * Select "New" -> "Python File".
   * Name the file "lab1.py".

#### Part 2: Python Coding Exercises
**Problem 1: Arithmetic Operations**
Write Python code to calculate the following:
* The area of a circle with radius 5 (Hint $$A = \pi r^2$$).
** If you put `import math` at the top of your file, you can access a value of PI with `math.pi`
* The volume of a sphere with radius 3 (Hint $$V = \frac{4}{3}\pi r^3$$).
* The hypotenuse of a right-angled triangle with sides 3 and 4. (Hint $$a^2 + b^2 = c^2$$).
** If you put `import math` at the top of your file, you can access the square root function like so `math.sqrt(thing_i_need_sqrt_for_goes_here)`

**Problem 2: String Manipulation**
1. Create a string variable containing your full name (Hint, we'll learn more about variables next week, but for now, its just a series of characters to the left of an = operator).
2. Print the length of your name (Hint, look for the `len(string_goes_here)` function).
3. Concatenate your first name and last name with a space in between (Hint, the + operator can concatenate strings, but its not the only way!).
4. Convert your name to uppercase and lowercase (Hint, string data types have methods `upper()` and `lower()`).

**Problem 3: Variable and Data Types**
1. Create variables to store your age, height (in feet), and weight (in pounds).
2. Print the data type of each variable using the `type()` function.
3. Calculate your Body Mass Index (BMI) using the formula: $$\text{BMI} = {\frac{\text{weight(lbs)}}{\text{height(inches)}^2}*703}$$.
    * Careful, pay attention to height in inches!
5. Print your BMI.

#### Part 3: Pushing to GitHub
1. **Create a GitHub Repository:**
   * Log in to your GitHub account.
   * Create a new repository with a suitable name (e.g., "python_lab1").
2. **Configure Git in PyCharm:**
   * Open the "Git" menu in PyCharm and initialize a Git repository for your project.
   * Add your GitHub remote repository by going to "Git" -> "Manage Remotes".
3. **Commit Changes:**
   * Stage all changes in your PyCharm project.
   * Commit the changes with a descriptive message (e.g., "Initial commit").
4. **Push to GitHub:**
   * Push the committed changes to your GitHub repository using the "Push" button in PyCharm.

### Submission
Submit the link to your GitHub repository containing the `lab1.py` file to the Canvas Lab!

### Additional Notes
* Use meaningful variable names to improve code readability.
* Indentation is crucial in Python. Use consistent indentation (4 spaces is common).
* Test your code thoroughly before submitting.
