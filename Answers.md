1. What are the order of insertions/removals for the following data structures?
   - **Stack**
   - **Queue**

   - Stacks follow a LIFO order, meaning the last inserted is the first removed. This is similar to a stack of dishes in a cabniet the last dish piled on the stack is the first dish removed from the stack.
   - Queues follow a FIFO order, meaning first inserted is the first removed. This is similar to a line at the store, where the first person to get in line is also the first person to be checked out.
2. What is the retreival time complexity for the following data structures?
   - **Linked List**
   - **Hash Table**
   - **Binary Search Trees**
   - Linked Lists have a Linear time complexity, represented as O(n) in Big O notation. This means in the worst case senario the element we are searching for is the very last element. which means you might have to end up iterating over the entire array for retreival. The n stands for the number of elements that you would have to iterate over.The number of steps here is directly equal to the size (n).
   - Hash-Tables have a near Constant Time complexity, depending on certain design decisions. Constant time complexity is represented as O(1) in Big O notation. This means the execution time is independant from the number of inputs recieved. It only takes a single step to accomplish the task, reguardless on the input.
   - Binary Search Trees have a Logarithmic Time Complexity, represented as O(logn) in Big O notation. with size n the number of steps is decreased with each step.
2. What are some advantages to using a Hash Tables over an array in JavaScript?
- One advantage of using a hash Table over an array in Javascript is the time complexity. It is usually faster to serch a hash table then an array because in the worst case scenario of using an array you woud be iterating over every element to find what you are serching for. Hash tables have near constant time complexity, so lookup time is almost instant, and you dont have to iterate over an entire array.