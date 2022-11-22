# Processing: Color

## Color
- Color is also a datatype in Processing to store colors.
- They may be assigned with the get() or the color() function.

## color()
- Creates color for storing variables in the color datatype.
- Interpreted as RGB or HSB depending on the colorMode.

### background()
- background(r,g,b) paints the whole screen in one color
	- If background is places after other functions, it will paint over them.
	- Alpha parameter for transparency is not able to be used with background colors.

### fill() and stroke()
- Outline of a shape is called a *Stroke*
- Inside of a shape is called *Fill*
- Fill and Stroke go before the function call of the shape.
- fill(255) = fill(255,255,255)

All  can different number of total arguments. 
1. Grayscale
2. Grayscale,Transparency
3. R,G,B
4. R,G,B,A

### Colormode
This function is used to change the numerical range used to specify colors and switch color systems.
-	The default is colorMode(RGB, 255, 255, 255)
-	You could change colorMode(RGB, 1.0) will specify those values to be in the range between 0 - 1.
-	Another ColorMode is HSB, meaning Hue, Saturation and Brightness.

#processing
#color

