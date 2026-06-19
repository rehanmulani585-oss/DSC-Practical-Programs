# Data Structures Practical Exam Programs

# Practical Programs Included

1. Stack Implementation Using Array
2. Stack Implementation Using Linked List
3. Queue Implementation Using Array
4. Queue Implementation Using Linked List

---

# Introduction to Stack

A Stack is a linear data structure that follows the **LIFO (Last In First Out)** principle.

Example:

```text
Push 10
Push 20
Push 30

Pop → 30
Pop → 20
```

The last inserted element is deleted first.

## Stack Operations

### Push

Adds an element to the top of the stack.

### Pop

Removes an element from the top of the stack.

### Peek

Displays the top element without removing it.

### Display

Shows all stack elements.

---

# Stack Using Array

## Definition

In this implementation, stack elements are stored in a fixed-size array.

## Advantages

* Simple implementation
* Fast access using index

## Disadvantages

* Fixed size
* Stack Overflow may occur

## Algorithm for Push

1. Check if stack is full.
2. Increment top.
3. Insert element.

## Algorithm for Pop

1. Check if stack is empty.
2. Delete top element.
3. Decrement top.

---

# Stack Using Linked List

## Definition

In this implementation, each element is stored in a node.

## Advantages

* Dynamic memory allocation
* No fixed size limitation

## Disadvantages

* Extra memory required for pointers

## Algorithm for Push

1. Create a new node.
2. Store data.
3. Link node with top.
4. Update top.

## Algorithm for Pop

1. Check if stack is empty.
2. Store top node.
3. Move top to next node.
4. Delete old node.

---

# Introduction to Queue

A Queue is a linear data structure that follows the **FIFO (First In First Out)** principle.

Example:

```text
Enqueue 10
Enqueue 20
Enqueue 30

Dequeue → 10
Dequeue → 20
```

The first inserted element is deleted first.

---

# Queue Operations

### Enqueue

Insert an element at the rear.

### Dequeue

Delete an element from the front.

### Front

Displays first element.

### Display

Shows all queue elements.

---

# Queue Using Array

## Definition

Queue elements are stored in a fixed-size array.

## Advantages

* Easy implementation
* Fast access

## Disadvantages

* Fixed size
* Memory wastage possible

## Algorithm for Enqueue

1. Check if queue is full.
2. Insert element at rear.
3. Increment rear.

## Algorithm for Dequeue

1. Check if queue is empty.
2. Delete front element.
3. Increment front.

---

# Queue Using Linked List

## Definition

Queue elements are stored using linked list nodes.

## Advantages

* Dynamic memory allocation
* No fixed size restriction

## Disadvantages

* Additional memory required

## Algorithm for Enqueue

1. Create new node.
2. Insert node at rear.
3. Update rear pointer.

## Algorithm for Dequeue

1. Check if queue is empty.
2. Delete front node.
3. Move front pointer.

---

# Important Terms

## LIFO

Last In First Out

Used in Stack.

Example:

```text
Push 10
Push 20
Push 30

Pop = 30
```

## FIFO

First In First Out

Used in Queue.

Example:

```text
Enqueue 10
Enqueue 20
Enqueue 30

Dequeue = 10
```

## Overflow

Condition when insertion is attempted in a full data structure.

## Underflow

Condition when deletion is attempted in an empty data structure.

---

# Difference Between Stack and Queue

| Stack                              | Queue                                    |
| ---------------------------------- | ---------------------------------------- |
| LIFO                               | FIFO                                     |
| Push operation                     | Enqueue operation                        |
| Pop operation                      | Dequeue operation                        |
| Insertion and deletion at same end | Insertion and deletion at different ends |
| Uses Top pointer                   | Uses Front and Rear pointers             |

---

# Difference Between Array and Linked List

| Array                | Linked List               |
| -------------------- | ------------------------- |
| Fixed size           | Dynamic size              |
| Continuous memory    | Non-continuous memory     |
| Faster access        | Sequential access         |
| Memory may be wasted | Better memory utilization |

---

# Viva Questions and Answers

### 1. What is a Stack?

A Stack is a linear data structure that follows LIFO principle.

### 2. What is a Queue?

A Queue is a linear data structure that follows FIFO principle.

### 3. What is LIFO?

Last In First Out.

### 4. What is FIFO?

First In First Out.

### 5. What is Push?

Insertion operation in Stack.

### 6. What is Pop?

Deletion operation in Stack.

### 7. What is Enqueue?

Insertion operation in Queue.

### 8. What is Dequeue?

Deletion operation in Queue.

### 9. What is Stack Overflow?

Insertion into a full stack.

### 10. What is Stack Underflow?

Deletion from an empty stack.

### 11. What is Queue Overflow?

Insertion into a full queue.

### 12. What is Queue Underflow?

Deletion from an empty queue.

### 13. What is Top?

Top stores the index/address of the last inserted stack element.

### 14. What is Front?

Front points to the first element of the queue.

### 15. What is Rear?

Rear points to the last element of the queue.

### 16. Why use Linked List?

To overcome fixed size limitations of arrays.

### 17. Which is better: Array or Linked List?

Linked List is better when dynamic memory allocation is required.

### 18. What is Dynamic Memory Allocation?

Memory allocated during program execution using malloc().

### 19. Which header file is used for malloc()?

```c
#include <stdlib.h>
```

### 20. What is a Node?

A node contains data and a pointer to the next node.

### 21. Time Complexity of Push?

O(1)

### 22. Time Complexity of Pop?

O(1)

### 23. Time Complexity of Enqueue?

O(1)

### 24. Time Complexity of Dequeue?

O(1)

### 25. Why are Front and Rear needed in Queue?

To perform insertion and deletion efficiently.
