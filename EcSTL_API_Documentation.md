# EcSTL Library Documentation

## Overview

EcSTL is a C++ Standard Template Library (STL) implementation that provides a comprehensive set of containers, algorithms, iterators, and utilities. This library implements the core STL components with additional optimizations and features.

## Table of Contents

1. [Containers](#containers)
   - [Vector](#vector)
   - [List](#list)
   - [Deque](#deque)
   - [String](#string)
   - [Stack](#stack)
   - [Queue](#queue)
   - [Priority Queue](#priority-queue)
   - [Hash Table](#hash-table)
   - [Unordered Map](#unordered-map)
   - [Unordered Set](#unordered-set)
   - [Red-Black Tree](#red-black-tree)

2. [Iterators](#iterators)
   - [Iterator Categories](#iterator-categories)
   - [Iterator Traits](#iterator-traits)
   - [Reverse Iterator](#reverse-iterator)

3. [Algorithms](#algorithms)
   - [Non-modifying Algorithms](#non-modifying-algorithms)
   - [Modifying Algorithms](#modifying-algorithms)
   - [Sorting Algorithms](#sorting-algorithms)

4. [Function Objects](#function-objects)
   - [Arithmetic Function Objects](#arithmetic-function-objects)
   - [Comparison Function Objects](#comparison-function-objects)
   - [Logical Function Objects](#logical-function-objects)

5. [Memory Management](#memory-management)
   - [Allocator](#allocator)
   - [Construction/Destruction](#constructiondestruction)

6. [Utility Components](#utility-components)
   - [Pair](#pair)
   - [Type Traits](#type-traits)

## Namespace

All components are defined in the `EcSTL` namespace.

```cpp
using namespace EcSTL;
```

## Basic Usage Example

```cpp
#include "vector.h"
#include "algorithm.h"
#include "string.h"

int main() {
    // Create a vector
    EcSTL::vector<int> vec = {1, 2, 3, 4, 5};
    
    // Use algorithms
    EcSTL::sort(vec.begin(), vec.end());
    
    // Create a string
    EcSTL::string str = "Hello, EcSTL!";
    
    return 0;
}
```