---
layout: post
title:  "Welcome to the galaxy of the well-developed source code!"
date:   2019-12-19 14:18:08 +0100
categories: random
---

_“Any fool can write code that a computer can understand. Good programmers write code that humans can understand.”—Martin Fowler_

Below are a few best practices we think you can benefit from when you start implementing your task 

0. Write clean code: https://simpleprogrammer.com/clean-code-principles-better-programmer/
1. Follow KISS
2. Always using your organisation code formatter
3. Follow the coding rules for your programming language, for example: http://isocpp.github.io/CppCoreGuidelines/CppCoreGuidelines
4. Strive for TDD: writing tests and developing against them - only then you have understood the subject
5. Updating the build script and building locally before comiting
6. Keeping the commit message in your organisation's format

Code example test: 
```cpp
my_value_type& operator=(my_value_type other)
{
    this->swap(other);
    return *this;
}
```

```python
def merge_dictionaries(a, b):
   return {**a, **b}


a = { 'x': 1, 'y': 2}
b = { 'y': 3, 'z': 4}
print(merge_dictionaries(a, b)) # {'y': 3, 'x': 1, 'z': 4}
```




