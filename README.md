# skrollr-experiment
 This is a short example of the skrollr library. Made with much appreciated inspiration from <a href="https://ihatetomatoes.net/">iHateTomatoes</a>.
 
 ##Architecture
 Skrollr builds on a quite simple parallax-animation principle that binds any animatable css properties to the accurate scroll position of the y-axis on the page. Simply define a data property on any HTML element - say 
 
----
<div class="fadein" data-0="opacity:0" data-100="opacity:1">This text will fade in when scroll-y pos is 100</div> 
----

And so on. 
