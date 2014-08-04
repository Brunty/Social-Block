# Social Block

The purpose of this small repo is to give a re-useable set of social icons based on [Font Awesome](http://fortawesome.github.io/Font-Awesome/) including variations on size, style and whether or not they're coloured etc.

## Sizes

* .social-block
* .social-block.small
* .social-block.large
* .social-block.x-large

The 'default' size (could be called 'medium') doesn't need a size class declared on it as well.

## Styles

* .radius
* .circles

The 'default' style is square

## Positioning

* .horizontal
* .vertical

Currently there's no set default on the style, you must declare one.

You can also remove spacing between the buttons by adding the following class:

* .no-space

## Colouring

Colouring is added via the following class:

* .coloured
* .hover-coloured

The hover-coloured class will make them coloured to their respective brand colours when you hover over them.

It's the British spelling. Deal with it.

Example block:

```
<!-- Put this block where you want social icons -->
 <div class="social-block horizontal coloured radius">
     <a href="">
         <i class="fa fa-facebook"></i>
     </a>
     <a href="">
         <i class="fa fa-twitter"></i>
     </a>
     <a href="">
         <i class="fa fa-google-plus"></i>
     </a>
     <a href="">
         <i class="fa fa-linkedin"></i>
     </a>
     <a href="">
         <i class="fa fa-instagram"></i>
     </a>
 </div>
 <!-- /.social-block -->
```




Of course, you can write your own styles to override the ones in the CSS.
You can even mess with them, they're just there as a starting point so we're not re-inventing the wheel every time!

I've only written styles for a few social media sites currently, more will be added if needed in time.