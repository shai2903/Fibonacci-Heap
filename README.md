# Fibonacci-Heap
Implementation of Fibonacci heap


**insert** :
Creates a node (of type HeapNode) which contains the given key, and insert it into the heap 
Time complexity(Average) :O(1)


**deleteMin** :
Delete the node containing the minimum key.
Time complexity(Average) :O(log n)


**findMin** :
 Return the node of the heap whose key is minimal.
Time complexity(WC) :O(1)

**meld(heap2)** :
Meld current heap with heap2
Time complexity(Average) :O(1)


**countersRep()** :
Return a counters array, where the value of the i-th entry is the number of
trees of order i in the heap.
Time complexity(WC) :O(n)

**decreaseKey** :
The function decreases the key of the node x by delta. The structure of the
heap should be updated to reflect this chage (for example, the cascading cuts
procedure should be applied if needed).
Time complexity(Average) :O(1)

**potential** :
This function returns the current potential of the heap, which is: Potential = #trees + 2*#marked
Time complexity(WC) :O(1)

**delete (x)** : 
 Deletes the node x from the heap.
Time complexity(Average) :O(log n)




