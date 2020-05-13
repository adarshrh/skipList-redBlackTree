# CS 6301.001. Implementation of data structures and algorithms
# Long Project 3: Skip Lists vs RBT

## Project Description
In this long project, implement skip lists and red-black tree, and then perform comparison
study of both the data structures over a large number (million) of add, contain, remove
operations.

### Skip Lists
Implement the following operations of skip lists.  
*  `add(x): Add a new element x to the list. If x already exists in the skiplist, replace it and return false. Otherwise, insert x into the skiplist and return true.`   
*  `contains(x): Does list contain x?`  
*  `remove(x): Remove x from the list. If successful, removed element is returned. Otherwise, return null.`  
*   `size(): Return the number of elements in the list.`  
*   `isEmpty(): Is the list empty?`  
*   `get(n): Return element at index n of list. First element is at index 0. Call either getLinear or getLog.`  
*   `getLinear(n): O(n) algorithm for get(n). (optional)`  
*  `getLog(n): O(log n) expected time algorithm for get(n).` 

### Red-black Tree
Extend BST to Red-Black Tree. Implement add and remove operations. Also, implement method verifyRBT() to verify whether
the tree satisfies all the properties of RB tree. 
 
  