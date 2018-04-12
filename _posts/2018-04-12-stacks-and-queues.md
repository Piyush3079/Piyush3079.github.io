---
layout: post
title: Stacks and Queues
date: 2018-04-12 23:23:10 +0530
categories: jekyll update
---

### Stacks

#include <stack>

Defining a Stack in c++: `stack<int> s;`

Functions to be used with stacks

| FunctionName | Usage | Time Complexity |
| ------ | ------ | ------ |
| empty() | Used to check whether a stack is empty or nor not. It return bool. If empty it will return true otherwise it will return false | Constant |
| size() | It is used to find out the size of the stack. | Conatant
| top() | It is used to get the topmost element of the stack. The topmost element is the element which is pushed in the last or the topmost element in the stack | Constant |
| push() | It is used to push the element at the top of the stack. Pushing means adding the element in the stack | Constant |
| pop() | It is used to remove element from the top of the stack | Constant |
| swap() | It is used to swap the elements of two stacks. Eg swaping the elemnts of stacks foo and bar. | Constant |

