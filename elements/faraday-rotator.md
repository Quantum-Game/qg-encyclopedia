# Faraday Rotator

It rotates the polarization of light by 45 degrees due to interaction with magnetic crystal.

```{quantum-board}
{
  "cols": 6,
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
      "element": "FaradayRotator",
      "rotation": 0,
      "frozen": false
    },
    {
      "coord": { "x": 4, "y": 1 },
      "element": "FaradayRotator",
      "rotation": 0,
      "frozen": false
    }
  ]
}
```

## The basics

A photon enters a ferromagnetic crystal placed in a strong magnetic field. Due to the “magneto-optic effect”, the polarization of the photon is rotated by an angle proportional to the magnetic field along the propagation direction. Consequently, if the photon enters from the opposite end, its polarization will be rotated in the opposite direction.

The strength of the effect is described by the Verdet coefficient. For olive oil and red light (659.2 nm) it is 192° per meter per Tesla.

## Explanations

Suppose a photon travels through a Faraday rotator, gets reflected off the mirror and travels back through the rotator. On the second pass, the effect of the rotator adds up to the first pass, and the photon polarization is rotated by 90 degrees overall. The reason for this is that upon reflection, the wave changes chirality - so left-circularly polarized light becomes right-circularly polarized, and vice versa. This so-called “non-reciprocity” is the reason why Faraday rotators are ubiquitous in optics laboratories.

## Usage in laboratories and experiments

By combining a Faraday rotator with two polarizing beamsplitters we create an optical isolator. This device allows light to pass in one direction, while blocking the other. Isolators are commonly used to protect sensitive equipment (such as laser diodes) that can break due to back-reflections. Faraday rotators can also be used to create double-pass amplifiers.

## Further Reading

* [Magneto-optic Effects](https://en.wikipedia.org/wiki/Magneto-optic_effect)
* [Faraday Rotators](https://www.rp-photonics.com/faraday_rotators.html)
* [Faraday Rotators on ThorLabs](https://www.thorlabs.com/newgrouppage9.cfm?objectgroup_id=12684)
* [Control light with magnets and olive oil?!](https://www.youtube.com/watch?v=XhU-nNiAgtI)
* [Measuring the Faraday effect in olive oil using permanent magnets and Malus' law](https://arxiv.org/abs/1908.08120)
