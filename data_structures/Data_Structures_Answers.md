Add your answers to the questions below.

1. What is the runtime complexity of your `depth_first_for_each` method?
The runtime compexity of `depth_first_for_each` method would be O(n) since we have to traverse all nodes

2. What is the space complexity of your `depth_first_for_each` function?
The space complexity of  `depth_first_for_each` would be O(n), since we're using a stack to keep track of the next nodes

3. What is the runtime complexity of your `breadth_first_for_each` method?
The runtime complexity of the `breadth_first_for_each` method O(n) since we have to traverse all nodes

4. What is the space complexity of your `breadth_first_for_each` method?
The space compexity of the `breadth_first_for_each` would be O(n), like at #2, but we use here a queue

5. What is the runtime complexity of your `heapsort` function?
We iterate through each item of the array, and then perform a log n insert. So the runtime complexity would be O(n log(n)). 

6. What is the space complexity of the `heapsort` function? Recall that your implementation should return a new array with the sorted data. What would be the space complexity if your function instead altered the input array?
Space complexity would be O(n), however if we did the heapsort inplace, the space complexity would be O(1).