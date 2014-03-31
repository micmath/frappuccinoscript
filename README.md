HotcaffeinatedbeverageScript
=========================

> There's not a man, woman or child on the face of the earth, who doesn't enjoy a tasty beverage.
>
> _David Letterman_

HotcaffeinatedbeverageScript is a proposal for a new dialect of JavaScript. In fact our motto is, "It's just very verbose JavaScript." HotcaffeinatedbeverageScript is meant for those of us who find regular JavaScript too terse.

For example, in JavaScript you write `var` for "variable" but cannot write `fun` for "function." How many hours have you wasted trying to guess which keywords are shortened and which are not?
HotcaffeinatedbeverageScript solves this problem by normalising all the inconsistency away, so you can always write the most verbose form of any expression, all the time.

At last! JavaScript without the confusing terseness!!!

## Declaring and Defining Variables

We do away with all the "confusing parts" of JavaScript, including the misjudged "comma operator" and the ability to both declare and define a variable in the same statement.

Notice you can forget about trying to decide when to use a primitive value and a full object wrapper for your numbers, HotcaffeinatedbeverageScript doesn't even recognise primitives without a full object wrapper!

**Write HotcaffeinatedbeverageScript**

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

Not sure when you can and can't use semicolons or newlines or...??? Not any longer: In HotcaffeinatedbeverageScript semicolons **and** newlines are _always_ required!

## Built-In Mathematical Functions

Stop trying to guess what shortened name to use, and just relax while you write out the full _long form_ of every name!

**Write HotcaffeinatedbeverageScript**
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

All global built-in functions are defined by their full un-shortened names. Confusing, error-prone constructs like nesting of function calls is not allowed.

**Write HotcaffeinatedbeverageScript**
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

Now you can switch into "pedant mode" with a simple statement at the top of your script file. Simply add the statement `use "pedant";`, sit back and enjoy the full, verbose completeness that has stopped JavaScript from being the the most beautiful language you've ever used!

**Write HotcaffeinatedbeverageScript**

```js
use "pedant";

variable s;
s = new String("beautiful");
variable c;
c = s.characterAtLocation(1);
```

**Compiles to JavaScript**
```js
var c="beautiful".charAt(1)
```


&copy; 1st April 2014, Michael J Mathews. All rights Reserved. 