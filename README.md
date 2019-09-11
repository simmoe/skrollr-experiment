# skrollr-experiment
 This is a short example of the skrollr library. Made with much appreciated inspiration from <a href="https://ihatetomatoes.net/">iHateTomatoes</a>.
 
 ## Architecture
 Skrollr builds on a quite simple parallax-animation principle that binds any animatable css properties to the accurate scroll position of the y-axis on the page. Simply define a data property on any HTML element - say 
 
~~~~
<div class="fadein" data-0="opacity:0" data-100="opacity:1">This text will fade in when scroll-y pos is 100</div> 
~~~~

And so on. Remark that this is not exactly <a href="https://medium.com/@dhg/parallax-done-right-82ced812e61c">the kosher way of creating parallax style effects</a>. However the library can be used to create some very nice animated stories, and when you get the hang, fun too. 

The principle used in this - admittedly ugly and demonstration only - example, is to set all sections to full viewport height/width and position static. You can then blend them in eiher by moving them in on an axis, or fading opacity. It is definitely not great on performancebut but it's good fun.

<a href="https://simmoe.github.io/skrollr-experiment/">See demo</a>

<a href="https://github.com/Prinzhorn/skrollr">Check out furhter docs here</a>
