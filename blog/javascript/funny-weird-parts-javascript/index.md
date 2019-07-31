---
title: The funny-weird parts in JavaScript!!!
date: "2019-07-20T17:20:00.284Z"
description: "The purpose of this article is to mockery some funny aspects on our every day routine."
tags: [JavaScript]
---

![javascript](markus-spiske-xekxE_VR0Ec-unsplash.jpg)

In this article I will try to demonstrate some funny / weird parts in JavaScript. Besides its flaws we are using it and we are loving it! (most of the time!)

<br/><br/>
Let’s start!!

```javascript
true + true
```

what do we expect from the above line of code??
Anything you are thinking right now is wrong!! Unless you had known the answer already! :)

The correct answer is: **2**

wait what??

Now that we understand the craziness of this article let’s continue!

## Something with strings!!

```javascript
“This is a test string” instanceof String  //RESULT: fasle
```

OK, probably I can live with this!!

But wait…

```javascript
typeof “This is a test string”  //RESULT: string
```

ohh nooo!!!!

## Continuing with numbers!!

> JavaScript loves numbers so much!!

So if you write the number `9999999999999999`, JavaScript thinks that is the same as `10000000000000000` !!! Smart right??

Let’s make a simple addition floating point numbers

```javascript
0.1 + 0.2 //POSIBLE RESULT: 0.3
```

The above is right for you!! Not for JavaScript!!! For the JavaScript the result is 0.30000000000000004 !

> Yes, JavaScript says “I am better in maths than you”!

```javascript
3 > 2 > 1
```

You are guessing wrong again!!
The right answer is not **true**!!
But **false**!

Now your brain fights to recognize reality!!

Next one

```javascript
“2” + 1   // RESULT: 21
“2” — 1   // RESULT: 1
```

Boom!! After that your brain is losing the fight!

## A little bit about falsy values

```javascript
typeof NaN //RESULT: Number
```

OK, I will pretend that is right!

```javascript
NaN instanceof Number // POSSIBLE RESULT: true
```

Nope!! It is not!! It’s **false**!!

And something that I just leave here

```javascript
typeof null //RESULT: object
```

No comment here!!

## Final chapter

Arrays and objects. After this I will leave you in peace

```javascript
[] + []   //RESULT: “”
[] + {}   //RESULT: “[object Object]”
```

Based on the above, are you thinking `[object Object]`? Nope

```javascript
{
}
;+[] //RESULT: 0
```

The purpose of this article is to mock some funny aspects on our every day routine. However JavaScript is one of the most usable languages. Millions developers use it every day!!
