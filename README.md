three and a half Perf tips
==========================

[slides](https://goo.gl/m4YgDu)
###Tip -1
_________________
Cache global variables in the local scope when you are accessing them for a million times

##Tip-2
___________
For Array
1.  assign value by index is faster than push, if you know which index you are pushing
2.  indexOf and lastIndexOf takes a second parameter. This second parameter tells from where search should be started. For example, if you have one thousand elements and you know the elements you are looking for is after index = 750. You can save time to search 0-750 by providing 750 as the second parameter.
3.  A simple for loop coudd be much faster than build forEach, map in the most cases


###Tip -3
_______________
Delegate Events when similar event handler for hundred of elements

###Tip-3.5
______________
Use throttle and debounce when same events are firing several times whithin a short period of time and you care only about the 
the last one. For example, When user is scrolling their mouse, only you care about the last position of the mouse, when user stops
scrolling. Hence, you can avoid firing event hundred times. Just fire only for the last one.



