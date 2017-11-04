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
