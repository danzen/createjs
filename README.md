<p>ZIM at https://zimjs.com is a general JavaScript Canvas Framework that is powered by CreateJS.
CreateJS has been stable since 2017 and generally provides containers and events for the HTML Canvas
as well as preloading, sound and tweening - see https://createjs.com
</p>

![about_examples](https://github.com/danzen/createjs/assets/380281/0ce27ff4-5887-403f-8328-0f7e4d9d7188)

<p>ZIM has been constantly progressing since 2014 and is now over 4 times more code than CreateJS.
It provides many conveniences, components and controls.  
No longer are createjs objects directly used as ZIM extends a Container, Shape, Bitmap and MovieClip
with ZIM providing over 40 components and over 80 methods to DisplayObjects.
Preloading is done in the ZIM Frame or on demand - including lazy loading.
ZIM animate() provides dozens of extra features making animation in ZIM as powerful and complete as GreenSock GSAP.  
This includes animating and dragging along user editable paths providing industry leading functionality.
Please read https://zimjs.com/about for features.</p>

![vision](https://github.com/danzen/createjs/assets/380281/9550da0c-f84f-436a-a16a-b11f5cccedae)

<p>This is a version of CreateJS that we have been modifying over the last 10 years.  
It is based on CreateJS 1.0 (ES5 - not ES6 - which as far as we know, has not been fully developed).</p>
<p>Look for <em>Dan Zen</em> in the code to see the 40 (or so) updates.
Many of the updates have also been updated in the CreateJS Github where we do some maintenance.</p>
<p>Generally, ZIM works with the official CreateJS except for ZIM TextureActives which needs this version.
The offical release is hosted on the Adobe CDN and is used with Adobe Animate. 
However, multitouch and retina adjustments make using our version a little more stable.
Retina (devicePixelRatio) makes you have to adjust for stage scale for mouse positions in the official CreateJS.
The ZIM version adjusts for that.</p>
<p>Note - that ZIM has ZIM Shim for Adobe Animate and you can use this version of CreateJS with that too.</p>
