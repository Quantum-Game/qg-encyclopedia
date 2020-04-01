# Glass

Light travels slower in a glass, so it retards a wavepacket (vs if it were traveling in the air).

```{quantum-board}
{
  "cols": 4,
  "rows": 3,
  "cells": [
    {
      "coord": { "x": 0, "y": 1 },
      "element": "Laser",
      "rotation": 0,
      "frozen": true
    },
    {
      "coord": { "x": 2, "y": 1 },
      "element": "Glass",
      "rotation": 90,
      "frozen": false
    }
  ]
}
```

## Basics

Glass has a refractive index of around 1.5, meaning that light travels a slower speed (2/3 c).
Some special glasses have an even higher refractive index, up to 2.

TODO: Photo of refraction.

## Going deeper

To delay 700nm light (red) by lambda/4 you need only 0.35 µm of glass at n=1.5. It is just half of its wavelength in the vacuum.

In the laboratory, we delay phase by subtler (and more accurate) means.

## Further reading

* [Refractive index](https://en.wikipedia.org/wiki/Refractive_index)
* [Flint glass](https://en.wikipedia.org/wiki/Flint_glass)
