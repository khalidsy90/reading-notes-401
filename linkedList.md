# Linked List

**Terminology**

![linkedList](https://diego-shared-files.s3.eu-west-2.amazonaws.com/linked-list.jpeg)

- LinkeList : A data structure that have data and refers to the next node .

- Singly : refers to the number of references the node have the singly refers to the next node .

- doubly : have two references next and previous references .

- Nodes : items and contents of linkedlist that have data and reference lives inside it .

- Next : refers to the next item in the linked list .

- Head : is the first node in the linked list .

- Current : is the node that I am at .

![linkedList](https://habrastorage.org/webt/yc/dp/gm/ycdpgmbgyf2mzr_pymlwds1hauu.png)

What are Linked Lists?

- Linear data structures :

Linear data structure is modeling the data sequentially so to reach the last one you have to traverse each element . Non - linear data structres are non-sequential data representation .

- Memory management :
  The difference between arrays and linked lists is the way they use memory in our machine . Arrays use static memory distribution : That means when declared it will allocate memroy side by side int the same place of memory . LinkedLists uses dynamic memroy allocation : when created it will alocate memory scattered and might not be in the same place .

- Shapes and sizes :
  Singly Linked List : The simplest type aranges the data in sequential term we can traverse from the beginning to the end . Doubly Linked List : Have two references in each node the reference to the next and previous node more dynaymicall traversable . Circular Linked List : Have a tail node that points to the first node and each nodes is connected with another node even the last node is connected to the first one .

**Big O?**
![Big O](https://miro.medium.com/max/1400/1*3IlTLK_S0HmATuYQGxcbUA.png)

- Is the way to calculate how efficent an algorithm is .
- It's used to determine how effictive an algorithm is in the terms of time and space .
- Big O referes to an order and n refers to number of elements in the algorithm .

When to use list and when not?

![linkedList](https://miro.medium.com/max/1276/0*L4Zd7xE60u4VfDtv.png)

- Linked list is a good approach when adding or removing most elements .
- It's slow in searching and finding or modifying elements .
- Linked lists are faster to insert and delete elements .
  Slow to search in a linked list (an array is a better approach in this case ) .
- Have dynamic size to shrink or grow .
- Only allocates memory as required during the runtime .
- Finding an element requires traversal through the linked list .
