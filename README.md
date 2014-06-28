three and a half Perf tips
==========================

For Chicago HTML5 meetup July 9, 2014

###Tip -1
_________________
Cache global variables in the local scope when you are accessing them for a million times

###Tip -2
_______________
Delegate Events when similar event handler for hundred of elements

###Tip-2.5
______________
Use throttle and debounce when same events are firing several times whithin a short period of time and you care only about the 
the last one. For example, When user is scrolling their mouse, only you care about the last position of the mouse, when user stops
scrolling. Hence, you can avoid firing event hundred times. Just fire only for the last one.

##Tip-3.5
___________
still looking for. May be You might not need JQuery

