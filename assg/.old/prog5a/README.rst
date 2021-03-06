Homework 5
==========

Select up to 64 points worth of problems.  You may earn +N extra credit points
if you submit the assignment N<=4 days in advance of the due date.  

You must provide a Makefile and run.sh for the assignment [-64].

This assignment is an exploration of the linked list, stack, and queue classes.
They're good mental exercises. You'll see problems like these on your test. 

For this assignment, append all member functions of to the provided header file
for that class.  Implement all non-member functions in ``main.cpp``.  The
difference is important!  You cannot add to the public/private data of
``Node``, ``Stack``, or ``Queue``; you must keep them as such. 

**You must demonstrate all the functions you create in main.cpp!**  For
example, if you are doing list problems, load list with some numbers, such as
``2 3 5 7``. Then demonstrate your rotations, reversals, etc. by printing out
the list before/after the function call.  Label your output appropriately so
that it can be graded easily. 



1. Right-rotation of a linked list.
     [8]  Write a method ``Node *Node::rRotate()`` which right-rotates
     a list (the tail is moved to the head).


2. Left-rotation of a linked list.
     [8]  Write a method ``Node *Node::lRotate()`` which left-rotates
     a list (the head node is moved to the tail).


3. Reversal of a linked list.
     [8]  Write a method ``Node *Node::reverse()`` which reverses
     a list.


4. Cycle detection in a list.
     [16]  Write a method ``void Node::makeCycle()`` which points the tail of a
     list ot the head.  Write also ``bool Node::hasCycle()`` which returns true
     if there is a cycle in the list, false otherwise.  A **cycle** occurs when
     the same node is multiply by a traversal of the list.  You can find hints
     on-line for how to efficiently detect cycles.


5. Up-rotation of a stack.
     [8]  Write a function ``Stack upRotate(Stack s)`` which returns 
     the up-rotation of a stack (the top node is moved to the bottom).


6. Down-rotation of a stack.
     [8]  Write a function ``Stack downRotate(Stack s)`` which returns 
     the down-rotation of a stack (the top node is moved to the bottom).


7. Copy of a stack.
     [8]  Write a function ``Stack *copy(Stack *s)`` which returns 
     a copy of the stack.  You must not destroy the original.


8. Check if a stack is a palindrome.
     [16]  Write a function ``bool isPalindrome(Stack s)`` which returns true
     if the stack is a palindrome (values are reflected across the middle).


9. Reversal of a queue.
     [16] Write a function ``Queue *reverse(Queue *q)`` which returns 
     the reverse of a queue.


10. N-number queue rotations.
     [16] Write methods ``void Queue::lRotate(int n)`` and ``void
     Queue::rRotate(int n)`` which rotate the queue by n-number elements.


11. Check if queue is rotation.
     [16] Write a function ``bool isRotation(Queue *p, Queue *q)`` to
     tell if ``p`` is a rotation of ``q``.  The integrity of the queues
     should be maintained on return of the function.

