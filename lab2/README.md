# Lab 2: Nim
## Description
Nim is a mathematical game of strategy in which two players take turns removing (or "nimming") objects from distinct heaps or piles. On each turn, a player must remove at least one object, and may remove any number of objects provided they all come from the same heap or pile. Depending on the version being played, the goal of the game is either to avoid taking the last object or to take the last object.

For example, `Nim(3)`:
```
1.                    |                     (1)
2.                |   |   |                 (3)
3.            |   |   |   |   |             (5)
```

Nim is typically played as a misère game, in which the player to take the last object loses. Nim can also be played as a "normal play" game whereby the player taking the last object wins.

## The lab task
The lab requested us to build an expert **rule-based agent** based on nim sum, and an **evolutionary-based agent** able to play the Nim game in the **Misere** version of a varation of Nim known as **The subtraction game**. <br>
In this variant, an upper bound is imposed on the number of objects that can be removed in a turn. Instead of removing arbitrarily many objects, a player can only remove 1 or 2 or ... or k at a time.

## References

* [Nim](https://en.wikipedia.org/wiki/Nim)
* [How to win at Nim](https://en.wikipedia.org/wiki/Nim#Proof_of_the_winning_formula)

## Collaborations
- I worked with [Davide Sferrazza - s326619](https://github.com/FarInHeight) for the rule-based agent. And then, with the help of both [Davide Sferrazza - s326619](https://github.com/FarInHeight) and [Alexandro Buffa - s316999](https://github.com/ExalFabu/Computational-Intelligence/tree/main), we developed the evolutionary-based agent.
