[![Build Status](https://travis-ci.com/JaroslawWiosna/level-set.svg?token=o1NhkEzXPpzaim9ynHJS&branch=master)](https://travis-ci.com/JaroslawWiosna/level-set)
[![Pull Requests](https://img.shields.io/github/issues-pr/JaroslawWiosna/level-set.svg)](https://github.com/JaroslawWiosna/level-set/pulls)

[![Licence](https://img.shields.io/github/license/JaroslawWiosna/level-set.svg)]()
[![Release](https://img.shields.io/github/release/JaroslawWiosna/level-set.svg?maxAge=3600)](https://github.com/JaroslawWiosna/level-set/releases)
[![GitHub contributors](https://img.shields.io/github/contributors/JaroslawWiosna/level-set.svg)]()

# level-set
> Team project - Cyfrowe techniki rozpoznawania obrazów (pl. "Digital image recognition methods") 2016/2017

  - [Overview](#overview)
     - [Basic algorithm](#basicalgorithm)
  - [Usage](#usage)
  - [Timeline](#timeline)
  - [Credits](#credits)
  - [Contributors](#contributors)
  - [Licence](#licence)

---

## Overview

The main purpose is to detect objects using **active contour**.
Implementation based on 
  - [Pascal Getreuer, Chan-Vese Segmentation, Image Processing On Line, 2 (2012), pp. 214–224](http://www.ipol.im/pub/art/2012/g-cv)
  - [Tony F. Chan, Luminita A. Vese Active Contours Without Edges IEEE TRANSACTIONS ON IMAGE PROCESSING, VOL. 10, NO. 2, FEBRUARY 2001](http://www.math.ucla.edu/~lvese/PAPERS/IEEEIP2001.pdf)

### Basic algorithm

TBD

---

## Usage

```
  $ mkdir -p build
  $ cd build
  $ cmake .. # or cmake -DBUILD_TESTS=ON if you want to build gtests
  $ make
  $ ./level-set -i ../test-images/001.jpg
```
Ifstead of `cmake ..` type `cmake -DBUILD_TESTS=ON` if you want to build gtests.

---

## Timeline
  - `28.11.2016` - start
  - `16.01.2017` - project will have been finished by this date
  - `23.01.2017` - presentation

## Credits

TBD

## Contributors

[![GitHub contributors](https://img.shields.io/github/contributors/JaroslawWiosna/level-set.svg)]()

[contributors](https://github.com/JaroslawWiosna/level-set/graphs/contributors)

## Licence

[![Licence](https://img.shields.io/github/license/JaroslawWiosna/level-set.svg)]()

[Mozilla Public License Version 2.0](https://github.com/JaroslawWiosna/level-set/blob/master/LICENCE)
