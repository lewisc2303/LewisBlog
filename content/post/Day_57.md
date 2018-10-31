---
title: "Day 57"
date: 2018-10-31
tags: []
draft: true
---

What is strict and lazy operator implementation
e.g. && and (+) are strict or lazy

Haskell is a lazy language?

strictness, non-strictness and lazy evaluation

left associativity

foldr or fold'. Don't usually use foldl because of lazy evaluation. doesn't evaluate until the whole spine has been evaluated, which for very big lists can cause a stack stack-overflow

all folds evaluate the spine first and then the values except fold'
