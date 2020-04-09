# Mach-Zehnder interferometer

A classic interferometer setup for measuring relative phase change.

```{quantum-board}
{
  "cols": 6,
  "rows": 4,
  "cells": [
    {
      "coord": { "x": 0, "y": 0 },
      "element": "Laser",
      "rotation": 0,
      "frozen": true
    },
    {
      "coord": { "x": 2, "y": 0 },
      "element": "BeamSplitter",
      "rotation": 135,
      "frozen": true
    },
    {
      "coord": { "x": 4, "y": 0 },
      "element": "Mirror",
      "rotation": 135,
      "frozen": true
    },
    {
      "coord": { "x": 2, "y": 2 },
      "element": "Mirror",
      "rotation": 135,
      "frozen": true
    },
    {
      "coord": { "x": 4, "y": 2 },
      "element": "BeamSplitter",
      "rotation": 135,
      "frozen": true
    }
  ]
}
```

```{quantum-board}
{
  "cols": 6,
  "rows": 4,
  "cells": [
    {
      "coord": { "x": 0, "y": 0 },
      "element": "Laser",
      "rotation": 0,
      "frozen": true
    },
    {
      "coord": { "x": 2, "y": 0 },
      "element": "BeamSplitter",
      "rotation": 135,
      "frozen": true
    },
    {
      "coord": { "x": 3, "y": 0 },
      "element": "Glass",
      "rotation": 0,
      "frozen": false
    },
    {
      "coord": { "x": 4, "y": 0 },
      "element": "Mirror",
      "rotation": 135,
      "frozen": true
    },
    {
      "coord": { "x": 4, "y": 1 },
      "element": "Glass",
      "rotation": 0,
      "frozen": false
    },
    {
      "coord": { "x": 2, "y": 2 },
      "element": "Mirror",
      "rotation": 135,
      "frozen": true
    },
    {
      "coord": { "x": 4, "y": 2 },
      "element": "BeamSplitter",
      "rotation": 135,
      "frozen": true
    }
  ]
}
```

## Further reading

* [Mach–Zehnder interferometer](https://en.wikipedia.org/wiki/Mach%E2%80%93Zehnder_interferometer)
* [Mach-Zehnder interferometers and beam splitters - MIT 8.04 Quantum Physics I, Spring 2016](https://www.youtube.com/watch?v=0USje5vTIKs)
