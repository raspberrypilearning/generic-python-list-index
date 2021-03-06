A Python list is a type of data structure. It can hold collections of any data type, and even a mixture of data types.

- Here is an example of a list of strings in Python:

	```python
	band = ['paul', 'john', 'ringo', 'george']
	```

- In Python, lists are indexed from `0`. That means you can talk about the zeroth item in a list. In our example, the zeroth item is `'paul'`.

- To find the value of an item in a list, you simply type the name of the list followed by the index.

	```python
	>>> band[0]
	'paul'
	>>> band[2]
	'ringo'
	```
- To find the value of the last item in a Python list, you can also use the index `-1`.

	```python
	>>> band[3]
	'george'
	>>> band[-1]
	'george'
	```

- Moreover, you can find out value of the penultimate item using the index `-2`, and so on.

- Sometimes you might want to use a two-dimensional list, i.e. a list of lists. To find a specific item, you will have to provide two indices. Here is a list representing a noughts and crosses game:

	```python
	board = [['X', 'O', 'X'],
			 ['O', 'X', 'O'],
			 ['O', 'O', 'X']]
	```

- To find the central character in this list of lists, you would use `board[1][1]`.
