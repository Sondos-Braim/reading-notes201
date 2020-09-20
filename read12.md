-	Accessing data in tables and lists is not so easy. An easier way to display data on your website is by using charts. However, creating these data might not be as easy as you think it would be.

-	In order to create the chart, you need to use the `canvas` element in the HTML file.

-	But first we need to install Chart.js.

-	The canvas element takes two attributes which are the width and height attributes.

-	The id attribute also can be applied to the canvas which will help with accessing the chart in the DOM.

-	The canvas can be style the same way other elements are. But the canvas starts out as transparent and needs to be styled.

-	Some older browsers cannot access the canvas so we need to do an alternative for them using fallback content.

-	The `canvas` element needs a closing tag.

-	You need to get the content from the javascript rendering but before that the chart would be empty.

-	You also need to get the id from HTML file so that you can create the chart in the place of that `canvas` element.

-	The canvas has a grid that actually has the position of the canvas and we can control it.

-	All of the shapes that the canvas can take are done by combining more than one path. We draw the path by joining more than one point together.

-	You can also draw lines by using the `lineTo()` method.

-	we use the `arc()` or `arcTo()` methods to draw circles.

-	When you add a `rect()` method, you can do a rectangle with the open path.

-	**There are two methods to color the shapes. `fillStyle` and `strokeStyle`:**

-	`fillStyle` = color
Sets the style used when filling shapes.

-	`strokeStyle` = color
Sets the style for shapes' outlines.

-	You can also make the shape transparent by setting the `globalAlpha` property.

-	**We have a lot of properties that are used to style lines.**

-	`linewidth` = value
Sets the width of lines drawn in the future.

-	`lineCap` = type
Sets the appearance of the ends of lines.

-	`lineJoin` = type
Sets the appearance of the "corners" where lines meet.

-	`miterLimit` = value
Establishes a limit on the miter when two lines join at a sharp angle, to let you control how thick the junction becomes.

-	`getLineDash()`
Returns the current line dash pattern array containing an even number of non-negative numbers.

-	`setLineDash`(segments)
Sets the current line dash pattern.

-	`lineDashOffset` = value
-	Specifies where to start a dash array on a line.

-	**In order to create a pattern that will repeat the same thing, we can use a for loop or, an easier way, we can use the `createPattern()` method.**

-	`repeat`
Tiles the image in both vertical and horizontal directions.

-	`repeat-x`
Tiles the image horizontally but not vertically.

-	`repeat-y`
Tiles the image vertically but not horizontally.

-	`no-repeat`
Doesn't tile the image. It's used only once.

-	**Using shadow to the images will create a huge change in the design, we can make shadows using four properties.**

-	`shadowOffsetX = float`
Indicates the horizontal distance the shadow should extend from the object. This value isn't affected by the transformation matrix. The default is 0.

-	`shadowOffsetY = float`
Indicates the vertical distance the shadow should extend from the object. This value isn't affected by the transformation matrix. The default is 0.

-	`shadowBlur = float`
Indicates the size of the blurring effect; this value doesn't correspond to a number of pixels and is not affected by the current transformation matrix. The default value is 0.

-	`shadowColor = color`
A standard CSS color value indicating the color of the shadow effect; by default, it is fully-transparent black.

-	**When you have texts on your canvas and you want to style them, use these properties:**

-	`font = value`
The current text style being used when drawing text. This string uses the same syntax as the CSS font property. The default font is 10px sans-serif.

-	`textAlign = value`
Text alignment setting. Possible values: start, end, left, right or center. The default value is start.

-	`textBaseline = value`
Baseline alignment setting. Possible values: top, hanging, middle, alphabetic, ideographic, bottom. The default value is alphabetic.

-	`direction = value`
Directionality. Possible values: ltr, rtl, inherit. The default value is inherit.


