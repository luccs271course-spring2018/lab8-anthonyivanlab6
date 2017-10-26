# Questions

**Question 1**

*(Why does `FixedArrayQueue` require an explicit constructor?)*

- The size of the ArrayQueue has to be set during creation (as done through the argument).

**Question 2**

*(What happens when you offer an item to a full `FixedArrayQueue`?)*

- It returns `false`. 

**Question 3**

*(What happens when you poll an empty `FixedArrayQueue`?)*

- It returns `null`.

**Question 4**

*(What is the time and (extra) space complexity of each of the `FixedArrayQueue` methods?)*

- Offer, Peek, Poll, isEmpty, Size = O(1)
- asList = O(n)