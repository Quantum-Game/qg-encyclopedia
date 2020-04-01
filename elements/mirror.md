# Mirror

A mirror is an object that reflects incident light preserving its properties.

_Mirror, mirror on the board, what is the best quantum game in the world?_

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
      "element": "Mirror",
      "rotation": 135,
      "frozen": false
    }
  ]
}
```

## The basics

A mirror reflects light, with incidence angle being the same as the reflectance angle.

It does change left with right! To see that, play with the transition matrix and set basis for circular ⟲⟳.

## In-game

We use a mirror that reflects light from both sides. While it is technically possible, it is not a common setting for everyday, or laboratory, use.

## Dig deeper

Typical mirrors are made by taking a flat piece of glass and coating one side with a metal such as silver or aluminum.
However, such metals do absorb light - at least a few percent with each reflection.

![Reflectance for metals](https://upload.wikimedia.org/wikipedia/commons/9/9d/Image-Metal-reflectance.png)

In laboratory, with mutliple mirrors in a single line, usually is not accetpable - due to heating (for strong beams) or lossing photons (for very weak beams).  
However, it is possible to reflect with non-absorbtive materials, using so-called Bragg reflection.
It requires enhancing natural reflection from surface by creating multiple layers with different refractive indicses, creating so-called dielectric mirrors.

For some applications it is enough to have a mirror that works at a given wavelength (e.g. for monochromatic lasers), but sometimes we need to work at a whole range of weavelength (e.g. for femtosecond impulses). There are mirros for various wavelength ranges, from infrared, through the visible spectrum, to ultraviolet light.

## TRICKS WITH PHASE

NB! When light hits a surface which has a higher refractive index than the medium in which is wa travelling it will pick up a 180 degrees phase!

## Everyday Life

“Mirror mirror on the wall who's the fairest of them all?”

We all use mirrors all the time, to check on our hair in the morning, or to look at our backs when we are driving. Mirrors are all around us!

## Further reading

* [Mirror](https://en.wikipedia.org/wiki/Mirror)
* [Specular reflection](https://en.wikipedia.org/wiki/Specular_reflection)
* [Dielectric mirror](https://en.wikipedia.org/wiki/Dielectric_mirror)
* [Reflection phase change](https://en.wikipedia.org/wiki/Reflection_phase_change)
* [Optical coating](https://en.wikipedia.org/wiki/Optical_coating)
* [Optical Cavity](https://en.wikipedia.org/wiki/Optical_cavity)
