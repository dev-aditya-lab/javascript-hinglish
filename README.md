<p><a target="_blank" href="https://app.eraser.io/workspace/MsoStjXZRR150HB8zbYx" id="edit-in-eraser-github-link"><img alt="Edit in Eraser" src="https://firebasestorage.googleapis.com/v0/b/second-petal-295822.appspot.com/o/images%2Fgithub%2FOpen%20in%20Eraser.svg?alt=media&amp;token=968381c8-a7e7-472a-8ed6-4a6626da5501"></a></p>

![image.png](/.eraser/MsoStjXZRR150HB8zbYx___C2lgX3XM8CaKzHCYaLpnjSddqwy2___SrkpevXpu5limntsGxTe4.png "image.png")



# Topics:-
### Basics 
- [x] Inbuilt Features 
- [x] Variables constants
- [x] compilers and interpreters
- [x] Windows
- [x] Data Types
- [x] Conditionals
- [x] Loops
- [x] Function
- [x] Return
- [x] undefine, not define or null
- [x] Arrays
- [x] Loop with array
- [x] Objects
### Advance 
- [x] this call apply bind
- [x] prototypal inheritance
- [x] Closures
- [ ] event delegation
- [x] Higher order functions
- [ ] Error Handling (try... catch block)
- [ ] custom Event
- [ ] synchronous and asynchronous js 
- [ ] Es6 Climax
- [ ] Questions
### More things
- [ ] switch case
- [ ] Ternary operator
- [ ] do-while
- [ ] for in
- [ ] for of
### interview prep
- [ ] Prototypes
- [ ] prototypal inheritance
# JS the language
- code shikna or main features
# Js the DOM
- code likhkar chizen banan shikna


---

# JavaScript Ke Inbuilt Features
JavaScript ek powerful programming language hai jisme kai inbuilt features hote hain jo isko aur bhi flexible aur versatile banate hain. Yeh features kuch is prakar hain:

- **DOM Manipulation:** JavaScript ke through hum web pages ka Document Object Model (DOM) manipulate kar sakte hain, jaise ki elements ko add, remove, ya modify karna.
- **Event Handling:** JavaScript me hum different events handle kar sakte hain jaise ki button click, form submission, mouse hover, etc.
- **Asynchronous Programming:** JavaScript me async operations perform karne ke liye promises aur async/await ka use hota hai.
- **Built-in Objects:** JavaScript me kai built-in objects hote hain jaise ki Math, Date, JSON, etc.
- **Error Handling:** JavaScript try-catch block ke through errors handle karne ka mechanism provide karta hai.
# Variables aur Constants
JavaScript me variables aur constants define karne ke liye hum `var`, `let`, aur `const` ka use karte hain:

- **ES5:**
    - `var` : Variable declare karne ke liye use hota hai. Scope function-level hota hai.
```
 var name = "John";
```
- **ES6:**
    - `let` : Block scope variable declare karne ke liye use hota hai.
```
let age = 30;
```
- `const` : Block scope constant declare karne ke liye use hota hai. Ek baar value assign hone ke baad change nahi hoti.
```
const pi = 3.14;
```
# Compilers aur Interpreters
JavaScript ek interpreted language hai, iska matlab hai ki code ko directly browser ke through execute kiya jata hai bina pehle compile kiye. Browsers me JavaScript engine hota hai jo isko run karta hai, jaise ki Google Chrome ka V8 engine.

JavaScript ke compilers aur interpreters ke baare me samajhna zaroori hai, kyunki dono kaam alag tarike se karte hain, aur JavaScript ki performance par inka bada asar padta hai. Chaliye inhe thoda detail me samajhte hain.

### Interpreters
Interpreter ek aisa program hota hai jo source code ko line-by-line execute karta hai. JavaScript traditionally interpreted language thi. Interpreter code ko ek line padh kar turant execute karta hai, jisse development cycle fast hoti hai kyunki changes ko turant dekh sakte hain. Lekin, performance ke mamle me interpreter thoda slow hota hai kyunki har baar code run hone par wo line-by-line padh kar execute karta hai.

### Compilers
Compiler ek program hota hai jo poore source code ko ek baar me padh kar usse machine code me translate kar deta hai. Yeh machine code directly CPU ke dwara execute hota hai, isliye yeh bahut fast hota hai. Traditional compilers, jaise C++ ya Java ke, code ko compile karne me thoda time lagate hain, lekin compiled code ki execution speed bahut fast hoti hai.

### JavaScript ke Modern Engines
JavaScript me dono approaches ka combination use hota hai, jaise ki Google Chrome ka V8 engine aur Firefox ka SpiderMonkey. Yeh engines initially code ko interpret karte hain taaki turant execution start ho sake. Baad me, yeh frequently used code ko JIT (Just-In-Time) compilation ka use karte hue machine code me compile kar dete hain, jisse performance improve hoti hai.

**V8 Engine (Chrome):**

- Initially code ko interpret karta hai.
- Frequently executed code ko JIT compiler ke through optimize karta hai.
- Performance enhance karne ke liye garbage collection aur other optimization techniques ka use karta hai.
**SpiderMonkey (Firefox):**

- Similar to V8, yeh bhi initially interpretation karta hai.
- Fir, hot code ko JIT compiler se compile karke optimize karta hai.
# Windows
JavaScript ka use sirf browser me nahi, balki backend me bhi hota hai Node.js ke through. Lekin browser environment me JavaScript ko use karne ke kuch khas tareeke hain:

- **Window Object:** JavaScript me global object hota hai `window` , jo browser window ko represent karta hai. Sabhi global variables aur functions `window`  object ke properties aur methods hote hain.
```
console.log(window.location.href); // Current URL print karta hai
```
- **Window Methods:**
    - `alert()` : Ek message box show karta hai.
```
alert("Hello, world!");
```
- `confirm()` : Ek dialog box show karta hai with OK and Cancel buttons.
```
if (confirm("Are you sure?")) {
  // OK clicked
} else {
  // Cancel clicked
}
```
- `prompt()` : User se input leta hai.
```
let name = prompt("Enter your name:");
```


![image.png](/.eraser/MsoStjXZRR150HB8zbYx___C2lgX3XM8CaKzHCYaLpnjSddqwy2___mwdaEzsFh-ONqhj8etXw6.png "image.png")

# Data Types:-
## Primitive Data Types
- String `﻿"aditya"` 
- Number/integer `﻿1234568` 
- Flot `﻿12.05` 
- Boolean `﻿true or false, 0 or 1` 
- character `﻿a` 
- null
- undefine
## Reference Data Type
- ()
- []
- {}
# Conditionals
 

- if
- else
- else-if
- switch case
# loops
loops that mean repeat

---

## Types of loops
- for (70% use)
- while
- do-while
- for each (25% use)
- for-in
- for-of
### For loop
```javascript
for(start; end; change){
  //code
}
```
- write a program to print  numbers from  20 to 5
```javascript
for(let i = 20; i >= 5; i--){
    console.log(i);
}
```
### while
```
start;
while(end){
  //code
 
  condition/change
}
```
- write a program to print numbers from 5 to 50
```
let i = 5;
while(i<=50){
    console.log(i);
    i++;
}
```
### for each
- for each ek normal loop nahi hai ye sirf arrays pr chalta hai  [﻿array](https://app.eraser.io/workspace/MsoStjXZRR150HB8zbYx#TCHorrOs0LWdli404GEUW)﻿
# Function
agar koi kaam baar baar krna padh rha hai toh ham usko function ke ander likh skte hain.

yasa code jisko abhi nahi chlana ho ya fir kabhi or chalna ho



```javascript
function functionName (param){
  //code
}
```
- param ho v skta hai or nahi v
- ** function ko hamesa call krna hota hai bina call kiye function nahi chlega. call krne ke liye  bs function ka naam or () laga dena hota hai or function call ho jayega `﻿functionName();` 


---

![image.png](/.eraser/MsoStjXZRR150HB8zbYx___C2lgX3XM8CaKzHCYaLpnjSddqwy2___vqI3rD-jtCLXKD2gpvhD3.png "image.png")

---

## Types of function
- ES5 or ES6
### ES5 Functions:-
1. function statements
2. Function expressions
3. Anonymous function
#### Function statement
```
function abcd(){
  //code
}
```
#### Function expression
```
let abcd = function(){
  //code
}
```
#### Anonymous Function
```
function(){
  //code
}
```
### ES6
1. Fat arrow function
    1. Basics fat arrow function
    2. fat arrow with one param
    3. fat arrow with an implicit return
#### Fat arrow function
```
let a = ()=> {
  //code
}
```
##### Basics fat arrow function
```
let a = ()=>{
  //code
}
```
##### Fat arrow function with one param
```
let a = val => {
  //code
}
```
##### Fat arrow function with an implicit return
- implicit return that means jb ham ko sirf ek hi chiz return krna ho tho ham log `{}` ka use nahi v kr skte hai yasa nahi hai ki use kr nahi sakte hai kr skte hain aapka mn .
- Return kya hota hai ye iske baad hai q ki bina function padhe return ko padhna posspossible nahi hai [﻿Return](https://app.eraser.io/workspace/MsoStjXZRR150HB8zbYx#1U89XJOohAK0vIAN8XgyS) 
```
let a = () => 12+13
```
```
let a = (val) => +5 
```
```
let a = val => val+5
```
# Return
return yasa chiz hai ki agar aap return ke baad jo v likhte hain wo return ho jata hai mtlb ki code ke pass chla jata hai jo v aap return ke baar ya return ke andr likhe ho.

ya yasa kha skte hai ki jaha pr function call huaa tha return wala code waha pe jayega us line pr jaha pe function call huaa tha.

or return function me lgta hai 

```
function abcd (){
  return 12;
}

abcd();

//output
   12
```
# undefine, not define or null
## Undefine
- ye value tb jati hai variable ko koi value na mili ho tb ye value jati hai `undefile`
- un define an error nahi value hai
## Not define
- not define an error hai
## NULL
- null is also a value jb code kuch khojta hai or usko nahi mlta hai toh hme null receive hoga 
# array
- array mtbl jb v ek ya ek se jyda value ek sath rakhni ho toh ham array banate hai
- or un sabhi values ko hame `﻿[]`  ke ander hi likhna pdega this is important 
- array hamesa 0 se counting start krta hai mtlb 0 1 2 3 4 yasa kuch jisko ham log index bolte hai
```
let userDetails = ["aditya", 20 , "male" , "india"]
```
- yaha `﻿aditya` ka index `﻿0` hai
- `﻿20`  ka `﻿1` 
- `﻿male` ka `﻿2` 
- or `﻿india` ka `﻿3`  hai
- jase ki hamko agar aditya print krna hai toh toh ham likhenge 
```
﻿console.log(userDetails[0]) 
```
# loop with array
```
let arr = [1,2,3,4,5,6,7,8,9];
```
array me hamlog loop bhut sare cases me lgate hai jase ki 

- agra hamko array ke sare item ko print krna ho 
- sare item ko add krna ya metamathematical calculations krna ho 
- items ko count krna ho  
## for each
```
arr.foreach(function(val){
  console.log(val);
})
```
- ye array ke har elements ko 1-1 krke print karega
# object
object ek trika jisme ham bhut sari details ek sath rakh skte hai, mtlb ki jase ek city me bhut sare aditya hai  or ham har aditya ke liye 1-1 object bana skte hai or object me ham uska naam, age, no, address, etc bhut kuch rakh skte hai. 

- object banane ke liye ham `﻿{}`  ka use krte hai
```
var obj = {
  key : data
}
```
> yaha pr key ka naam kuch v ho skta hai jo aap chahe or data me uska value 



- object banane ke or v trike hain jase ki 
```
var obj2 = new object();
```
ham log  object ko yese banate hai real life me  

```
var obj = {
  name : "aditya",
  age : 20,
  number : 12345467890,
}
```
- object ko use krne ke liye object ka dot key ka naam likhte hai`﻿obj.name` 
# synchronous and asynchronous js 
>  JavaScript me synchronous aur asynchronous programming kaafi important concepts hain. Dono kaam karne ke tarike me farak hota hai, aur yeh alag-alag scenarios me use hote hain.

## Synchronous JavaScript:
Synchronous programming me code line-by-line execute hota hai. Iska matlab yeh hota hai ki ek line tab tak execute nahi hogi jab tak pehle wali line execute na ho jaye. Yeh ek blocking process hai.

**Example:**

```javascript
console.log("Start");
console.log("Processing...");
console.log("End");
```
Is example me "Start", "Processing..." aur "End" line-by-line print hoga. Jab tak pehli line execute nahi hoti, doosri line execute nahi hogi.

## Asynchronous JavaScript:
Asynchronous programming me code ek saath execute ho sakta hai bina kisi line ko block kiye. Yeh non-blocking process hai. JavaScript me asynchronous code likhne ke liye hum callbacks, promises aur async/await ka use karte hain.

> callbacks, promises aur async/await** ke bare me ham aage dekhenge**

**Example using setTimeout (callback):**

```javascript
console.log("Start");

setTimeout(() => {
  console.log("Processing...");
}, 2000);

console.log("End");
```
Is example me "Start" sabse pehle print hoga, phir "End" print hoga aur 2 seconds ke baad "Processing..." print hoga. setTimeout asynchronous function hai jo 2 seconds ke liye wait karega bina console.log("End") ko roke.

- **Synchronous**: Ek time pe ek hi kaam hota hai, blocking process.
- **Asynchronous**: Multiple kaam ek sath ho sakte hain, non-blocking process.
Dono approaches ke apne-apne advantages aur use-cases hain, aur JavaScript me asynchronous programming zyada tar aise operations ke liye use hoti hai jo time-consuming hote hain jaise ke data fetching, timers, file handling, etc.

---

# Advance javaScript
---

# this,  call, apply,  bind
## this :- 
- this ki value baar baar badal skti hai alag alag conditions main
### this ki conditions
- global 
    - window
![image.png](/.eraser/MsoStjXZRR150HB8zbYx___C2lgX3XM8CaKzHCYaLpnjSddqwy2___ikfQJu6jYiYawJhozyi0_.png "image.png")



- function
    - window
![image.png](/.eraser/MsoStjXZRR150HB8zbYx___C2lgX3XM8CaKzHCYaLpnjSddqwy2___vJXp6j1BSVVvp8JziNByw.png "image.png")



- method
    - object
![image.png](/.eraser/MsoStjXZRR150HB8zbYx___C2lgX3XM8CaKzHCYaLpnjSddqwy2___zi5iDVGKFUiNz0d7pQ3bj.png "image.png")



- function inside method (es5)
    - window
![image.png](/.eraser/MsoStjXZRR150HB8zbYx___C2lgX3XM8CaKzHCYaLpnjSddqwy2___feeOltDcIgsixFKzgznD2.png "image.png")



- function inside method (es6)
    - object
![image.png](/.eraser/MsoStjXZRR150HB8zbYx___C2lgX3XM8CaKzHCYaLpnjSddqwy2___2UuwGy8755GSckZO98NK2.png "image.png")



- constructor function me this ki value 
    - new blank object
![image.png](/.eraser/MsoStjXZRR150HB8zbYx___C2lgX3XM8CaKzHCYaLpnjSddqwy2___lr414bu1sCxFJkCkv228P.png "image.png")

- event listener main this ki value
    - wo element jis pr event listener laga ho 


![image.png](/.eraser/MsoStjXZRR150HB8zbYx___C2lgX3XM8CaKzHCYaLpnjSddqwy2___Xjl75q90ir6o021xHFtHK.png "image.png")



# call, apply, bind
- ye teen trike hai function ko call krne ke kisi object ko `﻿this` maan kr
## call
```
let obj = {name : "aditya"};

function abc () {
  console.log(this);
}

```
- finction ko call krte time `﻿.call`  laga kr argument me jo v pass kiya jaye `﻿this` ki value wo ho jati hai
```
  abc.call(obj);
```
## apply
- jb function parameters mang rahi ho toh apply use krte hai
```
let obj = {name : "aditya"};

function abc (a,b,c) {
  console.log(this);
}

```
- finction ko call krte time `﻿.apply`  laga kr argument me phle `﻿this` ki value or uske baad array me parameters ki values pass kr skte hain 
```
  abc.apply(obj,[1,2,3]);
```
## bind
ye v call ki tharah hota hai lakin ye ek new function return krta hai jisko ham baad me call kr skte hain

```
let obj = {name : "aditya"};

function abc () {
  console.log(this);
}

```
- isme v call ki tharha finction ko call krte time `﻿.apply`  laga kr argument me jo v pass kiya jaye `﻿this` ki value wo ho jati hai lakin ham uako kisi variable me store kr ke baad me call kr skte hain 
```
  let newFunction = abc.bind(obj);
```
```
newFunction();
```
# prototype inheritance


![image.png](/.eraser/MsoStjXZRR150HB8zbYx___C2lgX3XM8CaKzHCYaLpnjSddqwy2___-h2bxJwEp0aqQtKGtnpxt.png "image.png")

# Closures
> yasa koi function jo kisi or function ko return krta ho usey closures lakin lakin wo use kre parent function ka koi variable

```
function abc(){
  let a = 15;
  return function(){
    console.log(a);
  }
}
```
```
let def = abc();

bef();
```


# Higher order function
Higher-order functions JavaScript me wo functions hote hain jo ya to ek ya zyada functions ko as an argument lete hain, ya phir ek function ko return karte hain, ya dono cheezein karte hain. Yeh functions functional programming me bahut use hote hain aur yeh code ko zyada modular aur reusable banate hain.

> mtlb ki jb ham argument me function pass krte hai or function paramerer me function accept krta hai usko higher order function khate hain

```
function abc (fun) {
  
}
```
```
abc(function(){});
```
> ya fir agar koi function function return krta ho use v higher order function khte hain ye clousers ke jasa dikh rha hai  lakin clouser me parent function  variable return function use krta hai lakin higher order function me yasa nahi hai agar koi function return me function hi return kr rha hai toh wo higher order function hogaa

```
function () {
  return function (){}
}
```
Higher-order functions ka fayda yeh hai ki aap complex operations ko concise aur readable tarike se likh sakte hain. Yeh functions alag-alag parts ko handle karte hain, jisse code maintain karna asaan hota hai aur errors kam hote hain.

> jase ki foreach, map, filter ye sb higher order functions hai

# Error Handling (try... catch block)
sb se phle code dekhte hai likha kase jata hai try catch

```
function abc(a,b){
  
  
  try{
    if(b == 0 ){
          throw Error("something want wrong");
       }else{
         console.log(a/b);
     }
   }
   
   
      catch(error){
      console.log(error);
    }
    
    
 }
```
toh is function me ham divide kr rhe hai jime agar ham `﻿b` me 0 pass krte hai toh toh hamne jo error throw kiya hai wo console me dikhega.



![image.png](/.eraser/MsoStjXZRR150HB8zbYx___C2lgX3XM8CaKzHCYaLpnjSddqwy2___jAZNDiKmln7M0nPzyjYvy.png "image.png")





<!--- Eraser file: https://app.eraser.io/workspace/MsoStjXZRR150HB8zbYx --->