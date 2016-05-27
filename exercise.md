## Data Types

What is the return value of each of the below code snippets? Come up with an answer before testing them out in the console.

```js
typeof( 15 );
// Include your answer below each line using a comment, like this.

typeof( 5.5 );
typeof( NaN );
typeof( "hello" );
typeof( true )
typeof( 1 != 2 );

"hamburger" + "s";
"hamburgers" - "s";
"1" + "3"
"1" - "3"
"johnny" + 5;
"johnny" - 5
99 * "luftbaloons";
```

What's going on in the second half of the previous question? Are there any "rules" we can pull from those examples?

## Data Collections

### Arrays

Javascript provides us with a number of native methods that allow us to interact with arrays. Find methods that do each of the following and provide an example...
* Add an element to the back of an array.
* Remove an element from the back of an array.
* Add an element to the front of an array.
* Remove an element from the front of an array.
* Concatenates all the elements in an array into a string.
* Separates the characters of a string into an array.

```js
// Your answers go here.
```

What will the contents of the below arrays be after the code samples are executed? Come up with an answer yourself before testing it out in the console.
> **HINT:** You might find it helpful to draw the arrays out as you run each line of code.

```js
var numbers = [ 2, 4, 6, 8 ];
numbers.pop();
numbers.push( 10 );
numbers.unshift( 3 );
```

```
Your answer goes here.
```

What is the return value of the below code sample? Come up with an answer yourself before testing it out in the console.

```js
var morse = [ "dot", "pause", "dot" ];
var moreMorse = morse.join( " dash " );
moreMorse.split( " " );
```

```
Your answer goes here.
```

What will the contents of the below array be after the below code sample is executed? Come up with an answer yourself before testing it out in the console.

```js
var bands = [];
var beatles = [ "Paul", "John", "George", "Pete" ];
var stones = [ "Brian", "Mick", "Keith", "Ronnie", "Charlie" ];
bands.push( beatles );
bands.unshift( stones );
bands[ bands.length - 1 ].pop();
bands[0].shift();
bands[1][3] = "Ringo";
```

```
Your answer goes here.
```

## Booleans & Comparison Operators

Here's an example truth table for the `!` (not) operation. In it, we're listing the values of `!a` that correspond with a given value of `a`.

|a|!a|
|---|---|
|true|false|
|false|true|

Fill out the truth tables below for `&&` (and), `||` (or) and one that uses multiple comparison operators. All you need to do is replace the `?`'s with either `true` or `false`.
> **NOTE:** Because of markdown formatting, `||` and `&&` have been replaced with `OR` and `AND` respectively.  
> **HINT:** With the last one, it may be helpful to add additional columns to the table for each individual comparison.  

| a | b | a AND b |
| --- | --- | --- |
| true | true | ? |
| true | false | ? |
| false | true | ? |
| false | false | ? |

|a|b|a OR b|
|---|---|---|
|true|true|?|
|true|false|?|
|false|true|?|
|false|false|?|

|a|b|a `!=` b|
|---|---|---|
|3|3|?|
|1|5|?|
|2|"2"|?|

|a|b|!a AND (a OR b)|
|---|---|---|
|true|true|?|
|true|false|?|
|false|true|?|
|false|false|?|

### "Truthiness" and "Falsiness"

You've seen the boolean values of `true` and `false`.

There is also a concept of "truthy" and "falsey". In Javascript, the following things are "falsey":

- `false`
- `0` (zero)
- `""` (empty string)
- `null`
- `undefined`
- `NaN` (a special Number value meaning- Not-a-Number!)

Everything else is "truthy".

These do the same thing:

```js
var name = '';
if(name == ''){
  alert('Enter your name, please');
}
if(!name){
  alert('Enter your name, please');
}
```

## Conditionals

You're a bouncer at a bar! Given an `age` variable, create a conditional that satisfies the following requirements...
* If a patron is older than `21`, print out `"Come on in!"`.
* If a patron is between `18` and `21`, print out `"Come on in (but no drinking)!"`.
* If a patron is younger than 18, print out `"You're too young to be in here!"`.
* If a patron is older than 75, print out `"Are you sure you want to be here?"`.

```js
// Your answer goes here.
```

## Loops

Your task is to create a loop that prints out all the odd numbers between 1 and 100...twice! Use a different type of Javascript loop each time.

```js
// Your answer goes here.
```

## Bonus: Fizz-Buzz
Fizz-Buzz is a classic coding exercise that you can create using your knowledge of conditionals and loops. Implement code that does the following...
* Counts from 1 to 100 and prints out something for each number.
* If the number is divisible by 3, print `"Fizz"`.
* If the number is divisible by 5, print `"Buzz"`.
* If the number is divisible by both 3 and 5, print `"FizzBuzz"`.
* If the number does not meet any of the above conditions, just print the number.

Your output should look something like this...
```
1, 2, Fizz, 4, Buzz, Fizz, 7, 8, Fizz, Buzz, 11, Fizz, 13, 14, Fizz Buzz, 16, 17, Fizz, 19, Buzz, Fizz, 22, 23, Fizz, Buzz, 26, Fizz, 28, 29, Fizz Buzz, 31, 32, Fizz, 34, Buzz, Fizz, ...
```

```js
// Your answer goes here.
```
