hardreset.css
=============

hardreset.css resets all elements to look as identical as possible in all browsers by default. 

##Why?

This came to mind when I started playing with css-modules. While css-modules removes global styles through classes, browsers still apply styles at a global level which undermines the practice.

It also got me thinking about all the times I removed padding/margin from a `ul` or removed the border from an `input`. I have a design for my elements. I want my CSS to only reflect that design - not the design plus a few bits and pieces that browsers throw in here and there.

##Caveats

Forms. Forms forms forms. And all of their children. Can't do much about making those look the same as we all know, but hardreset still removes as much as possible - padding, borders etc.
