**VERSION 1**
- Passes sample test cases but Timeline exceeds upon submission
- This is due to the "in" on line 5. "if i in newList" takes O(n) 
- If nums has n elements, and all elements are unique, this line runs roughly 1 + 2 + ... + (n-1) = O(n^2) times.
- Potential fix: using set instead of a list
