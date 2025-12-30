- #concept [[Python]] Lists
- Definition
	- An ordered, mutable sequence type used to store collections of items.
- Example
	- ```python
	  nums = [1, 2, 3]
	  mixed = [1, "a", True]
	  ```
- Common operations
	- Indexing: `nums[0]`
	- slicing: `nums[1:]`
	- Append: `nums.append(4)`
	- Comprehensions:`[x * 2 for x in nums]`
	- When to use
		- When order matters and you might modify the collection.
- When should I use a list in Python? #card
  card-last-interval:: 4
  card-repeats:: 1
  card-ease-factor:: 2.6
  card-next-schedule:: 2026-01-03T03:47:08.122Z
  card-last-reviewed:: 2025-12-30T03:47:08.124Z
  card-last-score:: 5
	- When I need an ordered, mutable collection where items may change over time.
- public:: true