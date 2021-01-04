# Basic Data Structures

Stack, queue, priority queue, binary heap, single-linked list, double-linked list.

## Reference

[Problem Solving with Algorithms and Data Structures](https://runestone.academy/runestone/books/published/pythonds/index.html), by Miller and Ranum.

## Files

`Stack.py` Stack data structure using lists.

```python
"""
__init__()      Initializes the stack.
__repr_()       Returns the string representation of the stack.
is_empty()      Checks if the stack is empty.
push()          Adds one item to the top of the stack.
pop()           Returns and removes the item at the top of the stack.
peek()          Returns the item at the top of the stack.
reverse()       Reverses the stack.
clear()         Removes all items from the stack.
"""
```

`Queue.py` Queue data structure using lists.

```python
"""
__init__()      Initializes the priority queue.
__repr_()       Returns the string representation of the queue.
is_empty()      Checks if the queue is empty.
enqueue()       Adds one item to the back of the queue.
dequeue()       Returns and removes the item at the front of the queue.
peek()          Returns the item at the front of the queue.
reverse()       Reverses the queue.
clear()         Removes all items from the queue.
"""
```

`PriorityQueue.py` Priority queue (max/min) data structure using lists.

```python
"""
__init__()      Initializes the priority queue.
__repr_()       Returns the string representation of the priority queue.
is_empty()      Checks if the priority queue is empty.
put()           Adds one item to the priority queue.
get()           Returns and removes the item at the front of the priority queue.
peek()          Returns the item at the front of the priority queue.
reverse()       Reverses the priority queue (from min to max and viceversa).
clear()         Removes all items from the priority queue.
"""
```

`BinaryHeap.py` Binary heap (max/min) data structure using lists.

```python
"""
__init__()      Initializes the binary heap.
__repr_()       Returns the string representation of the binary heap.
is_empty()      Checks if the binary heap is empty.
swap_up()       Swaps an item up to preserve the binary heap property.
swap_down()     Swaps an item down to preserve the binary heap property.
put()           Adds one item to the binary heap.
get()           Returns and removes the item at the root of the binary heap.
peek()          Returns the item at the root of the binary heap.
reverse()       Reverses the binary heap (from min to max and viceversa).
clear()         Removes all items from the binary heap.
"""
```

`SingleLinkedList.py` Single-linked list and single-linked node data structures.

```python
"""
SLnode Class:
__init__()      Initializes the node.
__repr__()      Returns the string representation of the node.
set_data()      Set/replaces the content of the node.
get_data()      Returns the content of the node.
set_next()      Sets/replaces the linked next node.
get_next()      Returns the linked next node.

SLL Class:
__init__()      Initializes the SLL.
__repr__()      Returns the string representation of the SLL.
is_empty()      Checks if the SLL is empty or not.
nodes()         Returns a list with all items contained in the SLL.
add_front()     Adds a new item to the front of the SLL.
add_back()      Adds a new item to the back of the SLL.
add_before()    Adds a new item before a specified item of the SLL.
add_after()     Adds a new item after a specified item of the SLL.
change()        Changes a specified item of the SLL to another.
switch()        Switches two items of the SLL.
search()        Searches the SLL for a specified item.
remove()        Removes a specified item from the SLL.
pop()           Removes the node at the front of the SLL and returns its content.
peek()          Returns the content of the node at the front of the SLL.
reverse()       Reverses the SLL.
clear()         Removes all items from the SLL.
"""
```

`DoubleLinkedList.py` Double-linked list and double-linked node data structures.

```python
"""
DLnode Class:
__init__()      Initializes the node.
__repr__()      Returns the string representation of the node.
set_data()      Set/replaces the content of the node.
get_data()      Returns the content of the node.
set_next()      Sets/replaces the linked next node.
get_next()      Returns the linked next node.
set_previous()  Sets/replaces the linked previous node.
get_previous()  Returns the linked previous node.

DLL Class:
__init__()      Initializes the DLL.
__repr__()      Returns the string representation of the DLL.
is_empty()      Checks if the DLL is empty or not.
nodes()         Returns a list with all items contained in the DLL.
add_front()     Adds a new item to the front of the DLL.
add_back()      Adds a new item to the back of the DLL.
add_before()    Adds a new item before a specified item of the DLL.
add_after()     Adds a new item after a specified item of the DLL.
change()        Changes a specified item of the DLL to another item.
switch()        Switches two items of the DLL.
search()        Searches the DLL for a specified item.
remove()        Removes a specified item from the DLL.
pop()           Removes the node at the front of the DLL and returns its content.
peek()          Returns the content of the node at the front of the DLL.
reverse()       Reverses the DLL.
clear()         Removes all items from the DLL.
"""
```

## Examples and Notes

See each file.
