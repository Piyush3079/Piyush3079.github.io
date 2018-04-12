---
layout: post
title: Stacks and Queues
date: 2018-04-12 23:23:10 +0530
categories: data_structures
---

### Stacks

`#include <stack>`

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


## Queues

`#include <queue>`

Defining queue in c++: `queue<int> q;`

Functions to be used with queues

| FunctionName | Usage | Time Complexity |
| ------ | ------ | ------ |
| empty() | Used to check whether a queue is empty or nor not. It return bool. If empty it will return true otherwise it will return false | Constant |
| size() | It is used to find out the size of the queue. | Conatant
| front() | It is used to get the front element of the queue. The front element is the element which is pushed firstly or first element in the queue | Constant |
| back() | It is used to get the last element of the queue. The last element is the element which is pushed in the end or the last element in the queue | Constant |
| push() | It is used to push the element in the queue. Pushing means adding the element in the queue | Constant |
| pop() | Removes the next element in the queue, effectively reducing its size by one. The element removed is the "oldest" element in the queue whose value can be retrieved by calling member `queue::front`. | Constant |
| swap() | It is used to swap the elements of two queues. Eg swaping the elemnts of queues foo and bar. | Constant |