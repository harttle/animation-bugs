## Transformed Elements Became the Container for the Fixed

The transformed container becomes the container of the fixed-position element. The fixed-position element scrolls along with the container.

* Platform: effectively all browsers with transform supported
* Demo: http://harttle.github.io/animation-bugs/fixed-in-transformed-layer.html
* Video: [fixed-in-transformed-layer.mp4](https://harttle.land/animation-bugs/fixed-in-transformed-layer.mp4)
* Issue: https://bugs.chromium.org/p/chromium/issues/detail?id=20574&desc=2

## TranslateY + Relative Causes Flikering

In some complicated cases, `translateY` and `position:relative` can cause page flikering

* Platform: iOS, tried iOS 10, iOS 11.3, iOS 11.4
* Demo: http://harttle.github.io/animation-bugs/translatey-relative-flikering.html
* Video: [translatey-relative-flikering.mp4](https://harttle.land/animation-bugs/translatey-relative-flikering.mp4)
* Issue: None

## Animation freezes ontouch in iOS UIWebview

In iOS UIWebview, any transition/animation/JavasCripts will freeze on touch.

* Platform: iOS UIWebview
* Demo: http://harttle.github.io/animation-bugs/a-normal-animation.html
* Video: [a-normal-animation.mp4](https://harttle.land/animation-bugs/a-normal-animation.mp4)
