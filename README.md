simpleslider
============

A simple, customizable Jquery slider or image fade gallery


License
============

Licensed under the WTFPL license http://www.wtfpl.net/
Copyright (C) 2014 Corbin Nakamura <www.creativeenhance.com>
Everyone is permitted to copy and distribute verbatim or modified
copies of this license document, and changing it is allowed as long
as the name is changed. 

#### Features:
 * Fade or slider options
 * 10kb minified and gzip
 * Simple markup using standard HTML img tags
 * Settings for timeout durations
 * Settings for speed of animations
 * Multiple slideshows supported
 * Works in all major desktop and mobile browsers
 * Add or remove next/prev controls
 * Choose a starting slide
 * Slideshow paused on hover

Basic Usage
============

 $("#slider").slider({
            width: 1200,
            height: 369,
            speed: 700,
            easing: 'easeOutExpo',
            nav: true,
            start: 1,
            play: {
                auto: true,
                interval: 2000
                  },
            effect: 'fade'
            });
