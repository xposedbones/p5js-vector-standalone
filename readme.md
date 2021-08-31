# Typescript standalone port of the wonderful Vector library from p5.js.

Ported from (here)[https://github.com/processing/p5.js/blob/main/src/math/p5.Vector.js]

## Usage
```ts
import { Vector } from 'p5js-vector-standalone';

const vec1: Vector = new Vector(10, 0, 0);
const vec2: Vector = new Vector(20, 10, 0);

vec1.add(vec2); // vec1 = {x: 30, y: 10, z: 0};
```

### List of methods
* copy()
* add()
* rem()
* sub()
* mult()
* div()
* mag()
* magSq()
* dot()
* cross()
* dist()
* normalize()
* limit()
* setMag()
* heading()
* setHeading()
* rotate()
* angleBetween()
* lerp()
* reflect()
* array()
* equals()

## List of static methods
* fromAngle()
* fromAngles()
* random2D()
* random3D()
* add()
* rem()
* sub()
* mult()
* rotate()
* div()
* dot()
* cross()
* dist()
* lerp()
* mag()
* normalize()

# Thanks
Huge thanks to everyone involved with (p5.js)[https://github.com/processing/p5.js/]