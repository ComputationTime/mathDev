---
title: C++ in Depth. Part 1
description: 
tags: 
    - C++
categories:
    - Programming
date: 2023-08-26 00:00:00+0000
image: 
draft: true
weight: 1
toc: true
---

# C++

## Hello World

## Preprocessor
Anything that begins with a # is a preprocessor statement.

### include
The most common preprocessor statement you
might find is #include. All include does is copy the contents of the file specified and paste it where
the statement is found

Example:
#### main.cpp
```C++
int main() {
    return 0;
#include "closing_bracket.h"
```
#### include.h
```C++
}
```


## main function
Entry point to the code.

It is actually a special case where you do not have to return anything. It will assume you are returning
0.