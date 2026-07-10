# JavaScript Basics (Output, Variables & User Input)

## Introduction

JavaScript is one of the most popular programming languages used to make web pages interactive. It allows websites to respond to user actions such as clicking buttons, entering data, displaying messages, validating forms, and much more.

Before learning conditions, loops, and functions, it is important to understand how JavaScript displays output, accepts user input, and stores data using variables.

In this chapter, you will learn:

- Displaying output using different methods
- Taking input from the user
- Creating and using variables
- Printing values in different ways
- Combining text and variables

---

# 1. Displaying Output

JavaScript provides several ways to display information.

## 1.1 alert()

The `alert()` function displays a popup message.

### Syntax

```javascript
alert("Message");
```

### Example

```javascript
alert("Welcome to JavaScript!");
```

### Output

```
+-------------------------+
| Welcome to JavaScript!  |
|            OK           |
+-------------------------+
```

### When to Use

- Show warning messages
- Display notifications
- Display important information

---

# 2. confirm()

The `confirm()` function displays a popup with **OK** and **Cancel** buttons.

It returns:

- `true` → User clicks **OK**
- `false` → User clicks **Cancel**

### Syntax

```javascript
confirm("Message");
```

### Example 1

```javascript
confirm("Do you want to continue?");
```

### Example 2

```javascript
var result = confirm("Do you want to continue?");

console.log(result);
```

### Possible Output

```
true
```

or

```
false
```

### Use Cases

- Delete confirmation
- Logout confirmation
- Exit confirmation

---

# 3. prompt()

The `prompt()` function is used to take input from the user.

### Syntax

```javascript
prompt("Message");
```

### Example

```javascript
var name = prompt("Enter your name");
```

If the user types

```
Rahul
```

then

```javascript
name
```

contains

```
Rahul
```

### Complete Example

```javascript
var name = prompt("Enter your name");

console.log("Hello " + name);
```

### Output

```
Hello Rahul
```

---

# 4. document.write()

The `document.write()` function writes content directly on the webpage.

### Syntax

```javascript
document.write("Text");
```

### Example

```javascript
document.write("Welcome to JavaScript");
```

### Output

```
Welcome to JavaScript
```

---

## Writing HTML using document.write()

You can also print HTML tags.

### Example

```javascript
document.write("<h1>JavaScript</h1>");
```

### Output

# JavaScript

---

### Example

```javascript
document.write("<p>This is a paragraph.</p>");
```

Output

This is a paragraph.

---

### Example

```javascript
document.write("<p>I am learning <b>JavaScript</b>.</p>");
```

Output

I am learning **JavaScript**.

---

# 5. console.log()

The `console.log()` function prints output in the browser's Developer Console.

It does **not** display anything on the webpage.

### Syntax

```javascript
console.log(value);
```

### Example

```javascript
console.log("Hello");
```

Output

```
Hello
```

---

### Example

```javascript
console.log(100);
```

Output

```
100
```

---

### Example

```javascript
console.log(true);
```

Output

```
true
```

---

### Example

```javascript
console.log(10 + 20);
```

Output

```
30
```

---

# 6. Variables

Variables are used to store data.

Think of a variable as a container that holds information.

### Syntax

```javascript
var variableName = value;
```

### Example

```javascript
var studentName = "Rahul";
```

Here,

- `var` creates a variable.
- `studentName` is the variable name.
- `"Rahul"` is the stored value.

---

# 7. Printing Variables

### Example

```javascript
var studentName = "Rahul";

console.log(studentName);
```

Output

```
Rahul
```

---

### Example

```javascript
var age = 20;

console.log(age);
```

Output

```
20
```

---

# 8. String Concatenation

Concatenation means joining two or more strings together.

JavaScript uses the `+` operator.

### Example

```javascript
var name = "Rahul";

console.log("Hello " + name);
```

Output

```
Hello Rahul
```

---

### Example

```javascript
var city = "Delhi";

console.log("I live in " + city);
```

Output

```
I live in Delhi
```

---

### Example

```javascript
var firstName = "Rahul";
var lastName = "Sharma";

console.log(firstName + " " + lastName);
```

Output

```
Rahul Sharma
```

---

# 9. Complete Program Example

```javascript
// Display alert
alert("Welcome");

// Confirmation box
var choice = confirm("Do you want to continue?");
console.log(choice);

// User input
var name = prompt("Enter your name");

// Display output
document.write("<h2>Welcome " + name + "</h2>");

// Console output
console.log("Hello " + name);
```

---


# JavaScript Basics (Output, Variables & User Input) – Practice Questions

This practice sheet is based on the following JavaScript concepts:

- `alert()`
- `confirm()`
- `prompt()`
- `document.write()`
- `console.log()`
- Variables (`var`)
- String Concatenation

---

# Practice Questions

## Question 1

Write a program that displays an alert box with the message:

> Welcome to JavaScript!

---

## Question 2

Write a program that asks the user:

> "Do you want to continue?"

Store the result in a variable and print it in the console.

---

## Question 3

Write a program that asks the user to enter their name using `prompt()` and display:

> Hello John

(where **John** is the user's input.)

---

## Question 4

Write a program that prints the following in the browser using `document.write()`:

```
Welcome to JavaScript
```

---

## Question 5

Write a program that displays the following heading using `document.write()`:

```html
<h1>Learning JavaScript</h1>
```

---

## Question 6

Write a program that prints the following paragraph using `document.write()`:

```html
<p>I am learning <b>JavaScript</b>.</p>
```

---

## Question 7

Create a variable named `studentName` and store your name in it.

Print the following message five times using `console.log()`:

```
Hello my name is Ankit
```

(Replace **Ankit** with the value stored in the variable.)

---

## Question 8

Create the following variables:

- `studentName`
- `age`

Print the following output:

```
My name is Rahul and I am 18 years old.
```

---

## Question 9

Create two variables:

```javascript
var num1 = 25;
var num2 = 15;
```

Print:

- Sum
- Difference
- Product
- Division

using `console.log()`.

---

## Question 10

Ask the user to enter their city using `prompt()`.

Print:

```
Welcome to Delhi
```

(Replace **Delhi** with the user's input.)

---

## Question 11

Ask the user for their favourite color.

Display the message using `alert()`:

```
Your favourite color is Blue.
```

---

## Question 12

Ask the user for their age.

Print:

```
You are 20 years old.
```

using `console.log()`.

---

## Question 13

Create three variables:

```javascript
var firstName;
var lastName;
var course;
```

Print the following:

```
Student: Rahul Sharma
Course: JavaScript
```

---

## Question 14

Write a program that asks the user for two numbers using `prompt()`.

Print both numbers in the console.

*(No addition required.)*

---

## Question 15

Create a variable called `collegeName`.

Print the following using `document.write()`:

```html
<h2>Welcome to ABC College</h2>
```

---

## Question 16

Write a program that prints the following in the console:

```
JavaScript is Fun!
```

10 times without using loops.

---

## Question 17

Ask the user:

```
Enter your favourite programming language
```

Print:

```
Your favourite programming language is JavaScript.
```

---

## Question 18

Create variables for:

- Name
- Age
- City

Print:

```
Name: Rahul
Age: 20
City: Delhi
```

---

## Question 19

Write a program that asks the user whether they like JavaScript using `confirm()`.

Print the returned value in the console.

---

## Question 20

Create the following variables:

```javascript
var school = "ABC Public School";
var student = "Riya";
```

Print:

```
Riya studies at ABC Public School.
```

using string concatenation.

---

# End of Practice Sheet
