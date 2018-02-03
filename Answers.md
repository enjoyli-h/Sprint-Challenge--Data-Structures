1. What are the order of insertions/removals for the following data structures? 
Stack - Insertion - To add something you have to push it on to the stack and increment the size of the stack.
Removal - Since a stack follows LIFO, we pop the most recently added data. Use the stacks current size to last data added, you delete it with the pop method, and decrement the stack size once. Finally, return the deleted data.
Queue - Insertion - We use enqueue(data) to add data. Use the newest index as a key of storage and use the data being added as the value of that key. Then increment newestIndex by 1.
Removal - Dequeue - This is FIFO, so we are going to remove the oldestIndex in the queue and increment the oldestIndex by one.  

2. What is the retreival time complexity for the following data structures? 
Linked List - 0(n)
Hash Table - 0(1)
Binary Search Trees - 0(log(n))

3. What are some advantages to using a Hash Tables over an array in JavaScript? Hashtables are more efficient. In an array, you may not know where the item is that your looking for and you have to search through each item linearly. This takes as much time as items in the array. Hashtags have a constant time retrieval.