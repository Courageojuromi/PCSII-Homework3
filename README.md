# PCSII-Homework3
This is a bench analysis 
The Heap function is a special case of balanced binary tree data structure where
the root-node key is compared with its children and arranged
accordingly.
Heaps are binary trees for which every parent node has a value less than or equal to any of its children. This implementation 
uses arrays for which heap[k] <= heap[2*k+1] and heap[k] <= heap[2*k+2] for all k, counting elements from zero. For the sake of comparison,
non-existing elements are considered to be infinite. The interesting property of a heap is that its smallest element is always the root, 
heap[0]. heapq.heapify(x)Transform list x into a heap, in-place, in linear time



#Binary trees organize data depending on the values of the
elements, Binary Trees are implemented using 2 pointers on each node.A binary tree is made of nodes, where each node contains a
"left" pointer, a "right" pointer, and a data element. ... The left and right pointers recursively point to smaller
"subtrees" on either side. A null pointer represents a binary tree with no elements -- the empty tree.
properties:
The left subtree of a node contains only nodes with keys lesser than the node’s key.
The right subtree of a node contains only nodes with keys greater than the node’s key.
The left and right subtree each must also be a binary search tree.

Bubble sort, sometimes referred to as sinking sort, is a simple sorting algorithm that repeatedly steps through the list, compares adjacent pairs and swaps them if they are in the wrong order. The pass through the list is repeated until the list is sorted. The algorithm, which is a comparison sort, is named for the way smaller or larger elements "bubble" to the top of the list. Although the algorithm is simple, it is too slow and impractical for most problems even when compared to insertion sort.[2] Bubble sort can be practical if the input is in mostly sorted order with some out-of-order elements nearly in position.

import matplotlib.pyplot as plt (this is indicate all of the graphs )
import time(to measure how fast each function works)
first thing first, we create an instance of the TimeTest object, which will take care of generating random arrays. After out Timetest object is instanciated, we run the function, which will take care of filling up our dataframe with all the values we need for our statistics.
we define the function of each alogrithms , for the quick sort ,bublbe sort , binarytree and python heap 
create the maximum and minimum.
when you implement the code you will see how the alogrithm works 

