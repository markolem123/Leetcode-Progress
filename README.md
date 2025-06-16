**VERSION 1**
- Passes sample test cases but Timeline exceeds upon submission
- This is due to the "in" on line 5. "if i in newList" takes O(n) 
- If nums has n elements, and all elements are unique, this line runs roughly 1 + 2 + ... + (n-1) = O(n^2) times.
- Potential fix: using set instead of a list

**VERSION 2**
- Used set instead of list. Only changed 2 lines
- Simple fix and works! Beats 94.4%
- _SET VS LIST_
   - set is a hash table so it is O(1) where it automatically will find what you're looking for
   - list is O(n) because it has to go through the actual list so worst case it goes through the whole thing
