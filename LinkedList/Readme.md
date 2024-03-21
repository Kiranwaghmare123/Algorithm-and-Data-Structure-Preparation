# Linked List 
    Quick summary: a linear collection of elements ordered by links instead of physical placement in memory.

### Important facts:
    Each element is called a node.
    The first node is called the head.
    The last node is called the tail.
    Nodes are sequential. Each node stores a reference (pointer) to one or more adjacent nodes:
    In a singly linked list, each node stores a reference to the next node.
    In a doubly linked list, each node stores references to both the next and the previous nodes. This enables traversing a list backwards.
    In a circularly linked list, the tail stores a reference to the head.
    Stacks and queues are usually implemented using linked lists, and less often using arrays.

### Pros:
    Optimized for fast operations on both ends, which ensures constant time insertion and deletion.
    Flexible capacity. Doesn't require setting initial capacity, can be expanded indefinitely.
### Cons:
    Costly access and search.
    Linked list nodes don't occupy continuous memory locations, which makes iterating a linked list somewhat slower than iterating an array.

### Notable uses:
    Implementation of stacks, queues, and graphs.

### Time complexity (worst case):
    Access: O(n)
    Search: O(n)
    Insertion: O(1)
    Deletion: O(1)
