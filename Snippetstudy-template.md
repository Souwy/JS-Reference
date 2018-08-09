# Snippetstudy_main-subject_sub-subject
<!---
- Identify a concept or skill you sort of understand, but would like to master. gradually develop the clearest snippet to communicate this principle
- Construct (or find) a simple example that isolates this skill or concept.
- Software tools to visualize code behavior
- Break down the snippet:
  - Is there anything you're not familiar with that isn't your target concept?
  - Do the variables names help understand the code?
  - Are there any logs or asserts that might help?
  - Avoid Comments, let the code's behavior speak for itself.
  - Does it fit well with the chosen study environment?
- Use paper & pencil to sketch code behavior
- Describe & predict code behavior
- Understand the same code from different perspectives
- Select the right visualization tools for your use case
--->
## What makes a good snippet and a good exercise?
How do I create a good snippet? You need to have very clear idea of what are you trying to learn out of the snippet.   
   
Isolate the snippet: break down the snippet and see what you don't understand and try to take the smallest bit of code that only has the thing you want to learn.   
   
Be careful on what name of the variables but also the values. For example, we want to learn about block scopes. We have a variable that is inner_var in the first block and the value is global var so you understand that this inner_var in the block has a global scope, by the value you give to your variable.   
   
Put the comment at the beginning of the snippet on what you want to learn, what the snippet is about. But nothing with values or variable because they are static: _what exactly am i trying to illustrate?_   
=> You take the expression you want to study and you make a trace block out of it : make it more understandable.
   
eg. you want to illustrate ++. I need an expression that uses it and only that

## Description
This is about...

<!---
personal note: use ctrl+f and lookup "continued" to find where you haven't finish.
-->

## Learning objectives (keywords)
* 

## Code snippet
```js
code
```
[repl.it]()  
[pythontutor]()  
   
Tracing table (deconstruction of input/output):
   
State nr. | State | Operation
------------|------------ | -------------
S0  | null |  
 . |  | Boolean (null)
S1 | false | 
. | | Void (undefined; "undefined")
S2 | undefined | 
. |  | Number (Number; Nan)
S3 | Nan | 
. |  | typeof (string; "Number")
S4 | "Number" | 
. | | "Number".toString
S5| "Number" | 
. | | typeof "number" (BECAUSE "number" is actually a string. "n-u-m-b-e-r"
S6 | "string" | 
   
## Vocabulary
   
## Review
* Struggles:   
  *   
* Learning objectives that need extra work?   
  *
* next steps:   
  * 
   
## Helpful links
