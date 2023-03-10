# Activities

## Task 1

- Refer to the following link. Discuss how Binary Search Trees work:
  https://www.cs.usfca.edu/~galles/visualization/BST.html

> inserting a value checks if the value is smaller or larger than the root. If the vaue is smaller, it's placed on the left side of the root, if it's larger it's placed on the right side. Delete removes the first same value it finds (starting from the root). There's also search operation


## Task 2

- Refer to the following link.
  https://iq.opengenus.org/time-and-space-complexity-of-binary-search-tree/

Discuss the Time and Space complexity of Binary Search Tree (BST) operations (Searching, Insertion, Deletion) in the Best case, average case and worst case.

> Insertion 
    Best case (the root in empty): O(1) 
    Average: O(log N), where N is number of nodes. 
    Worst case: (root to the last node): O(n) where n is the number of nodes.

> Deletion 
    Best case: O(log N) where logN is the average height of the tree
    Average: O(log N)
    Worst case: O(n), where n is the height of the tree.

> Search 
    Best case (the value in the root node is the one we are searching): O(1) 
    Average: O(logN) where height becomes logN where N is number of nodes in a tree. 
    Worst case (root to the deepest leaf node):  O(n) where n is number of nodes present in a tree.

## Task 3

- Explain how the code in ./src/bst.cpp works. Refer to the following link:
  https://www.geeksforgeeks.org/introduction-to-binary-search-tree-data-structure-and-algorithm-tutorials/




## Task 4: Individual (at home)

- Refer to te following link. Explain how In-order Traversal is used to print a binary search tree.
  https://opendsa-server.cs.vt.edu/OpenDSA/Books/Everything/html/BinaryTreeTraversal.html#inorder-traversal

> First it prints (with recursive traversal) the left sub-tree, then the root and after that the right sub-tree

## Link(s)

- https://cpp.sh/
- https://www.geeksforgeeks.org/binary-search-tree-data-structure/
