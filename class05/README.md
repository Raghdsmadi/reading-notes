## Definition

- linked list is a list of connected nodes 
- a node consists of piece of data and a pointer that reference (points) to the next node
- the last node in the list reference to the value (null)
- each node can only see (reach) the next node
- the first node called the (Head)

---

## Linear vs Non-linear

- linear linked list: 

    it is a linked list where each node in it points only to one single other node, the one next to it (in front of it)

- non-linear linked list: 

    it is a linked where nodes in it can point to more than one other node

---

## Singly vs Doubly vs Circular

- singly linked list: 

    it is a list where each node only reference to the one in front of it till the last one that reference to (null)

- doubly linked list: 

    it is a list where each node reference to its both next and previous ones, the first one reference only to the next, and the last one reference to (null)

- circular linked list: 

    it is a list where each node only reference to the one in front of it till the last one that reference to one of the nodes to form a circle

---
Adding a Node
Adding O(1)
Order of operations is extremely important when it comes to working with a Linked List. What I mean by this is you must be careful that all references to each link/node is properly assigned.

An example can be with adding a node to a linked list. If we want to add a node with an O(1) efficiency, we have to replace the current Head of the linked list with the new node, without losing the reference to the next node in the list.

Here are the required steps to add a new node with an O(1) efficiency.