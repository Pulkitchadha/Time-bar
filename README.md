# jquery-time-bar [![NPM version][npm-image]][npm-url] [![Build Status][travis-image]][travis-url] [![Dependency Status][daviddm-image]][daviddm-url]

## Demo
* [Link](https://jquery-timebar-demo.herokuapp.com/)

## Installation

1) Include these two files :
    timebar.js  && timebar.css in your index.html.

2)  Call this single function

    $(document).ready( function () {
        $("#mytimebar").timebar();
    } );

3) done.

## Options

1) totalTimeInSecond: Integer, Default value : 60
2) cuepoints: Array,Default value : 60
3) width: String,Default value : '1000px'
4) multiSelect: Boolean,Default value : false
5) selectedTime: Integer, Default value : 0
6) showCuepoints: Boolean, Default value : false

## Methods
1) addCuepoints : pass time in seconds,func(integer)
2) updateSelectedCuepoint: pass new time in seconds,func(integer)
3) deleteSelectedCuepoints: func()
4) showHideCuepoints : accept value in true or false,func(boolean)
5) getSelectedTime : return time in seconds, func
6) setSelectedTime: pass time in seconds, func(integer)
7) getTotalTime : return total time in seconds, func
8) setTotalTime : pass time in seconds , func(integer)
9) getWidth : return width ,func()
10) setWidth : pass width , func(string)
11) getCuepoints : return cuepoints in array, func()

## License

MIT © [pulkitchdha]()


[npm-image]: https://badge.fury.io/js/generator-js-plugin.svg
[npm-url]: https://npmjs.org/package/generator-js-plugin
[travis-image]: https://travis-ci.org/Pulkitchadha/generator-js-plugin.svg?branch=master
[travis-url]: https://travis-ci.org/Pulkitchadha/generator-js-plugin
[daviddm-image]: https://david-dm.org/Pulkitchadha/generator-js-plugin.svg?theme=shields.io
[daviddm-url]: https://david-dm.org/Pulkitchadha/generator-js-plugin
