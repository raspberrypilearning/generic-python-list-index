Une liste Python est un type de structure de données. Elle peut contenir des collections de n'importe quel type de données, et même un mélange de types de données.

- Voici un exemple de liste de chaînes en Python :

    ```python
    groupe = ['paul', 'john', 'ringo', 'george']
    ```

- En Python, les listes sont indexées à partir de `0`. On peut donc parler d'élément zéro dans une liste. Dans notre exemple, l'élément zéro est `'paul'`.

- Pour trouver la valeur d'un élément dans une liste, il te suffit de taper le nom de la liste suivi de l'index.

    ```python
    >>> groupe[0]
    'paul'
    >>> groupe[2]
    'ringo'
    ```
- Pour trouver la valeur du dernier élément d'une liste Python, tu peux également utiliser l'index `-1`.

    ```python
    >>> groupe[3]
    'george'
    >>> groupe[-1]
    'george'
    ```

- Tu peux aussi connaître la valeur de l'avant-dernier élément en utilisant l'index `-2`, et ainsi de suite.

- Parfois, tu peux utiliser une liste à deux dimensions, c'est-à-dire une liste de listes. Pour trouver un élément spécifique, tu devras fournir deux index. Voici une liste représentant un jeu de morpion :

    ```python
    tableau = [['X', 'O', 'X'],
             ['O', 'X', 'O'],
             ['O', 'O', 'X']]
    ```

- Pour trouver le caractère central dans cette liste de listes, tu utiliseras `tableau[1][1]`.
