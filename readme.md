## Wires
Starter file for wireframe design systems.

## Artboards / Frames

Includes four artboards:
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

A basic palette of ten colors, with five shades of gray used as default container fills. Four action colors (red, blue, green, and yellow) are reserved for cases where additional contrast / visibility in the wireframe is needed.

```
$color-action-red: #F44336;
$color-action-green: #4CAF50;
$color-action-blue: #2196F3;
$color-action-yellow: #FFEB3B;
$color-gray-10: #E0E0E0;
$color-gray-20: #C7C7C7;
$color-gray-40: #959595;
$color-gray-60: #646464;
$color-gray-90: #181818;
$color-white: #FFFFFF;
```

## Typography

Base font size set to 16px, line height of 1.5 and scale factor of 1.618.

```
body {
  font-family: Menlo;
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
