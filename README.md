Improved Errorbars for Highcharts
=============================

This is a plugin for Highcharts to allow X and Y errorbars to be added as a series. Series type is called 'error_bar' to avoid conflict with builtin errorbar type.

Data format is:   [x,y,left,right,low,high]

For example, if you had a data point that was at (20,30) and had an x error of +/- 2 and a y error of +/- 5, your data point would look like this:

[20,30,18,22,25,35]



Demos
=====

[Basic Errorbars Demo](http://jsfiddle.net/v8tLchrr/1/)
--------------------

Simple scatter plot, with the error_bar series added

[X only errorbars](http://jsfiddle.net/v8tLchrr/2/)
--------------------

Plot only X errorbars by setting the format to 'x'

[Y only errorbars](http://jsfiddle.net/v8tLchrr/3/)
--------------------

Plot only Y errorbars by setting the format to 'y'

[No whiskers](http://jsfiddle.net/v8tLchrr/4/)
--------------------

Remove whiskers by setting whiskerLength to 0