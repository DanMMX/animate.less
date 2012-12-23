#Animate.less
*Cross-browser CSS3 animation library for Bootstrap*

`animate.less`, originally created by [Dan Eden](https://github.com/daneden/animate.css "Dan Eden"), is a bunch of cool, fun, and cross-browser animations converted into LESS for you to use in your Bootstrap projects. Great for emphasis, home pages, sliders, and general just-add-water-awesomeness.

##Usage
###Bootstrap
To use animate.less in your Bootstrap project, simply add the line below into `bootstrap.less`:

```css
@import "animate.less";
```

###Inside your HTML
Add  the class `animated` to an element, along with any of the animation names. That's it! You've got a CSS animated element. Super!

For example:

```html
<h1 id="logo" class="animated fadeIn">...</h1>
```

###Inside your styelsheet
Add  the class `animated` to an element, along with any of the animation names. That's it! You've got a CSS animated element. Super!

###Working with jQuery
You can add more functionality to your animations with jQuery such as below:

```javascript
$('#yourElement').addClass('animated bounceOutLeft');
```

###Editing an animation
You can change the duration of your animations, add a delay or change the number of times that it plays!

```css
#yourElement {
	-vendor-animation-duration: 3s;
	-vendor-animation-delay: 2s;
	-vendor-animation-iteration-count: infinite;
}
```

*Note: be sure to replace "vendor" in the CSS with the applicable vendor prefixes (webkit, moz, ms, o)*

*Note: Safari in Mountion Lion (OS 10.8) has a display glitch with the Flippers. They may not appear at all until the animation is completed, or the page may have other artifacting. One fix is to add overflow: hidden to the parent div.*

##License
Animate.css is licensed under the &#9786; license. (http://licence.visualidiot.com/)

##Learn more
You can learn more about animate.css over at http://daneden.me/animate
You can also get in touch via email (dan.eden@me.com) or twitter (@_dte) if you need any help or have any issues.

##Cheat Sheet

####Attention seekers:
flash
bounce
shake
tada
swing
wobble
wiggle
pulse

####Flippers (currently Webkit, Firefox, &amp; IE10 only):
flip
flipInX
flipOutX
flipInY
flipOutY

####Fading entrances:
fadeIn
fadeInUp
fadeInDown
fadeInLeft
fadeInRight
fadeInUpBig
fadeInDownBig
fadeInLeftBig
fadeInRightBig

####Fading exits:
fadeOut
fadeOutUp
fadeOutDown
fadeOutLeft
fadeOutRight
fadeOutUpBig
fadeOutDownBig
fadeOutLeftBig
fadeOutRightBig

####Bouncing entrances:
bounceIn
bounceInDown
bounceInUp
bounceInLeft
bounceInRight

####Bouncing exits:
bounceOut
bounceOutDown
bounceOutUp
bounceOutLeft
bounceOutRight

####Rotating entrances:
rotateIn
rotateInDownLeft
rotateInDownRight
rotateInUpLeft
rotateInUpRight

####Rotating exits:
rotateOut
rotateOutDownLeft
rotateOutDownRight
rotateOutUpLeft
rotateOutUpRight

####Lightspeed:
lightSpeedIn
lightSpeedOut

####Specials:
hinge
rollIn
rollOut