# Sasser

A micro sass framework let you to write the code once, make both LTR and RTL directions 
instantly, paint your app or website as a brush and lighten the typography.

* Author — [Vahid Hallaji](http://hallaji.com) , <vahid@hallaji.com>
* License — The MIT License (MIT)
* Copyright — (c) 2015 Vahid Hallaji
* Stable Version — v0.9
* Unstable Version — v1.0-dev


## Quick Start
 
 1. Clone the source to your project sass directory.
 2. 
 3.

## Features

* Uses sass maps structure.
* Makes both LTR and RTL directions.
* Paints your app as a brush
* Assets like colors, fonts and devices can be added anytime and simply.
* Media query
* MVC frameworks
* Separates color and device based styles from main style sheets.

## Documentation

Add your own module to `modules` directory and import it inside `all.scss`

### Prefixes
    
```sass
app-direction-
app-align-
app-paint-
app-typography-
app-utility-
app-helper-
app-media-
```

### Directions

* `app-direction()`

```sass
app-direction()
app-direction-inverted()
app-direction-is-ltr()
app-direction-is-rtl()
app-direction-values($top, $end, $bottom, $start)
app-align-start()
app-align-end()
app-align-start-inverted()
app-align-end-inverted()
```

### Helpers

```sass
app-helper-map-name($map)
 app-helper-map-type($map)
app-helper-add-map($map)
```

### Typography

```sass
app-typography-font-exists($font-name)
```

```sass
app-typography-font-scale-set($font-name, $size: base, $callback-font: false)
```

### Utilities

```sass
app-utility-clearfix-set()
app-utility-vendorize-set($property, $value)
app-utility-offscreen-set()
```

### Media

```sass
app-media-device-exists($device)
app-media-by-property($device, $property)
```

```sass
app-media-device-feature-set($device, $limit: false)
```

### Paint

```sass
app-paint-color-exists($color)
app-paint-by-property($category, $property)
app-paint-by-tone($palette, $tone)
```

## Contributing
Anyone and everyone is welcome to contribute.
