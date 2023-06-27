# pyrallel-change-kata

A repository to practice parallel change kata in
python. [Parallel change, also known as expand and contract](https://martinfowler.com/bliki/ParallelChange.html), is a
pattern to implement backward-incompatible changes to an interface in a safe manner, by breaking the change into three
distinct phases: expand, migrate, and contract.

This code repository has been initiated from this [one](https://github.com/unclejamal/parallel-change).

## Parallel Change Kata

### What is Parallel Change?

Also known as Expand and Contract, this is a pattern that can be used to evolve a software design by introducing
backwards compatible changes without breaking clients of the existing code. It involves three steps:

1. expand (add the new element - class, method, variable);
2. migrate (clients of the existing element to use the new one introduced in step 1); and
3. contract (remove the old element - class, method, variable)

A more detailed discussion, with examples, may be found in
[Danilo Sato's article on Parallel Change](https://martinfowler.com/bliki/ParallelChange.html).

## Your Task

Using Parallel Change, modify the class `ShoppingCart` to handle multiple items instead of a single one.
Tests have already been written.

## Rules

The tests must not be red at any time. No compile-errors, no failures. (The only exception is for a few seconds while
you write a single line of code.)
