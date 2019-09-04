***Why would or wouldn't you want to use a singly linked list?

**They are more flexible than an array.

  -A linked list data structure is dynamic, it can grow and shrink in memory while a function is running.

  -Removing and adding to a list is easy, *wink* easier than shifting around an array.

  -Other data structures can are easier to use with linked lists. (think stacks and queues.)

**Memory and read access

  Memory useage can be a concern, they are bigger because of pointers.

  Only squential reading of nodes is possible.

  if unsorted, read times can be crazy

  Can't read backwards, unless doubly linked, but the trade off here is more
  memory is used


**The basic component of a singly linked list is a node. A basic node contains data and a reference. The reference is like an address to another node, it's link to the next node in the list. In a singly linked list, each node will only be able to point to the node next to it.

**The first node of a linked list is called the "head". When we refer to the head we are referring to a object where it's primary attribute is a reference pointed to the address of the first node in the linked list.

**A addition and removal of a node is revolves around the these links and pointers. If a node is not in this linked list, it's no longer part of the list and cannot be accessed through the list.
