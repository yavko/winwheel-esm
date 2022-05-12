# winwheel-esm
Create spinning prize wheels on HTML canvas with winwheel-esm a fork of Winwheel.js

## Description
winwheel-esm is a feature packed JavaScript library that allows you to easily create HTML5 canvas Winning / Prize Wheels, Pie graphs and other things using a highly configurable JavaScript class.

Wheels can be animated using gsap's TweenMax, which contain easing functions, and many other powerful animation features.

winwheel-esm Features Include:
* Easy to use, highly configurable JavaScript classes.
* Draw wheels using code generated segments or graphically rich images.
* Responsive features so wheels display correctly on different sized devices.
* Numerous text orientation, direction, size and colour options.
* Random or Pre-calculated prize stopping location.
* Play sounds while the wheel is spinning including a "tick" sound.
* Ability to get the segment the user clicked upon.
* Fully commented source code. Plenty of tutorials and other documentation.
* winwheel-esm is free to use with an open source license.

## Example
```javascript
import { Winwheel } from '@yavko/winwheel-esm';

const wheel = new Winwheel({
    'numSegments': 4,
    'segments': [
        {'fillStyle': '#eae56f', 'text': 'Prize One'},
        {'fillStyle': '#89f26e', 'text': 'Prize Two'},
        {'fillStyle': '#7de6ef', 'text': 'Prize Three'},
        {'fillStyle': '#e7706f', 'text': 'Prize Four'}
    ],
    'animation': {
        'type': 'spinToStop',
        'duration': 5,
        'spins': 8
    }
});
```

## More examples
See the /examples folder for examples of some of the types of things you can create with winwheel-esm, to see these examples in action please visit the examples section on the original winwheel website http://dougtesting.net/winwheel/examples

## Tutorials and other documentation
Please visit http://dougtesting.net/winwheel/docs to see a complete set of tutorials on how to use winwheel-esm as well as other documentation such as class references.

## Maintainer
Yavor Kolev https://github.com/yavko

## Please note
This wasn't created by me this is just a fork of Winwheel.js that supports ecmascript modules
