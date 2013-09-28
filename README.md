Elegance
=======

A responsive &amp; minimalist browser compatible video player made with Javascript and CSS. 

Objectives
====

Based on the Popcorn video player I decided to give it a minimalist touch so I modified it's easy to
use and responsive, give an elegant touch to your videos.

Install
===

"Omg I'm overwhelmed with installing anything" Chill, just download the [master.zip](https://github.com/dope/popcorn/archive/master.zip) and link your stylesheet and script file to your `.html` document

### Then what?!

Literally just copy and paste this to your HTML file to get it working properly
```
<div id="videoWrap">
    <video id="mainVideo" poster="img/popcorn-poster.svg">
        <source src="media/your_movie.mp4" type="video/mp4">
        <source src="media/your_movie.m4v" type="video/mp4">
        <source src="media/your_movie.mov" type="video/mov">
        <source src="media/your_movie.ogv" type="video/ogg">
    </video>
    
    <div id="controlsOptions">
    
        <button class="videoBtn" id="playPausebtn"> 
        <i class="icon-play"></i>
        </button> 
        
        <span id="curtimetext">00:00</span>

        <input id="slider" type="range" min="0" max="100" value="0" step="1"> 
        <span id="durtimetext">00:00</span>

        <button class="videoBtn" id="fullscreenbtn"> 
        <i class="icon-full"></i>
        </button>
        
        <button class="videoBtn" id="mutebtn"> 
        <i class="icon-unmute"></i>
        </button>
    </div>
</div>
```
