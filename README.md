#Animate.css - from [daneden](https://github.com/daneden/animate.css)
*Just-add-water CSS animation*

`animate.css` is a bunch of cool, fun, and cross-browser animations for you to use in your projects. Great for emphasis, home pages, sliders, and general just-add-water-awesomeness.

<br>
##My implementation

I've amended [daneden's](https://github.com/daneden/animate.css) fantastic animate.css to fit in with my project structure. It's written in SASS and all properties are unprefixed. For vendor prefxing I run my compiled CSS files through [gulp-autoprefixer](https://www.npmjs.org/package/gulp-autoprefixer). You can amend and prefix in a way that best suits your project/structure/needs.


##Usage
For basic usage instructions please refer to [daneden's README](https://github.com/daneden/animate.css).

To use my version of animate.css you need to import animate.scss into your SASS file of choice. First, you need to enable animations to be able to use the 'animated' class in your HTML. Then, you can choose to enable any and all animations you wish to use on your project. (Remember to update the path to reflect your project structure).

```
$animations: true;
$animations-bounceInDown: true;
$animations-bounceIn: true;
$animations-wobble: true;
```

```
@import "animate";
```

See the example folder for more information. Feedback welcome!