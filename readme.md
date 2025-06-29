A deque is a double-ended queue that allows enqueue and dequeue operations from both the ends.

Given a deque and q queries. The task is to perform some operation on dequeue according to the queries as given below:
1. pb: query to push back the element x.
2. pf: query to push element x(given with query) to the front of the deque.
3. pp_b(): query to delete element from the back of the deque.
4. f: query to return a front element from the deque.

Examples:
```
Input: queries = [[ pf 5 ],[ pf 10 ],[ pb 6 ],[ f ],[ pp_b ]]
Output: 10
Explanation: 
1. After push front deque will be [5]
2. After push front deque will be [10, 5]
3. After push back deque will be [10, 5, 6]
4. Return front element which is 10
5. After pop back deque will be [10, 5]
```
```
Input: queries = [[ pf 5 ],[ f ]]
Output: 5 
Explanation:
1. After push front deque will be [5]
2. Return front element which is 5
```
