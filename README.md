# SVG
SVG/Scalable Vector Graphics program code

SVG, allows the web page user to create both 'still' graphics/as well as, 'moving' animations.

It's possible to use SVG to draw such shapes as...

- lines
- oblongs
- squares
- circles
- ellipses
- polyline
- polygon
- path

In addition to which it's possible to combine together shapes to produce such things as: drawings/or, text messages.

-----

There are 2 main advantages to using SVG code:-

1. SVG graphics code, is all written out as being in the form of text;     
and, therefore, the file sizes can be very 'light weight'...;  
especially, when compared to other graphic file formats;  
which, in turn, means the web page both downloads and runs really 'fast'.   

2. The other most highly noticiable feature of SVG graphics is they can be 'resized' without loosing 'quality';          
which is quite unlike other 'lossy' graphic file formats such as: .jpg/.gif./-etc.;    
in other words, SVG graphics do NOT look pixelated when you either blow them up/or else, shrink them down;    
and, this is because SVG Graphics are calculated mathematically.     

-----

## Example codes

-----

The opening and closing SVG-/SVG tags...

The first thing one does when one is creating SVG Code...is to declare a pair of opening and closing 'SVG'-'/SVG' tags...;   
next, one includes both the 'width/height' properties of the box shape you wish to draw your SVG shapes in:-     

&lt;svg width="100" height="100"&gt;    
-(the rest of the svg code will be written inside here...)-  
&lt;/svg&gt;  

Or, you might wish to draw a CSS outline border to more clearly indicate where you SVG box is on the page...  

&lt;svg width="100" height="100" style="border: solid black 1px;"&gt;    
-(the rest of the svg code will be written inside here...)-  
&lt;/svg&gt;  

Alternatively, you may wish to colour in the box a certain specific colour, again, using CSS...  

&lt;svg width="100" height="100" style="background-color:red"&gt;    
-(the rest of the svg code will be written inside here...)-  
&lt;/svg&gt;  

-----

Circle

The circle has the following properties...

circle cx,cy,r,stroke,stroke-width,fill

- cx, circle horizontal co-ordinate/(How far from left side of screen...)    
- cy, circle vertical co-ordinate/(How far from top of screen...)    
- r, circle radius  
- stroke, circle outline colour  
- stroke-width, circle outline width  
- fill, circle inside colour  

&lt;circle cx="50" cy="50" r="25" stroke="yellow" stroke-width="4" fill="green" /&gt;

...will create a green circle/with a yellow outline...outline size 4 pixels in width;       
50 pixels out from the left side of the screen/50 pixels down from the top of the screen;  
with a radius size of 25 pixels.

-(**NOTE**: Because SVG is also an application of XML; therefore, it's necessary to close off any single tag with an ending forwards slash: '/'.)-  

-----

Rect

-----

The rect tag...which produces a rectangle shape...has the following properties...

-----

## Links

-----

### Tutorials

W3Schools...

- https://www.w3schools.com/graphics/svg_intro.asp  





