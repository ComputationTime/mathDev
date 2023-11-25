---
title: C++ Plan
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

```C++
#include<iostream>

int main() {
    std::cout << "Hello, world!\n";
    return 0;
}
```

### Preprocessor
Anything that begins with a # is a preprocessor statement.

#### include
The most common preprocessor statement you
might find is #include. All include does is copy the contents of the file specified and paste it where
the statement is found

Example:
##### main.cpp
```C++
int main() {
    return 0;
#include "closing_bracket.h"
```
##### include.h
```C++
}
```
### Standard Library
### main function
Entry point to the code.

It is actually a special case where you do not have to return anything. It will assume you are returning
0.

## Multiple Files
### Linker

## From C++ to Binary
### Preprocessor
### Object - Translation Units
### Linker
### LLVM, GNU, etc
### Assembly
### Machine Code

## Preprocessor statements
### include
### define
### if
### ifdef
### pragma

## Optimization levels - Debug, Prod etc

## Linker

## Header Files

## Variables
### int
### unsigned
### Characters are just numbers
### float
### double
### bool
### sizeof




