# javascriptWH

### Primitive data types

->A primitive (primitive value, primitive data type) is data that is not an object and has no methods.

+ Boolean:
    - The boolean data type can only have two values: __true__ or __false__
___
+ Number:
    - The numeric data type handles numers like __0.75__ for exaple
___    
+ String:
    - The string data type consists of letters and other charakters like __Hi, Sarah!__ for example.
___    
+ Null:
    - Null has one value: null. It is explicitly nothing.
___
+ Undefined:
    - A variable that has no value is undefined.
___    
+ Symbol:
    - Symbols are new in ES6. A Symbol is an immutable primitive value that is unique. 
___

### Variables

**Description:**
Variables can store the bits of information your script needs to temporarily store.

**Example:**
1. You need to declare your variable before you can use it. 
This involves creating the variable and giving it a name.
``` js
var quantity;
```
2. After you've declared the variable you can assign a value to the variable.
``` js
quantity = 3;
```
### Operators

+ Operators allow programmers to create a single value from one or more values.
+ There are different operators:
    - Assignment operators
    - Arithmetic operators
    - String operators
    - Comparison operators
    - and logical operators
    
##### Assignment Operators
-> assigning a value to a variable.

|  Type  | Example | Result |
| ------ | -------- | ---------|
|    =   | x = y | x = y  |
|   +=   | x += y | x = x + y |
|   -=   | x -= y | x = x - y |
|   *=   | x *= y | x = x * y |
|   /=   | x /= y | x = x / y |
|   %=   | x %= y | x = x % y |

Example:
``` js
color = 'blue';
```

##### Arithmetic Operators
-> mathematical operators, which you can use with numbers.

|  Type  | Description | Example | Result |
| ------ | ----------- | ------- | ----- |
|    +   | adds one value to another | 10 + 5 | 15 |
|    -   | subtracts one value from another | 10 - 5 | 5 |
|    *   | multiplies two values | 10 * 5 | 50 |
|    /   | divides two values | 10 / 5 | 2 |
|    %   | divides two values and returns the remainder | 10 % 3 | 1 |
|   ++   | adds one to the currrent number | i = 10; i++; | 11 |
|   --   | subtracts one from the current number | i = 10; i--; | 9 |

##### String Operators
There is just one string operator: the __+__ symbol.
It is used to join the strings on either side of it.

Example:
``` js
var firstName = 'Sarah ';
var lastName = 'Loos ';
var fulName = firstName + lastName;
```
##### Comparison Operators
-> Can return single values of true or false.

|  Type  | Description |
| ------ | ----------- |
|   ==   | is equal to |
|   !=   | is not equal to |
|  ===   | strict equal to |
|  !==   |  strict not equal to|
|   >   | greater than |
|   <   | less than |
|   >=   | greater than or equal to |
|   <=   | less than or equal to |

Example:
``` js
(score >= pass)
```

##### Logical Operators
-> Allow you to compare th results of more than one comparison operator.

|  Type  | Description |
| ------ | ----------- |
|    &&   | logical and |
|   '||'  | logical or|
|   !   | logical not |

### Outputs
JavaScript can "display" data in different ways:

Writing into an HTML element, using __innerHTML__.
Writing into the HTML output using __document.write()__.
Writing into an alert box, using __window.alert()__.
Writing into the browser console, using __console.log()__.

##### innerHTML
To access an HTML element, JavaScript can use the __document.getElementById(id)__ method.

Example:
```js
<p id="try"></p>

<script>
document.getElementById("try").innerHTML = 2 + 8;
</script>
```
##### document.write()
For testing purposes, it is convenient to use __document.write()__.

Example:
```js
<script>
document.write(2 + 8);
</script>
```
##### window.alert()
You can use an alert box to display data.

Example:
```js
<script>
window.alert(2 + 8);
</script>
```
##### console.log()
For debugging purposes, you can use the __console.log()__ method to display data.

Example:
```js
<script>
console.log(2 + 8);
</script>
```

### Conditional Statements

|  Type  | Description |
| ------ | ----------- |
| if | Use if to specify a block of code to be executed, if a specified condition is true |
| else | Use else to specify a block of code to be executed, if the same condition is false  |
| else if | Use else if to specify a new condition to test, if the first condition is false  |
| switch | Use switch to specify many alternative blocks of code to be executed  |

Example:
``` js
if (hour < 18) {
greeting = "Good day";
}
```


### Loops

|  Type  | Description |
| ------ | ----------- |
| for | used to run a code a specific number of times |
| while | used to run a code if you don't know how many times the code should run  |
| do while | will always run the statements inside the curly braces at least once, even if the condition evaluates to false |

Example:
``` js
for (var i = 0; i < 10; i++) {document.write(i);
}
```

## Commentar
```
How to publish your .md?
1) git clone https://github.com/sloos123/javascriptWH.git
2) cd /Users/Sarah/Documents/Repos/javascriptWH
3) git add README.md
4) git commit -m "initial commit"
5) git status
6) git push
```

```
Index/References:
- https://www.w3schools.com
- https://developer.mozilla.org/en-US/docs/Web/JavaScript/Data_structures
- "Javascript & JQuery" (interactive front-end web development) by Jon Duckett
```