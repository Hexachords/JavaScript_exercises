Fundamental notes from the FreeCodeCampJS course

Comments in JS

```javascript
// inline comments

/*
Multi
-line
comments
*/
```

Declaring variables in JS

"_JavaScript provides eight different data types which are `undefined`, `null`, `boolean`, `string`, `symbol`, `bigint`, `number`, and `object`._"


```javascript
var example;
var catdog21;
var hiworld;
```

Storing values in the Variables 

```javascript
var num;
num = 66;

```

Declare a Read-Only Variable with the const Keyword
Assigning the Value of One Variable to Another

```javascript
var num1;
num1 = 6;
var num2;
num2 = num1;

```

Initializing Variables with the Assignment Operator
```javascript
var num = 6;
```

Declare String Variables
```javascript
var randomString = "blehbelsb";
```

Explore Differences Between the var and let Keywords
"_let allows you to declare variables that are limited to the scope of a block statement, or expression on which it is used_"

```javascript
let newVar = 89;
```

Declare a Read-Only Variable with the const Keyword
_`const` has all the awesome features that `let` has, with the added bonus that variables declared using `const` are read-only. They are a constant value, which means that once a variable is assigned with `const`, it cannot be reassigned_

_Use `let` when you want the variable to change, and `const` when you want the variable to remain constant._

```javascript
const FCC = "freeCodeCamp"; 

let fact = "is cool!"; 
fact = "is awesome!";

console.log(FCC, fact); 


```

```javascript 
// output:  freeCodeCamp is awesome! 
	```

Add Two Numbers with JavaScript
```javascript
var addNums = 6+6; ```

Subtract One Number from Another with JavaScript
```javascript
const subNums = 17 - 9;```

Multiply Two Numbers with JavaScript
```javascript
var product = 8 * 9; ```

Divide One Number by Another with JavaScript

```javascript 
const divideNum = 66 / 11;  ```

Increment a Number with JavaScript
```javascript
i++ ;
// or 
i = i +1;
```

Decrement a Number with JavaScript
```javascript
i--;
// or 
i = i - 1;
```

Finding a Remainder in JavaScript
```javascript
const remainder = 11 % 3;
```

Compound Assignment With Augmented Addition
```javascript
let a = 3;

let b = 17;

let c = 12;

  
a += 12;

b += 9;

c += 7;
```

Compound Assignment With Augmented Subtraction
```javascript
let a = 11;

let b = 9;

let c = 3;

  

// Only change code below this line

a -= 6;

b -= 15;

c -= 1;


```
Addition +=
Subtraction -=
Multiplication *=
Division /=

Escaping Literal Quotes in Strings
```javascript
const sampleStr = "Alan said, \"Peter is learning JavaScript\".";
```

Escape Sequences in Strings
![[Pasted image 20220224154437.png]]

Printing to Console
```javascript
console.log('Hello World');

```


```javascript
parseInt();  //
parseFloat();//
String();//
```