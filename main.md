### Learn JavaScript in a week PDF.
### What is JavaScript?

```md
Javascript is a programming language which is used to develop dynamic web and mobile applications.By using javascript we can manipulate the DOM.(Add,Update,Delete).And also by using javascript we can perfom validations.
DOM:Document object model.
```
### What is ES6?
```md
ES6
ES6 stands for Ecma script.
```
### What is Node Js.
```md
Node js.
Node js is a runtime environament for javascript,By using nodejs we can create API's.
Node js is not a programing language not a libraary and neighter a framework.
```

### Set up development Environment.

To set up the Dev environment for the front end we need a browser.
```md
To start things off with the setup we need a browser.
It could be any browser(Chrome,edge,Arc,Mozilla Firefox...Etc...)
We need an IDE(Integrated development environment)
1.VS code
2.SublimeText.
3.Atom and a few others.
We recommend SublimeText!
```

```md
We need a HTMl file to run JavaScript code in the frontend.
To create a HTML file all you got to do is,
Open up your IDE and save the files with a .HTML extension.
Example : index.html
And then you are good to go.
```

```md
### To run a JavaScript file.
To run Javascript in it save another file with a .js extension.
Example: index.js
Same as the .html file above mentioned.
```

```md
Next you need to attach the .js file to the html file.
For this you need to open up your index.html file in the Ide(Sublime,Vscode or....anyother IDE).
As you can see the below html code there you need to type in this code.

<script src="index.js"> </script>
<script> : This is a HTML script tag.
Using this tag you will be able to attach the .Js file.
```

```html
<!DOCTYPE html>
<html>
<title> How to attach a .js file to a html file </title>
<script src="index.js> </script>
<head>

<body>

</body>

</head>

</html>

```

```.md
### To attch a css file, you need to repeat the same thing but...with
the <link> tag.
<link rel="stylesheet" href="index.css> 
Just like the HTML and Js file, you need to name the css file with a .css Extension.Yes that's how computers work!
Pretty Cool right???
Never mind.
```

```.md
So, Enough going off script..
We will start JavaScript now.
javascript is a programming language.......Blah Blah blah..
So far we know these things.
```

### Here's the main part of the JavaScript.
```.md
We can store data in memory by using these keywords.
By using these data types we store the variables.
1.var
2.let
3.const
```

```js
//Example
let mango = 100;
var apple = 200;
const banana = 300;
```

```js
//To print the values in JavaScript we need to console.log.
console.log();
//This is the syntax for printing the values in javascript.
```

### Example.
```js
let mango = 50;
console.log(mango)
//Output : 50
```
##### Get it?
```.md
(;) is optional by the way.
```

### What's Next??
### Data Types.
```.md
Data types :
There are two types of data types in JavaScript.
1.Primitive data types and non primitive....(nah)
2.Refrence data types.
```

We use primitive data types to store a single value in a memory.
We use Reference data types to store multiple values in the memory

### primitive data types.
```md
- String
- number
- Boolean
- undefined
- null
```

```.md
String data types..
A string is a collection of characteres that is stored in a memory.
By using "",'',``
We can store strings in the memory.
```

```js
//Example:
let stream1 = "netflix"; //using double quotes.
let stream2 = 'amazon'; //Using singe quotes.
let stream3  = `hulu`; //Using (``) (What ever these are) 
//Kidding, these are called backticks.
console.log(stram3)
//Outputs: hulu
```

```md
Number data types.
we can use a integers or floats using number data type.
```

```js
let num1 = 1000;
let num2 = 0.0555; //this is a float number.
console.log(num1)
//Outputs : 1000
```

```md
Boolean data type.
We can store boolean data types,
true or false using boolean data types.
```

```js
var bool1= true;
var bool2 = false;
console.log(bool1)
//Outputs: true
```

```md
Undefined.
So what is undefined?
Undefined means a variable has been declared.But the value has not been assigned.
```

```js
let var1 = ;
console.log(var1)
//outputs:undefined
```

```md
Null.
Null means an empty value.
A variable has been declared but the value contains no value.
```

```js
var value = null;
console.log(value)
//Outputs: Null
```

```md
So these are the 5 primitive data types in JavaScript.

Now let's learn about reference data types.Shall we??
```

### Reference data types.
We use reference data types to store multiple values in a memory.
```md
- Object
- Array
- Function
Es6:
- Map 
- Weak map
- Set
- Weak Set.
These are introduced in ES6.
```

```md
Object data type.
By using this data type we can store multiple values in a single memory location in the form of key and value pair. Using .(dot) operator we can access the values.
Objects are often used to model real world entities such as person,cars or anyother entities that has properities and behaviours.
```

```js
object syntax.

var object1 = {
fullname : "Aubrey drake grahm",
name : "drake",
age : 38,
dob : "24th oct 1986"
}
console.log(object1)
//outputs : The entire object1 with all the properities.
//if you want the specific value of the object, just use the . opertor.
//As we mentioned earlier.
//I want the full name of the object1.
console.log(object1.fullname)
//Outputs : Aubrey drake grahm.
```
### Easy right?

### Arrays.
```md
By using arrays we can use a collection of values in a single memory location.
It stores only values.Internally js attaches index numbers to the values in the array.By using index numbers we can access the values.
```

```js
let array1 = [1,2,3,4,5,6,7,8,9]
let array2 = ["Kendrik","drake","beyonce","jayz","hanumankind"]
let array3 = [1,"kendrik","drake",245,"legion"]
```

```md
In the above mentioned box we have declared 3 types of arrays.
1.array1 = Numbers array.
2.array2 = Names array.
3.Array3 = Mixed array.(you can actually store multiple values).
It can either be numbres, names or float numbers.
```

### Functions.

```md
A function is a block of code,By using functions we can do some task and return some value.
```

```js
function name = {
console.log("My name is america")
}
name()
```

```md
There are a few types of functions in js.
We will get to that later.
But these are fun tooo.
The above functions is called a function declaration.
```

### Type of operator.
```md
By using this type of operator we can find out the data type of the value which is stored in the memory.
Let's say if you want ot find out what type of value this is.......
```

```js
var number = 24;
console.log(typeof number)
//Outputs:number

//Another example
var name  = "Los angeles"
console.log(typeof name)
//outputs : String.

var array1 = ["Losangeles","Neywork","Texas"]
console.log(typeof array1)
//Outputs: Array
//That's how cool JavaScript is.
```
### Operators

```md
What are operators?
We use operators to develop logic or expression in combinations with variables.
There are several types of operators in Js.

- Arthematic operator.(+,-,*,/,%,**,++,--)
- Assignment operator.(=)
- Comprission operator.()
- Ternery operator.()
- Logical operator.()
```

```md
Arthematic operators.
So what does these symbols mean.
(+,-,*,/,%,**,++,--)
```

```js
var audi = 100;
var bmw = 200;
console.log(audi+bmw)
//Output : 300
```

```js
var audi = 300
var bmw = 100
console.log(audi-bmw);
//Output : 200
```

```md
123 git test
```

### Set timeout function.
```md
Now we will look at the set timeout funtion.
If you want to delay the process or if you wan to make the function wait for the gicen specific time you can use this set timeout function.
```

```js
setTimeout(function(){conole.log("This is s settimeout function")},4000)
```


```md
what is a json file??

A json file is a Javascript object notation file and it is used to create files 
JSON is simply a data representation format very similar to xml and ymal.
It is used because it's extermley light weight to send the data back and forth, due to it's small file size.It's easy to read compared to xml.
Here is an quick example for the .JSOn file.
```
```js
[
{"company1":"google","fonder":"larrypage","ceo":"sundarpichai",},
{"company2":"Apple","founder":"Stevejobs","ceo":"timcook",},
{"company3":"amazon","founder":"Jeffbesoz","ceo":"jeffbezos"}
]
```
```md
So basically json file is kind of an object inside an array.
Get it.
```



