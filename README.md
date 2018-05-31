## Transformed Elements Became the Container for the Fixed

The transformed container becomes the container of the fixed-position element. The fixed-position element scrolls along with the container.

* Environment: effectively all browsers with transform supported
* Demo: http://harttle.github.io/animation-bugs/fixed-in-transformed-layer.html
* Video: [fixed-in-transformed-layer.mp4](./fixed-in-transformed-layer.mp4)
* Issue: https://bugs.chromium.org/p/chromium/issues/detail?id=20574&desc=2

## TranslateY + Relative Causes Flikering

In some complicated cases, `translateY` and `position:relative` can cause page flikering

* Environment: iOS, tried iOS 10, iOS 11.3, iOS 11.4
* Demo: http://harttle.github.io/animation-bugs/translatey-relative-flikering.html
* Video: [translatey-relative-flikering.mp4](./translatey-relative-flikering.mp4)
* Issue: None
