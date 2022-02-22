Fundamental notes from the FreeCodeCampJS course

Comments in JS

```
// inline comments

/*
Multi
-line
comments
*/
```

Declaring variables in JS

"_JavaScript provides eight different data types which are `undefined`, `null`, `boolean`, `string`, `symbol`, `bigint`, `number`, and `object`._"


```
var example;
var catdog21;
var hiworld;
```

Storing values in the Variables 

```
var num;
num = 66;

```

Declare a Read-Only Variable with the const Keyword
Assigning the Value of One Variable to Another

```
var num1;
num1 = 6;
var num2;
num2 = num1;

```

Initializing Variables with the Assignment Operator
```
var num = 6;
```

Declare String Variables
```
var randomString = "blehbelsb";
```

Explore Differences Between the var and let Keywords
"_let allows you to declare variables that are limited to the scope of a block statement, or expression on which it is used_"

```
let newVar = 89;
```

Declare a Read-Only Variable with the const Keyword
_`const` has all the awesome features that `let` has, with the added bonus that variables declared using `const` are read-only. They are a constant value, which means that once a variable is assigned with `const`, it cannot be reassigned_

_Use `let` when you want the variable to change, and `const` when you want the variable to remain constant._

```
const FCC = "freeCodeCamp"; 

let fact = "is cool!"; 
fact = "is awesome!";

console.log(FCC, fact); 


```

``` output:  freeCodeCamp is awesome!```

Add Two Numbers with JavaScript
``` var addNums = 6+6; ```