FrappuccinoScript
=========================

> There's not a man, woman or child on the face of the earth, who doesn't enjoy a tasty beverage.
>
> _David Letterman_

FrappuccinoScript is a proposal for a new dialect of JavaScript that is designed to _add_ to the traditional JavaScript offering we all know and love. But at it's frothy core, FrappuccinoScript **is** JavaScript, in fact our motto is, "It's just a very verbose version of JavaScript."

FrappuccinoScript is here for those of us who find plain-old JavaScript just too confusingly terse. For example, in _ordinary_ JavaScript you write `var` for "variable" yet cannot write `fun` for "function." How many hours have you wasted trying to guess which keywords are shortened and which are not?
FrappuccinoScript solves this problem by normalising all the inconsistency away, so you can always write the most verbose form of any expression, all the time.

At last! JavaScript without the confusing terseness!!!

## Declaring and Defining Variables

We do away with all the "confusing parts" of JavaScript, including the misjudged "comma operator" and the ability to both declare and define a variable in the same statement.

In addition, you can forget about trying to decide when to use a primitive value and when to use a full-on object wrapper for your numbers; FrappuccinoScript doesn't even recognise primitives without a full object wrapper!

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
var x=1,y=2,z=3
```

Notice also: Not sure when you can and can't use semicolons or newlines or...??? Not any longer. In FrappuccinoScript semicolons **and** newlines are _always_ required!

## Built-In Mathematical Functions

Stop trying to guess what shortened name to use, and just relax while you write out the full _long form_ of every name!

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
var x=Math.abs(x),y=Math.E,z=Math.arc(z)
```

## Global Built-In Functions

All global built-in functions are defined by their full **un**-shortened names. Confusing, error-prone constructs like nesting of function calls are not allowed.

**Write FrappuccinoScript**
```js
variable a;
a = new String('x*y');
a = evaluate(a);
a = parseIntegerFrom(a);
```

**Compiles to JavaScript**
```js
var a=parseInt(eval('x*y'))
```

## And More!

Now you can switch into "verbose mode" with a simple statement at the top of your script file. Simply add the statement `use "verbose";`, sit back and enjoy the full, long-winded completeness that, without any of the teresness had previously stopped JavaScript from being the most beautiful language you've ever used!

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
var c="beautiful".charAt(1)
```


&copy; 1st April 2014, Michael J Mathews. All rights Reserved. 