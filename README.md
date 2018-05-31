## Transformed Elements Became the Container for the Fixed

The transformed container becomes the container of the fixed-position element. The fixed-position element scrolls along with the container.

* Demo: http://harttle.github.io/animation-bugs/fixed-in-transformed-layer.html
* Issue: https://bugs.chromium.org/p/chromium/issues/detail?id=20574&desc=2

## TranslateY + Relative Causing Flikering

`translateY` and `position:relative` causes page flikering in iOS Safari (tried iOS 10, iOS 11.3, iOS 11.4)

* Demo: http://harttle.github.io/animation-bugs/translatey-relative-flikering.html
