# animated-image
a polymer 2.0 component to animate image using panning and zooming effect known as ken-burns-effect

## Installation
```
$ bower install --save gauravkk22/animated-image
```

## Using the component

```
<animated-image>...</animated-image>
```

PROPERTIES:
```
 source="gaurav_profile.jpg" --- source for the image
 viewport-width="448px"      --- set width of image viewport
 viewport-height="300px"     --- set height of image viewport
 scale-start="2"             --- set the scale beginning value
 scale-end="1"               --- set the scale end value
 animation-fill-mode="forwards" ---  set the animation fill mode value
 animation-timing-function="cubic-bezier(0, 3.58, 0.43, -0.59)" --- set the animation timing function
 animation-duration="10s"   --- set the animation duration
 opacity-start="0.3"        --- set the opacity start value
 opacity-end="0.6"          --- set the opacity end value
 translate-x-start="0px"    --- set the x axis translation that occurs at the start of the animation
 translate-x-end="-10px"    --- set the x axis translation that occurs at the end of the animation
 translate-y-start="-60px"  --- set the y axis translation that occurs at the start of the animation
 translate-y-end="-150px"   --- set the y axis translation that occurs at the end of the animation
 ```

## Usage
```
<script src="../webcomponentsjs/webcomponents-lite.js"></script>
<link rel="import" href="animated-image.html">
<animated-image>...</animated-image>
```

This component is used to animate the image using ken-burns-effect.
Customisable css which can be used to set animation in :root (Example is below):-

```
  --kb-viewport-width: 448px;
  --kb-viewport-height: 300px;
  --kb-animation-duration: 10s;
  --kb-background-color: black;
  --kb-scale-start: 2;
  --kb-scale-end: 1.1;
  --kb-opacity-start: 1px;
  --kb-opacity-end: 1px;
  --kb-animation-fill-mode: forwards;
  --kb-animation-timing-function: ease-in;
  --kb-translate-x-start: 0px;
  --kb-translate-y-start: 0px;
  --kb-translate-x-end: -50px;
  --kb-translate-y-end: -50px;
```


## Contributing

```
Fork it!
Create your feature branch: git checkout -b my-new-feature
Commit your changes: git commit -am 'Add some feature'
Push to the branch: git push origin my-new-feature
Submit a pull request :D

```
## License

```
MIT License

```
