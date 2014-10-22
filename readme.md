# Sasser

A micro sass framework let you to write once, make both ltr and rtl directions 
instantly, paint your app or website as a brush and lighten the typography.

- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -

 * Author — [Vahid Hallaji](http://hallaji.com) , <vahid@hallaji.com>
 * Copyright — (C) 2006-2014, Vahid Hallaji
 * License — The MIT License (MIT)
 * Stable Version — No release
 * Unstable Version — v0.1-dev

- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - -

## Quick Start

### Install

## Features

 * Support both ltr and rtl directions
 * Media query
 * Add color, font, device simply

## Documentation

 * Index
    
        app-direction-
        app-align-
        app-paint-
        app-typography-
        app-utility-
        app-helper-
        app-media-
    
 * app-direction
    
    * @function
    
        app-direction()
        app-direction-inverted()
        app-direction-is-ltr()
        app-direction-is-rtl()
        app-direction-values($top, $end, $bottom, $start)
        app-align-start()
        app-align-end()
        app-align-start-inverted()
        app-align-end-inverted()
        
 * app-helper
        
    * @function
    
        app-helper-map-name($map)
        app-helper-map-type($map)
        app-helper-add-map($map)
        
* app-typography
        
    * @function
    
        app-typography-font-exists($font-name)
        
    * @mixin
    
        app-typography-font-scale-set($font-name, $size: base, $callback-font: false)
        
 * app-utility

    * @mixin
        
        app-utility-clearfix-set()
        app-utility-vendorize-set($property, $value)
        app-utility-offscreen-set()
        
* app-media
        
    * @function
        
        app-media-device-exists($device)
        app-media-by-property($device, $property)
        
    * @mixin    
        
        app-media-device-feature-set($device, $limit: false)
        
 * app-paint

    * @function
   
        app-paint-color-exists($color)
        app-paint-by-property($category, $property)
        app-paint-by-tone($palette, $tone)
        
## Contributing

Anyone and everyone is welcome to contribute.

## License

The Sasser is an open-source software licensed under the MIT license
