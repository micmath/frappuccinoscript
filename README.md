Introducing FrappuccinoScript
=========================

> There's not a man, woman or child on the face of the earth, who doesn't enjoy a tasty beverage.
>
> _Mr David Letterman_

FrappuccinoScript is a proposal for a brand new dialect of JavaScript that is designed to add mountains of creamy filling to the watery JavaScript offering we've had to consume in the past. Of course, at it's foamy center, FrappuccinoScript is still JavaScript, in fact our motto is, "It's just a rather verbose version of JavaScript."

FrappuccinoScript is here for those of us who find plain-old JavaScript just too damned confusingly terse! For example, in _ordinary_ JavaScript you write `var` for "variable," yet cannot write `fun` for "function." WTF? How many hours have you wasted trying to guess which keywords are shortened and which are not?
FrappuccinoScript solves this problem by normalising all the inconsistency away, so you can always write the most verbose form of any expression, all the time.

At last! Someone fixed JavaScript; no more confusing terseness!!!

## Declaring and Defining Variables

We do away with all the "confusing parts" of JavaScript, including the famously misjudged "comma operator" and the ability to both declare and define a variable in the same statement.

In addition, you can forget about trying to decide when to use a primitive value and when to use a full-on object wrapper for your numbers strings; FrappuccinoScript doesn't even recognise primitives without a full object wrapper!

**Write FrappuccinoScript**

```js
variable x;
variable y;
variable z;
x = new Number(1);
y = new Number(2);
z = new Number(3);
```
**Compiles to JavaScript**
```js
var x = 1, y = 2, z = 3
```

And look! Never sure when you should and shouldn't use semicolons or newlines, or...??? Not any longer. In FrappuccinoScript semicolons **and** newlines are _always_ required! It actually won't run any with other combination!

## Built-In Mathematical Functions

Stop trying to guess what shortened name to use, and just relax while you spell out out the entire, full, _long form_ of every name!

**Write FrappuccinoScript**
```js
variable x;
x = Mathematics.absoluteValueOf(x);
variable y;
y = Mathematics.LEONHARDEULERSNUMBER;
variable z;
z = Mathematics.arctangentOf(z);
```
**Compiles to JavaScript**
```js
var x = Math.abs(x), y = Math.E, z = Math.arc(z)
```

## Global Built-In Functions

All global built-in functions are defined by their full **un**-abbreviated names. Confusing and error-prone constructs like "nesting" of function calls or "chaining" of method results are _never allowed_ in FrappuccinoScript.

**Write FrappuccinoScript**
```js
variable a;
a = new String("x*y");
a = evaluate(a);
a = parseIntegerFrom(a);
```

**Compiles to JavaScript**
```js
var a = parseInt( eval("x*y") )
```

_† Sick and tired of coworkers mocking your use of JavaScript's `eval` function by calling it "evil"? Well just watch them try to come up with a catchy putdown that rhymes with FrappuccinoScript's `evaluate`!_

## There's More!

Now you can switch into FrappuccinoScript mode with one simple statement at the top of your script files. Simply add the statement `use "verbose";`, then sit back and enjoy all the keyboard-straining, LOC-growing, pedantic completeness that FrappuccinoScript requires (and will immediately throw syntax errors to ensure that it _gets_), without any of the terseness that had previously stopped JavaScript from being the most beautiful language you've ever used!

**Write FrappuccinoScript**

```js
use "verbose";

variable s;
s = new String("beautiful");
variable n;
n = new Number(1);
variable c;
c = s.characterAtPosition(n);
```

**Compiles to JavaScript**
```js
var c = "beautiful".charAt(1)
```


&copy; 1st April 2014, Michael J Mathews. All rights Reserved. 