Una lista de Python es un tipo de estructura de datos. Puede contener colecciones de cualquier tipo de datos e incluso una mezcla de tipos de datos.

- Aquí hay un ejemplo de una lista de cadenas en Python:

    ```python
    banda = ['paul', 'john', 'ringo', 'george']
    ```

- En Python, las listas se indexan desde `0`. Eso significa que puedes hablar sobre el elemento cero en una lista. En nuestro ejemplo, el elemento cero es `'paul'`.

- Para encontrar el valor de un elemento en una lista, simplemente escribe el nombre de la lista seguido por el índice.

    ```python
    >>> banda[0]
    'paul'
    >>> banda[2]
    'ringo'
    ```
- Para encontrar el valor del último elemento en una lista de Python, también puedes usar el índice `-1`.

    ```python
    >>> banda[3]
    'george'
    >>> banda[-1]
    'george'
    ```

- Más aún, puedes encontrar el valor del penúltimo elemento usando el índice `-2`, y así sucesivamente.

- A veces, tal vez quieras usar una lista de dos dimensiones, es decir, una lista de listas. Para encontrar un elemento específico, tendrás que proporcionar dos índices. Here is a list representing a noughts and crosses game:

    ```python
    tablero = [['X', 'O', 'X'],
             ['O', 'X', 'O'],
             ['O', 'O', 'X']]
    ```

- Para encontrar el carácter central en esta lista de listas, tendrás que usar `tablero[1][1]`.
