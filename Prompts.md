#### Variables
* Variables are containers which will hold some value of data. Each container (variable) has a label (variable name) which helps us and the computer remember which variable has what data. Variables allow you to reference, access and change that data easily.
Think about multiple empty food containers and pile of multiple kinds of cookies, if you were to label each container with a type of cookie and sort the cookies into each containers, you can think of each container as a variable and the cookies inside as the variable value/data. Now you don't have to worry about holding an individual cookie, you can take your cookie container and pass it your friend, or you can take your cookie out and cover it with frosting and put it back into container. 

#### Strings
 * Strings are a type of value that hold any squence of characters, similar to words or sentences. You can use strings to define any sort of text based values. Strings can be empty, and can be numbers, however strings are not numbres. "10" is completely different than 10.

 #### Functions
 * Functions are blocks of reusable code that perform a certain action that usually produce and return an output. The output can vary depending if the function definition accepts arguments through their parameters. 
 You usually define functions when you require reptitive code in more than one places or to clean up 
 your main logic into more readable actions. Think about waiters at a restaurant as a program, each waiter has a function to bring you the food you order, no matter what you order the waiter repeats the same action, they go to the kitchen and returns with the dish you ordered. Each waiter expects to recieve an order of food similar to how a function defines parameters of data it may expect, when you tell the waiter what food you want, it's like passing an argument to the function you are calling.

```
function <functionName>(<parameters>) {
    <code>
    return <statement>
}
```

```
 function orderFood(foodItem) {
     console.log("Tell waiter you would like to order" + foodItem");
     console.log("Waiter goes to kitchen");
     return "Waiter returns with food item " + foodItem;
 }
 ```

 #### if statements

 * if statements are a block of code that wrap other code and determine if the wrapped code will run and execute depending on the if statement's expression. If the if statement expression resolves to `true` the wrapped code will execute. If the expression resolves to `false` the wrapped code will not execute. You can also include an `else` statement which will execute if the parent if statement does not. In day to day life everyone makes `if` statements, when you're running `if` your shoes are untied, you perform the action of tying your shoes, `else` you proceed to continue running. 

```
var shoesUntied = false;

if(shoesUntied) {
    tieShoes();
} else {
    continueRunning():
}
```

#### Bolean Values
* Boolean values are either `true` or `false`. The state of your shoelaces can be a boolean value, are they tied or they not? Is it `true` that they are tied, or is it `false` that they are tied.
