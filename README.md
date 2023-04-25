# stack

A stack is a linear data structure in which the insertion of a new element and removal of an existing element 
takes place at the same end represented as the top of the stack.

In order to make manipulations in a stack, there are certain operations provided to us.
push() to insert an element into the stack
pop() to remove an element from the stack
top() Returns the top element of the stack.
isEmpty() returns true if stack is empty else false.
size() returns the size of stack.

Types of Stacks:
Fixed Size Stack: As the name suggests, a fixed size stack has a fixed size and cannot grow or shrink dynamically.
If the stack is full and an attempt is made to add an element to it, an overflow error occurs.
If the stack is empty and an attempt is made to remove an element from it, an underflow error occurs.
Dynamic Size Stack: A dynamic size stack can grow or shrink dynamically.
When the stack is full, it automatically increases its size to accommodate the new element, and when the stack is empty, it decreases its size. 
This type of stack is implemented using a linked list, as it allows for easy resizing of the stack.
