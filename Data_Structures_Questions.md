Answer the following questions for each of the data structures you implemented as part of this project.

## Stack

1. What is the runtime complexity of `push` using a list?
constant
2. What is the runtime complexity of `push` using a linked list?
constant
3. What is the runtime complexity of `pop` using a list?
constant
4. What is the runtime complexity of `pop` using a linked list?
constant
5. What is the runtime complexity of `len` using a list?
linear
6. What is the runtime complexity of `len` using a linked list?
linear

Linked Lists work on O(n) While directly excplicit is O(1).

O(n) is Linear, while O(1) is Constant.

## Queue

1. What is the runtime complexity of `enqueue` using a list?
constant
2. What is the runtime complexity of `enqueue` using a linked list?
constant 
3. What is the runtime complexity of `dequeue` using a list?
constant
4. What is the runtime complexity of `dequeue` using a linked list?
constant 
5. What is the runtime complexity of `len` using a list?
linear
6. What is the runtime complexity of `len` using a linked list?
linear


## Doubly Linked List

1. What is the runtime complexity of `ListNode.insert_after`?
O(n log n)
2. What is the runtime complexity of `ListNode.insert_before`?
O(n log n)
3. What is the runtime complexity of `ListNode.delete`?
O(1)
4. What is the runtime complexity of `DoublyLinkedList.add_to_head`?
O(n log n)
5. What is the runtime complexity of `DoublyLinkedList.remove_from_head`?
O(n log n)
6. What is the runtime complexity of `DoublyLinkedList.add_to_tail`?
O(n)
7. What is the runtime complexity of `DoublyLinkedList.remove_from_tail`?
O(1)
8. What is the runtime complexity of `DoublyLinkedList.move_to_front`?
O(n log n)
9. What is the runtime complexity of `DoublyLinkedList.move_to_end`?
O(n log n)
10. What is the runtime complexity of `DoublyLinkedList.delete`?
O(n log n)
    a. Compare the runtime of the doubly linked list's `delete` method with the worst-case runtime of the JS `Array.splice` method. Which method generally performs better?
dll delete runs smoother, and a lot faster. Less alignment, just finds the node and nips it out, and re-aligns the list.
## Binary Search Tree

1. What is the runtime complexity of `insert`? 
O(log n)
2. What is the runtime complexity of `contains`?
O(log n)
3. What is the runtime complexity of `get_max`? 
O(log n)
4. What is the runtime complexity of `for_each`?
O(n)

## Heap

1. What is the runtime complexity of `_bubble_up`?

2. What is the runtime complexity of `_sift_down`?

3. What is the runtime complexity of `insert`?

4. What is the runtime complexity of `delete`?

5. What is the runtime complexity of `get_max`?
