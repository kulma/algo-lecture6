# Activities

## Task 1

- Refer to the following link. Discuss how Min Heap data structure works:
  https://www.cs.usfca.edu/~galles/visualization/Heap.html

  > It's a binary tree where the root node has always the smallest value, so when new values are added to the heap the smaller values keep moving up to the root. 

## Task 2

- Refer to the following link.
  https://iq.opengenus.org/time-and-space-complexity-of-heap/

Discuss the Time and Space Complexity of Heap data structure operations, in the Best case, average case and worst case.

> Insertion: \
    Best Case (one check and no shift): O(1) \
    Average Case: O(logN) \
    Worst Case (if the inserted value had to be shifted until we reached the root): O(logN)
    

> Deletion: \
    Best Case (no shifting): O(1) \
    Average Case: O(logN) \
    Worst Case (downshift till the bottom of the Heap): O(logN)
   

> Search: \
    Best Case (root node is the one): O(1) \
    Average Case: O(N) \
    Worst Case (last Node of the Heap): O(N)
    


## Task 3

- Explain how the code in ./src/priority-queue.cpp works. Refer to the following link:
  https://www.geeksforgeeks.org/priority-queue-using-binary-heap/



## Task 4: Individual (at home)

- Explain how the code in ./src/heap.cpp works. Refer to the following link:
  https://www.geeksforgeeks.org/binary-heap/



## Link(s)

- https://cpp.sh/
- https://www.geeksforgeeks.org/array-representation-of-binary-heap/
