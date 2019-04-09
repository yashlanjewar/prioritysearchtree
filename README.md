# prioritysearchtree
This project is based on Priority Search Tree.

Here, we have taken 2D coordinates as input and we are representing tree structure as output.

STEPS involved:
1)Root of tree will be the coordinate with max y value.

2)Then other coordinates are divided into 2 parts by a median value.

3)Left child of the node will be the coordinate with max y value and left to the median value.

4)Right child of the node will be the coordinate with max y value and right to the median value.

5)These steps goes on for every other coordinates.

 
For a given set of points S, we create a priority search tree as follows:
-If S is empty, we return NULL pointer and do not continue.
-The point P in S with the greatest Y-coordinate becomes the root R.
-If S°P is empty,R is also a leaf;we return R and do not continue.
-Recursively create a priority search tree on the lower half of S°P, let its root be the left child of R.
-Recursively create a priority search tree on the upper half of S°P, let its root be the right child of R.
