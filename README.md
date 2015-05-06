# Sasser

The micro sass framework lets you code once, generate both LTR and RTL directions instantly, paint your app as a brush and lighten the typography.

* Version (Unstable) — v0.9.0

## Features

* Generates both LTR and RTL directions
* Paints your app as a brush by defineing palettes
* Separates theme and device based styles from main style sheet
* Provides app assets like color, font and device which can be added anytime
* Simplifies media queries
* Uses sass map structure for assets

## Quick Start

```
$ bower install sasser
```

## Preview 

```CSS 
body {
    direction: app-direction();
    app-typography-font-scale-set(ubuntu, base, byekan);
    backgraund-color: app-paint-by-tone(gray, dark);
}
section {
    float: app-align-start();

    #{app-align-start()}: 10px;
    @include app-media-device-feature-set(medium, min){
        #{app-align-start()}: 50px;
    }
}
```

## Documentation

#### Prefixes

```
app-direction-
app-align-
app-paint-
app-typography-
app-utility-
app-helper-
app-media-
```

#### Directions

```
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

#### Helpers

```
app-helper-map-name($map)
app-helper-map-type($map)
app-helper-add-map($map)
```

#### Typography

```
app-typography-font-exists($font-name)
app-typography-font-scale-set($font-name, $size: base, $callback-font: false)
```

#### Utilities

```
app-utility-clearfix-set()
app-utility-vendorize-set($property, $value)
app-utility-offscreen-set()
```

#### Media

```
app-media-device-exists($device)
app-media-by-property($device, $property)
app-media-device-feature-set($device, $limit: false)
```

#### Paint

```
app-paint-color-exists($color)
app-paint-by-property($category, $property)
app-paint-by-tone($palette, $tone)
```

## Author

* Author — [Vahid Hallaji](http://hallaji.com) , <vahid@hallaji.com>
* License — The MIT License (MIT)
* Copyright — (c) 2015 Vahid Hallaji

## Contributing
Anyone is welcome to contribute.
