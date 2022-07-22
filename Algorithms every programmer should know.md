1. LINEAR SEARCH  
In computer science, a linear search or sequential search is a method for finding an element within a list. It sequentially checks each element of the list until a match is found or the whole list has been searched.
![alt text](https://navakz.github.io/Web/alg/ls.webp?raw=true)  
In linear search, we search for the target element in the list in sequential order one by one from the first element of the list to last.  
**Best Case:** Target Value is at the first position of the list  
**Worst Case:** Target Value is the last position of the list  
**When to use:**  
  >> When the list is unsorted  
  >> When the list is small  


2. BINARY SEARCH  
In computer science, binary search, also known as half-interval search, logarithmic search, or binary chop, is a search algorithm that finds the position of a target value within a sorted array. Binary search compares the target value to the middle element of the array. If they are not equal, the half in which the target cannot lie is eliminated and the search continues on the remaining half, again taking the middle element to compare to the target value.
![alt text](https://navakz.github.io/Web/alg/bs.webp?raw=true)  
In Binary Search, the list must be in some sorted order. We searched the target value by picking the value from the middle of the list and comparing it. If not matched, then if the target value is less than the middle element then the initial half will be drop otherwise the terminating half will be drop. The process will continue until we find the target value.  
**Best Case:** Target Value is at the middle position of the list  
**Worst Case:** Target Value is at either first or last position of the list  
**When to use:** 
  >> When the list is sorted  
  >> When the list is big  

3. DEPTH FIRST SEARCH(DFS)  
Depth-first search (DFS) is an algorithm for traversing or searching tree or graph data structures. The algorithm starts at the root node (selecting some arbitrary node as the root node in the case of a graph) and explores as far as possible along each branch before backtracking.  
![alt text](https://navakz.github.io/Web/alg/dfs.webp?raw=true)  
In DFS, we choose the root of the graph, tree, or data structure and explore every branch in order. When a branch is selected then it explores its all sub-branches before changing to a different branch.  
**Best Case:** Target Value is at the root position of the tree  
**Worst Case:** Target Value is at the tip of a sub-branch of the last ordered branch  
**When to use:**  
  >> When the tree is very wide  
  >> When the target value is located at the deep of the tree  

4. BREADTH FIRST SEARCH(BFS)  
Breadth-first search (BFS) is an algorithm for traversing or searching tree or graph data structures. It starts at the tree root (or some arbitrary node of a graph, sometimes referred to as a ‘search key’), and explores all of the neighbor nodes at the present depth prior to moving on to the nodes at the next depth level.  
![alt text](https://navakz.github.io/Web/alg/bfs.webp?raw=true)    
In BSF, same as in DFS, we choose the root node of graph, tree, or data structure. After node, we move to its all adjacent node and then to the next level that is all node adjacent to the branch.  
**Best Case:** Target Value is at the root position of the tree  
**Worst Case:** Target Value is at the tip of the longest branch of the tree  
**When to use:**   
  >> When the target value is not far from the root of the tree  
  >> When the tree is very deep, and the target value is rare.  
