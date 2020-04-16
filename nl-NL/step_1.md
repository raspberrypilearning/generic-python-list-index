Een Python-lijst is een type gegevensstructuur. Het kan verzamelingen van elk gegevenstype bevatten, en zelfs een combinatie van gegevenstypes.

- Hier is een voorbeeld van een lijst met strings in Python:

    ```python
    band = ['paul', 'john', 'ringo', 'george']
    ```

- In Python worden lijsten geïndexeerd vanaf `0`. Dat betekent dat je kunt praten over het nulde item in een lijst. In ons voorbeeld is het nulde item `'paul'`.

- Om de waarde van een item in een lijst te vinden, typ je eenvoudig de naam van de lijst gevolgd door de index.

    ```python
    >>> band[0]
    'paul'
    >>> band[2]
    'ringo'
    ```
- Om de waarde van het laatste item in een Python-lijst te vinden, kun je ook de index `-1` gebruiken.

    ```python
    >>> band[3]
    'george'
    >>> band[-1]
    'george'
    ```

- Bovendien kun je de waarde van het voorlaatste item vinden met behulp van de index `-2`, enzovoort.

- Soms wil je misschien een tweedimensionale lijst gebruiken, dat wil zeggen een lijst met lijsten. Om een specifiek item te vinden, moet je twee indices opgeven. Hier is een lijst met een spelletje boter-kaas-en-eieren:

    ```python
    bord = [['X', 'O', 'X'],
             ['O', 'X', 'O'],
             ['O', 'O', 'X']]
    ```

- Om het centrale karakter in deze lijst met lijsten te vinden, gebruik je `bord[1][1]`.
