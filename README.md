simpleslider
============

A simple, customizable Jquery slider or image fade gallery

/*
  SIMPLESLIDER Jquery Plugin
  Updated: 5/2014
  Version: 1.0;
  Licensed under the WTFPL license http://www.wtfpl.net/
  Copyright (C) 2014 Corbin Nakamura <corbin@creativeenhance.com> 

  Everyone is permitted to copy and distribute verbatim or modified 
  copies of this license document, and changing it is allowed as long 
  as the name is changed. 

*/

Usage
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
