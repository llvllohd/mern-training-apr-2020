# mern-training-apr-2020
Thruskills MERN stack training Apr 2020

## Day  6

    1. Conditional statements
        - if, else
        - switch
        - ternery operator
    2. Looping statement
        for
        while
        do while

// block
{
    // a block of code
    var i = 20;

    ...
    ..
}

if (condition){
    // true - this block run
}


if (condition){
    // true - this block runs
}else{
    // false - this block of code will run
}

// 1-7

1 = monday
2 = tuesday
...
...

// Nested if else
var day;
if(day == 1){
    console.log('Monday is here')
}else if(day == 3){
    console.log('Wednesday')
}else if(day == 5){
    console.log('Friday')
}else{
    console.log('some other day')
}

## switch
condition
multiple cases - outcomes of the condition

var day;
switch(day){
    // expression may return number, string, boolean
    case 1:
        console.log('Monday')
        break;
    case 2:
        console.log('Tuesday')
        break;
    case 3:
        console.log('Wednesday')
        break;
    case 4:
        console.log('Thursday')
        break;
    case 5:
        console.log('Friday')
        break;
    case 6:
        console.log('Saturday')
        break;
    case 7:
         console.log('Sunday')
        break;
    default:
        console.log('Invalid day')
}   

## Loops
run some staments again and again based on certain conditions - looping

for - standard for loop
for(initializer; exit condition; final expression){
    // block of code that runs
}

while ()
// initializer
var i=0;
while(exit condition){
    // while block

    final expression
}


do{
    console.log('hi')
} while(exit condition)

break;
continue;

## Day 5
Today's agenda

    1. Operators
    2. Create a web page and include JS (client side JS)
        2.1. multiple ways to include js in a web page
        2.2. placeholder for javascript
            head
            body 
            both --- very often
        2.3. order in which javascript is loaded
            main.js
            main1.js

    Operators
    ### Ternary operator
        (experssion) ? val1 : val2;
    
    ### comma 

    ### unary

        delete
        typeof
        void

    ### Relational
        instanceof
    
    ### precedence


## Day 4
Todays agenda
    1. Arrays
    2. Operators
    

    ### Array
    A collection of elements. Elements can be of any type

    var numbers = [1,1,2,3,5,8];

    ### operators

    operands
    operators

    var x;

    var y = 20;

    y -> operand
    = -> operator (assignment operator)

    types of operators
        - based on the number of operands they work with
         unary operators
         binary
         ternary
    
    precedence of operators

    1 + 3 + 3 * 4 / 3 = ? based on the operator precendence

    Assignment operators
    =   

    a = a + 5; // a += 5; // -=, *=, /= 

    &   - ??
    &&  - ??

    Comparison operators
    ==      equals to
    ===     strict equal
    != 
    !== 

    Arithmetic operator
    +, -, *, /, %
    ++ increment
    -- decrement
        post increment/decrement
        pre increment/dcrement

    1. swap two number without using a third variable?
        var a = 10;
        var b = 20;
        var tmp = a; // temp or third variable
        a = b;
        b= tmp;

        // how many ways are there to solve the above problem?
        // which will the most efficient one?

    Bitwise Operators
        &   AND     if both the bits are 1 = output will be 1
        |   OR      if any bit is 1 = output will be 1
        ^   XOR     if different = output will be 1 (caret)
        ~   NOT     negation  0 to 1 and 1  tp 0    (tilde)

        a = 3 = 011
        b = 4 = 100
        ---------------
            AND 000 0
            OR  111 7
            ^   111 7
        ----------------
        ~a = 011 -> 100 = -4

        a << 1; 011 << 1; => 110 = 6
        a >> 1; 011 >> 1; => 001 = 1


    Logical operators
        AND     &&  if both the experssions return true - true
        OR      ||  if any expression returns true - true
        NOT     !   oppostive of the expression

    String concatenation
        + plus

## Day 3
Recap -
    statement
    variable declaration
        var 
        let     - es6
        const   - es6 
    variable naming rules
    best practices around naming your variables
    keywords / reserved words in JS

Data types?
    1. the data  type of a variable is determined by the value it holds
    2. you dont have to specify a data type while declaring variables

Dynamically typed language ?? 
types?? data type?

    1. primitive
        1. string
        2. number
        3. boolean

    2. composite
        1. array
        2. object

    3. special data types
        1. null
        2. undefined

String
    " " double quotes => string literal value
    ' ' single quotes => string literal value
    ` ` back ticks => 
    
    which one to use and why ?
    single quote vs double quote?
    
    Hi! I'm Manohar.

    var intro = "Hi! I'm Manohar."      // double quotes is what i will recommend
    var intro = 'Hi! I\'m Manohar.";    // or use the escape character

    var x = 'I think it\'s going to "rain" today';

    var freeText = "this is some sample text";
    
    // as a recommendation - use single quotes

    // Hindi/ Kanadda/ Tamil / chinese 


    var name = 'manohar';
    var str = `My name is ${name}`;

    toUpperCase
    toLowerCase
    indexOf
    lastIndexOf
    charAt
    trim

Number
    int
    float

    number system ?? 
    Base    Range           Name
    10      0 - 9           decial number system - this is the default number system
    8       0 - 7           octal
    16      0 - 9, a - f    hexa decimal
    2       0 - 1           binary

    // decimal is the default
    var i = 10;

    var i = 010; // octal value

    var i = 0x10; // hexadecimal

Boolean
    var x = true;
    var y = false;

    // booleans with string +     


undefined

null

Array
    an array is a collection of homogenous data types // similar
    

##Today we will learn some more git commands

- ```git branch``` 						- shows current branch and list of all local branches
- ```git checkout <branch-name>```		- switch to another branch
- ```git checkout -b <brranch-name>```	- create a new branch and switch to that
- ```git merge <branch-name>```			- merge the branch into the current branch
