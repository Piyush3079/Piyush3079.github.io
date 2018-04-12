---
layout: post
title: Stacks and Queues
date: 2018-04-12 23:23:10 +0530
categories: Data-Structures
comments: true
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

## Priority Queues

`#include <queue>`

Defining priority queue in c++: `priority_queue<int> p;`

Priority queues are a type of container adaptors, specifically designed such that its first element is always the greatest of the elements it contains, according to some strict weak ordering criterion.

This context is similar to a heap, where elements can be inserted at any moment, and only the max heap element can be retrieved (the one at the top in the priority queue).

Functions to be used with priority queues

| FunctionName | Usage | Time Complexity |
| ------ | ------ | ------ |
| empty() | Used to check whether a priority queue is empty or nor not. It return bool. If empty it will return true otherwise it will return false | Constant |
| size() | It is used to find out the size of the priority queue. | Conatant
| top() | It is used to get the topmost element of the priority queue. The topmost element is the element which is pushed in the last or the topmost element in the priority queue | Constant |
| push() | It is used to push the element at the top of the priority queue. Pushing means adding the element in the priority queue | Constant |
| pop() | It is used to remove element from the top of the priority queue | Constant |
| swap() | It is used to swap the elements of two priority queues. Eg swaping the elemnts of priority queues foo and bar. | Constant |