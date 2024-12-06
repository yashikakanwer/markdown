# 🚀   "JavaScript: The Language of Modern Web Development"



## **Title Page**
- **Report Title:**  
  _"An Introduction to JavaScript and Variables: Foundation of Modern Web Development"_  
- **Prepared by:** Yashika Kanwer  
- **Date:** 6 December 2024  

---

## **Table of Contents**
1. **Introduction to JavaScript**  
    1.1 [History of JavaScript](#11-history-of-javascript)  
    1.2 [Importance of JavaScript](#12-importance-of-javascript)  
    1.3 [Features of JavaScript](#13-features-of-javascript)  
    
2. **Variables and Data Types in JavaScript**  
    2.1 [Declaring Variables](#21-declaring-variables)  
    2.2 [Rules for Naming Variables](#22-rules-for-naming-variables)  
    2.3 [Data Types in JavaScript](#23-data-types-in-javascript)  
        - [Primitive Data Types](#primitive-data-types)  
        - [Object Data Types](#object-data-types)  
    2.4 [Variable Scope](#24-variable-scope)  
    2.5 [Hoisting](#25-hoisting)  
3. **Conclusion**  

---

### **1. Introduction to JavaScript**
•  A powerful, high-level programming language used for creating dynamic and interactive websites.
•  JavaScript is essential for both client-side and server-side development.
•  React, Angular, and Node.js are built with JavaScript.
•	Can be used for web apps, mobile apps, and even backend development.


#### **1.1 History of JavaScript**
_JavaScript ka janm 1995 mein hua tha, jab Netscape company ke Brendan Eich ne ise sirf 10 din mein banaya. Pehle iska naam Mocha tha, phir LiveScript, aur aakhir mein JavaScript rakha gaya. Ye HTML aur CSS ke saath use hoti hai websites ko interactive banane ke liye. Suru mein, JavaScript sirf browser ke liye thi, lekin ab Node.js ke zariye backend development ke liye bhi use hoti hai. Aaj ye web development ki jaan hai!._

#### **1.2 Importance of JavaScript**
_JavaScript is crucial for adding interactivity, dynamic content, and responsive behavior to websites, making them engaging and user-friendly._

#### **1.3 Features of JavaScript**
_JavaScript is versatile, supporting event-driven programming, dynamic typing, and asynchronous operations, enabling interactive web experiences and real-time applications._

---

### **2. Variables and Data Types in JavaScript**

#### **2.1 Declaring Variables**
Just like we follow some rules while speaking English we have some rules to follow while writing a javascript programme the set of these rules is called syntax in javascript 

#### What is a variable?
 A variable is a container that store a value this is a very similar to the container used to store rice water and oats. The value of a javascript variable can be changed during the execution of a programme. 

To use variables in JavaScript, we first need to create it i.e. declare a variable. To declare variables, we use one of the var, let, or const keywords.

----- 

### Var vs Let v const in JavaScript
| Feature        | var            | let            | const           |
|----------------|----------------|----------------|-----------------|
| **Scope**      | Global         | Block          | Block           |
| **Redeclaration** | Allowed     | Not allowed    | Not allowed     |
| **Reassignment** | Allowed      | Allowed        | Not allowed     |
| **Initialization** | Undefined  | Not initialized | Must initialize |

#### **2.2 Rules for Naming Variables**
•	letter digit under scoops and sIGN allowed .
•	it must have been with  a $ _ or a letter 
•	javascript reserved word cannot be used as a variable name 
•	Harry and haRry are different variable .

__

#### **2.3 Data Types in JavaScript**
  There are 2 types of Data types 
  1. primitve data types 
  2. Non primitive data types 

##### **Primitive Data Types**

Primitive data types are a set of basic data types in javascript

there are seven primitive data types in javascript 
1.	null 
2.	number 
3.	string 
4.	symbol 
5.	undefined 
6.	boolean
7.	Bigint  


##### **Object Data Types**
_Object data types in JavaScript are used to store collections of key-value pairs or complex data. Examples include arrays, functions, and user-defined objects. Objects are versatile and essential for managing structured, dynamic information efficiently._

__

---

#### **2.4 Variable Scope**

There are 4 types pf scopes 
 #### 1. Global Scope
•	Declaration: Variables declared outside any function or {}.
•	Access: Available throughout the entire script.
•	Keywords: var, let, const.

#### 2. Function Scope
•	Declaration: Variables defined within a function.
•	Access: Accessible only inside that function.
•	Keywords: var, let, const.
________________________________________
#### Scope Evolution with ES6
#### 3. Block Scope
•	Declaration: Variables inside {} (e.g., loops, conditionals).
•	Access: Only within the block.
•	Keywords: let, const.
•	Special Note: var doesn’t support Block Scope.
________________________________________
#### 4. Local Scope
•	Declaration: Same as Function Scope (within a function).
•	Access: Limited to the function.
•	Lifecycle: Created on function start, destroyed after completion.
_

#### **2.5 Hoisting**
_JavaScript Hoisting refers to the process whereby the interpreter appears to move the declaration of functions, variables, or classes to the top of their scope, prior to execution of the code._

---

### **3. Conclusion**
_JavaScript ek powerful programming language hai jo web development mein interactivity aur dynamic features add karta hai. Variables data ko store karne ka tareeka hain, aur JavaScript mein different data types, jaise objects, arrays, aur functions, hote hain jo complex data ko handle karte hain aur programming ko efficient banate hain._
