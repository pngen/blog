---
layout: post
title: 'Clarification'
categories: jekyll update
---

"It is important to view knowledge as sort of a semantic tree. Make sure you understand the fundamental principles, ie. the trunk and big branches, before you get into the leaves/details or there is nothing for them to hang on to." —Elon Musk

## Code Syntax

`=>` is used in associative array key value assignment. The double arrow operator, `=>`, is used as an access mechanism for arrays. What is on the left side will have a corresponding value of what is on the right side in the array context. This is used to set values of any acceptable type into a corresponding index of an array.

`->` is used to access an object method or property, ie. `$obj->method()`. The object operator, `->`, is used in object scope to access methods and properties of an object. It means that what is on the right of the operator is a member of the object, instantiated into the variable on the left side of the operator. Instantiated is the key term here.

To access a static method, use the class name, double colon `(::)`, and the method name:

```
ClassName::staticMethod();
```

A class is a template for objects. An object is an instance of a class.
