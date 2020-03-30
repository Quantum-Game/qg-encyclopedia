# Mine

Photo-sensitive bomb.

```{quantum-board}
      {
        "cols": 4,
        "rows": 3,
        "cells": [
          {
            "coord": { "y": 1, "x": 0 },
            "element": "Laser",
            "rotation": 0,
            "frozen": true,
            "active": true
          },
          {
            "coord": { "y": 1, "x": 2 },
            "element": "Mine",
            "rotation": 135,
            "frozen": false,
            "active": false
          }
        ]
      }
```

## Basics

It detects the presence of a photon. Note that if there is amplitude 1/sqrt(2), there is 50% probability of the bomb exploding.
A bomb cannot "sense" a part of amplitude, either the photon localizes there (and we are done) or not.

## Digging deeper

Depending on your worldview, either there is a random chance that the bomb explodes or not (e.g. in the Copenhagen interpretation of measurement), or there are two equivalent worlds - one in which it explodes, and one in which it does not (e.g. in the many-world interpretation by Everett).

## Further reading

* [Elitzur–Vaidman bomb tester](https://en.wikipedia.org/wiki/Elitzur%E2%80%93Vaidman_bomb_tester)

## Trivia

Yes, it is a homage to the classic Minesweeper.

* [Kaboom: an unusual Minesweeper](https://pwmarcz.pl/blog/kaboom/)
