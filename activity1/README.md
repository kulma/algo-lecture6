# Activities

## Task 1: Tree Definition

- Answer at least 5 questions from the following link. Make sure you write the question as well as the answer.
  https://opendsa-server.cs.vt.edu/OpenDSA/Exercises/Binary/DefSumm.html
> Group 6 answers:
> What is the minimum number of nodes in a full binary tree with height 3? 

7

> Select the one true statement.

- [ ] Every binary tree is either complete or full

- [ ] Every complete binary tree is also a full binary tree

- [ ] Every full binary tree is also a complete binary tree

- [ ] No binary tree is both complete and full

- [x] None of the above

> What is the minimum number of nodes in a complete binary tree with height 3?

8

> Suppose T is a binary tree with 14 nodes. What is the minimum possible height of T?

3

> What is the minimum number of internal nodes in a binary tree with 8 nodes?

4


## Task 2

- Explain how the code in ./src/bt.cpp works. Refer to the following link:
  https://www.geeksforgeeks.org/binary-tree-array-implementation/
> The root function sets the character given as a parameter as the root node, that is the 0th element of the array. The set_left function takes a character and an integer as parameters, and uses the integer to determine which node is the parent node of the new node. If it doesn't exist, it raises an error. If it does, the character is added to index $(parent\cdot2)+1$. The same goes for set_right, except the character is added to index $(parent\cdot2)+2$. The print_tree function prints the array out, replacing null characters with hyphens.

## Task 3: Tree Traversal

Refer to te following links. Discuss the difference between the different ways binary trees can be traversed.

- [Pre-order Traversal](https://opendsa-server.cs.vt.edu/OpenDSA/AV/Binary/btTravPreorderPRO.html)
- [Post-order Traversal](https://opendsa-server.cs.vt.edu/OpenDSA/AV/Binary/btTravPostorderPRO.html)
- [In-order Traversal](https://opendsa-server.cs.vt.edu/OpenDSA/AV/Binary/btTravInorderPRO.html)

## Task 4: Individual (at home)

- Answer at least 5 questions from the following link. Make sure you write the question as well as the answer.
  https://opendsa-server.cs.vt.edu/OpenDSA/Exercises/Binary/TravSumm.html
- Answer at least 5 questions from the following link. Make sure you write the question as well as the answer.
  https://opendsa-server.cs.vt.edu/OpenDSA/Exercises/Binary/Treeprobs.html

## Links

- https://cpp.sh/
- https://opendsa-server.cs.vt.edu/OpenDSA/Books/Everything/html/BinaryTree.html
- https://opendsa-server.cs.vt.edu/OpenDSA/Books/Everything/html/BinaryTreeTraversal.html
