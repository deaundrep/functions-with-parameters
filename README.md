###Functions With Global Variables

### Tasks

Let's start by creating our variables (using `let` this time, but we'll move back to `const` soon enough!) so that we can manipulate them later on with functions. 

* Create a variable called `x` and set it to the value 3.
* Create a variable called `y` and set it to the value 10.
* Create a variable called `z` and set it to the value 5.
* Create a variable called `name` and set it the string version of your first name.
* Create a variable called `greeting` and set it to the value `'HEY'`.


Now for some functions!

* Create a function called `multiply` that takes in one parameter and changes `x` to the product of `x` and that parameter.
* Create a function called `modYBy` that takes in one parameter, divides `y` by that parameter, and sets `y` to the remainder of that division. Look up the JavaScript modulus operator if you don't remember it, because it could sure come in handy here!
* Create a function called `opposite` that takes in a parameter and sets `z` to equal the opposite sign of that parameter. Note that we are not "reading" the value of `z` here. In other words, unlike the other problems here, it doesn't matter what `z` used to be!
* Create a variable called `makeFullName` that takes in a string parameter and sets `name` to have that string at the end, with a space in the middle.
* Create a function called `yellAt` that takes in a string parameter and adds that string to the end of `greeting`, with a comma and a space in between and an exclamation point at the end. This string concatenation (or "smooshing" in the technical parlance) should be set to be the new value of `greeting`.