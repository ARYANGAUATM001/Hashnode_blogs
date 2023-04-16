---
title: "Tree Data Structure - Explanation And Implementation"
seoTitle: "tree data structure implementation"
datePublished: Tue Mar 28 2023 12:44:39 GMT+0000 (Coordinated Universal Time)
cuid: clfs92r9502ipx0nvg5nohqe9
slug: tree-data-structure-explanation-and-implementation
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1680008583862/52df72e5-8d0e-4ebf-b120-e207d31c61f4.png
tags: tutorial, technology, python, data-structures, data-structure-and-algorithms

---

A **tree data structure** is a hierarchical structure that is used to represent and organize data in a way that is easy to navigate and search. It is a collection of nodes that are connected by edges and has a hierarchical relationship between the nodes.

### Representation of Tree Data Structure --&gt;

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1679993169175/12e3a623-60b4-4f51-a97b-f70c5eb3cc73.png align="center")

Tree is considered a non-linear data structure. The data in a tree are not stored in a sequential manner i.e, they are not stored linearly. Instead, they are arranged on multiple levels or we can say it is a hierarchical structure. For this reason, the tree is considered to be a non-linear data structure.

### **BINARY TREE --&gt;**

Binary Tree is defined as a tree data structure where each node has at most 2 children. Since each element in a binary tree can have only 2 children, we typically name them the left and right child.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1679993427257/decb15b9-0422-4ff3-b8ca-f7ad5ffb3314.png align="center")

### **BINARY TREE REPRESENTATION --&gt;**

A Binary tree is represented by a pointer to the topmost node (commonly known as the “root”) of the tree. If the tree is empty, then the value of the root is NULL. Each node of a Binary Tree contains the following parts :

1\. Data

2\. Pointer to left child

3\. Pointer to right child

### **IMPLEMENTATION OF TREE(BINARY TREE) IN PYTHON -&gt;**

We create a tree data structure in python by using the concept of node discussed earlier. We designate one node as root node and then add more nodes as child nodes.

### **CREATING ROOT --&gt;**

We just create a Node class and add assign a value to the node. This becomes tree with only a root node.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1679994136167/eabbf55d-c44f-4da5-946e-613bb89df8cc.png align="center")

When the above code executes it gives the result as shown:

25

### INSERTING INTO TREE --&gt;

To insert into a tree we use the same node class created above and add an insert method to it. Here we are creating a Binary Search Tree.

A binary search tree is a rooted binary tree in which the nodes are arranged in strict total order in which the nodes with keys greater than any particular node is stored on the right sub-trees and the ones with equal to or less than are stored on the left sub-tree satisfying the binary search property.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1679995800785/00068d8d-5055-41c0-9ceb-80693b878ac5.png align="center")

The insert method compares the value of the node to the parent node and decides to add it as a left node or a right node. Finally, the printTree method is used to print the tree.

The code when executes gives the result --&gt;

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1679995863888/69e3e5fc-8064-4943-a5ee-b94f7da72a57.png align="center")

The output result is given as :

\[5,12,45,58,100\]

In this way we can implement a Tree Data structure in Python.