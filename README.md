A priority queue is implemented using a heap data structure, which is a complete binary tree with the following properties:

Max Heap Property: In a max heap, for any given node i, the value of the node is greater than or equal to the values of its child nodes.
Complete Binary Tree Property: A complete binary tree is a binary tree in which all levels are completely filled, except possibly for the last level, which is filled from left to right.
When elements are inserted into a priority queue (implemented as a max heap), the heap property is maintained, ensuring that the largest element is always at the top (root) of the heap.
BY DEFAULT PRIORITY QUEUE IS MAX HEAP.
priority_queue<int, vector<int>, greater<int>>. The greater<int> comparison function ensures that the smallest element is always at the top of the heap.
