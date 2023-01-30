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

Line

Here are 3 examples of exactly the same line being drawn...; only using 3 slightly different methods to do it.  
The first example using pure XML code; and, the other 2 examples do employ the use of XML/intermixed with CSS code.    

&lt;line x1="10" y2="10" x2="25" y2="70" stroke="black" stroke-width="4"&gt;    
&lt;line x1="10" y2="10" x2="25" y2="70" style="stroke:black;stroke-width:4"&gt;     
&lt;line x1="10" y2="10" x2="25" y2="70" style="stroke:rbg(0,0,0);stroke-width:4"&gt;       

This program demonstrates how to draw a square using 4 straight lines...   

&lt;svg width="100"   
     height="100"  
     style="border:solid black 1px;"  
&gt;  

&lt;!--draws a left vertical line going downwards--&gt;  
&lt;line x1="25" y1="25" x2="25" y2="70" stroke="black" stroke-width="1" /&gt;   

&lt;!--draws a right vertical line going downwards--&gt;  
&lt;line x1="70" y1="25" x2="70" y2="70" stroke="black" stroke-width="1" /&gt;   

&lt;!--draws a top horizontal line going across--&gt;  
&lt;line x1="25" y1="25" x2="70" y2="25" stroke="black" stroke-width="1" /&gt;   

&lt;!--draws a bottom horizontal line going across--&gt;  
&lt;line x1="25" y1="70" x2="70" y2="70" stroke="black" stroke-width="1" /&gt;   

&lt;/svg&gt;  

The first 2...x1,y1 co-ordinates indicate the start of the line;   
the last 2...x2,y2 co-ordinates indicate the end of the line;  
the x co-ordinate indicates the line's horizontal position from the left hand side of the screen;   
the y co-ordinate indicates the line's vertical position from the top side of the screen.  

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

Ellipse

&lt;ellipse cx="50" cy="50" rx="10" ry="10" style="fill:red;stroke:yellow;stroke-width:4;"&gt;  

cx, ellipse horizontal co-ordinate/(How far along from left of screen...)  
cy, ellipse vertical co-ordinate/(How far down from top of screen...)  
rx, ellipse horizontal radius  
ry, ellipse vertical radius  

-----

Rect

-----

The rect tag...which produces a rectangle shape...has the following properties...

x, rectangle horizontal position/(How far from left side of the screen...)     
y, rectangle vertical position/(How far down from top of the screen...)      
width, how wide the rectangle will be  
height, how tall the rectangle will be  
...note: all the rest of the properties can be set using CSS...    
fill, rectangle fill colour   
fill-opacity, rectangle fill colour opacity    
stroke, rectangle outline colour   
stroke-width, rectangle outline width size  
stroke-opacity, rectangle outline opacity   

&lt;rect width="300" height="100" style="fill:green;stroke-width:3;stroke:yellow"; />  
&lt;rect x=50, y=50 width="300" height="100" style="fill:rgb(0,255,0);stroke-width:3;stroke:rgb(255,255,0);" />  
&lt;rect x=50, y=50 width="300" height="100" style="fill:rgb(0,255,0);fill-opacity:0.5;stroke-width:3;stroke:rgb(255,255,0);stroke-opacity:0.1);" />  

-(**NOTE**: If no x/y co-ordinates are specified; then, the rect shape starts at 0,0.)-  

-----

Text

&lt;svg width="300" height="100"&gt;  

&lt;text x="50" y="500" fill="orange"&gt;    
SVG Graphics is really so cool...!    
&lt;/text&gt;    

&lt;/svg&gt;  

The x co-ordinate places the text horizontal position;    
the y co-ordinate places the text vertical position;   
the fill determines the text colour.  

&lt;text x="50" y="50" style="fill:orange;stroke:red;stroke-width:3;stroke-opacity:0.5;"&gt;   
SVG Graphics is so cool...!  
&lt;/text&gt;  

-(**NOTE**: There are further CSS properties you can use.)-  

-----

## Links

### Tutorials

W3Schools...

- https://www.w3schools.com/graphics/svg_intro.asp  





