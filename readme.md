## Wirez
Starter file for wireframe design systems.

## Getting started

Grab the [Sketch](https://sketch.cloud/s/zzLYM) or [Figma](https://www.figma.com/file/WV7JaXV0jkEKQxCaWUz7XN) files in order to get started.

## Artboards / Frames

Includes four artboards / frames:
* 360px
* 768px
* 1280px
* 1440px

## Layout

Follows an 8px grid with a 4px baseline grid.

* 360px
  * columns: 4 / 60px
  * margins: 24px
  * gutters: 24px
* 768pt
  * columns: 8 / 76px
  * margins: 24px
  * gutters: 16px
* 1280pt
  * columns: 12 / 88px
  * margins: 24px
  * gutters: 16px
* 1440pt
  * columns: 12 / 80px
  * margins: 64px
  * gutters: 32px

## Colors

Includes five shades of gray + white used as default background fills as well as four basic hues (red, blue, green, and yellow) for additional contrast and visibility.

```
$color-red: #FF0000;
$color-green: #008000;
$color-blue: #0000FF;
$color-yellow: #FFFF00;
$color-white: #FFFFFF;
$color-gray-10: #EEEEEE;
$color-gray-20: #BDBDBD;
$color-gray-60: #757575;
$color-gray-80: #424242;
$color-gray-90: #212121;
```

## Typography

Base font size set to 16px, line height of 1.5 and scale factor of 1.618.

```
body {
  font-family: Menlo, Fira Code, monospace;
  font-size: 16px;
  line-height: 24px;
}

h1 {
  font-size: 68px;
  line-height: 72px;
  margin-top: 24px;
  margin-bottom: 48px;
}

h2 {
  font-size: 42px;
  line-height: 48px;
  margin-top: 24px;
  margin-bottom: 24px;
}

h3 {
  font-size: 26px;
  line-height: 48px;
  margin-top: 24px;
  margin-bottom: 0px;
}

h4 {
  font-size: 16px;
  line-height: 24px;
  margin-top: 24px;
  margin-bottom: 0px;
  text-transform: uppercase;
}
```
