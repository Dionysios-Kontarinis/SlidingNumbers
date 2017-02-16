NumberSliding
===============

This is an implementation of a well-known **number sliding puzzle**. Also, it contains a small **A.I. engine** able to play the game.
By running *NumberPuzzleApp.class*:

* The user is requested to create a square with 9 elements.
* Each element is a number in [1,9] except from 3. Also, one element is "void" (denoted by '0').
* The user can choose:

1. To play the game by himself. In this case, he is asked to play a series of moves (each move slides an element to its adjacent "void")
until he properly arranges all 9 elements (1 2 "void" # 4 5 6 # 7 8 9).

2. To ask the help of our A.I. engine. If the engine sees a series of moves leading to the desired arrangement, then it will play them instantly,
one-by-one. Otherwise, it will use a heuristic in order to play one "good" move, and then it will continue from there.
