Una lista de Python es un tipo de estructura de datos. Puede contener colecciones de cualquier tipo de datos e incluso una mezcla de tipos de datos.

- Aquí hay un ejemplo de una lista de cadenas en Python:

    ```python
    banda = ['paul', 'john', 'ringo', 'george']
    ```

- En Python, las listas se indexan desde `0`. Eso significa que puedes hablar sobre el elemento cero en una lista. En nuestro ejemplo, el elemento cero es `'paul'`.

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
