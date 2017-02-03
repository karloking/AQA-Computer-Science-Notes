#Stacks

>Be able to describe and apply the following
>operations:
>* push
>* pop
>* peek or top
>* test for empty stack
>* test for stack full.

**Stacks:** Data type base on Last In First Out principle, where elements recently pushed to the stack is popped first, elements pushed first would be popped last.

##Operations of a Stack

A stack is an abstract data type (ADT) that supports
two main methods:
```
push(o): Inserts object onto top of stack
Input: Object; Output: none
```
```
pop(): Removes the top object of stack andreturns it; if stack is empty an error occurs
Input: none; Output: Object
```

The following support methods should also be
defined:
```
- size(): Returns the number of objects in stack
Input: none; Output: integer
```
```
- isEmpty(): Return a boolean indicating if stack is empty.
Input: none; Output: boolean
```
```
- top(): return the top object of the stack,without removing it; if the stack is empty an error occurs.
Input: none; Output: Object
```

##Pseudocode
```scala
STACK-EMPTY(S)
if top[S] = 0
return true
else return false

PUSH(S, x)
top[S] <- top[S] + 1
S[top[S]] <- x

POP(S)
if STACK-EMPTY(S)
then error ”underflow”
else top[S] <- top[S] – 1
return S[top[S] + 1]
```
