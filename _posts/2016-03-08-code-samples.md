---
layout: post
title: Code Samples
subtitle: Using Hugo or Pygments
date: 2016-03-08
tags: [example, code]
excerpt_separator: <!--more-->
---
The following are two code samples using syntax highlighting.

<!--more-->

The following is a code sample using triple backticks ( ``` ) code fencing provided in Hugo. This is client side highlighting and does not require any special installation.

```javascript
var num1, num2, sum
num1 = prompt("Enter first number")
num2 = prompt("Enter second number")
sum = parseInt(num1) + parseInt(num2) // "+" means "add"
alert("Sum = " + sum)  // "+" means combine into a string
```


The following is a code sample using the "highlight" shortcode provided in Hugo. This is server side highlighting and requires Python and Pygments to be installed.

{% highlight javascript %}
var num1, num2, sum
num1 = prompt("Enter first number")
num2 = prompt("Enter second number")
sum = parseInt(num1) + parseInt(num2) // "+" means "add"
alert("Sum = " + sum)  // "+" means combine into a string
{% endhighlight %}


And here is the same code with line numbers:

{% highlight javascript linenos %}
var num1, num2, sum
num1 = prompt("Enter first number")
num2 = prompt("Enter second number")
sum = parseInt(num1) + parseInt(num2) // "+" means "add"
alert("Sum = " + sum)  // "+" means combine into a string
{% endhighlight %}
