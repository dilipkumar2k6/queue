# Circular Queue
https://leetcode.com/problems/design-circular-queue/
- Change above problem without constraints
# Queue using Stack
https://leetcode.com/problems/implement-queue-using-stacks/

# Monotonic Queue
## Overview
Unlike a standard FIFO (First-In-First-Out) queue, a monotonic queue maintains its elements in a strictly monotonic order. 
- Increasing: Elements get larger as you move from the front to the back of the queue.
- Decreasing: Elements get smaller as you move from the front to the back of the queue.
- Maintaining Order: The key aspect is ensuring the monotonic order during insertions. This might involve removing elements that violate the order before adding the new element.
## Application
- Monotonic queues are particularly useful in solving problems that involve finding the maximum or minimum value within a specific window as you process an array.
- Finding the maximum/minimum element in a sliding window: Given an array and a window size, find the maximum/minimum element within each window as you slide it across the array.
- Optimizations in Dynamic Programming: Monotonic queues can help improve efficiency in dynamic programming problems where you need to consider the maximum or minimum value within a certain range.

## Implementation
- While a standard queue can be adapted for monotonic queues, the most common and efficient implementation leverages a deque (double-ended queue) data structure.
- This allows for efficient insertion and deletion from both ends, which is crucial for maintaining the order.

## Problems

 https://leetcode.com/problems/sliding-window-maximum/

 https://leetcode.com/problems/number-of-visible-people-in-a-queue/description/

 https://leetcode.com/problems/online-stock-span/description/

 


# Stack using Queue
https://leetcode.com/problems/implement-stack-using-queues/

# Max Key API

# LRU Cache
https://leetcode.com/problems/lru-cache/

# LFU
https://leetcode.com/problems/lfu-cache/
