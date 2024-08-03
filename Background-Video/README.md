box-sizing: This property specifies how the total width and height of an element are calculated, including its padding and border.

There are two main values for box-sizing:

content-box: This is the default value. The width and height properties (and respective min/max properties) apply only to the element's content. Padding and border are added outside of the content's width and height, increasing the overall size of the element.

border-box: With this value, the width and height properties (and respective min/max properties) include the content, padding, and border. This means that padding and border are included within the specified width and height, and do not increase the element's overall size.

For content-box:

The content width is 200px.
Adding padding (20px on each side) makes the total width 240px.
Adding the border (10px on each side) makes the total width 260px.

For border-box:

The total width is set to 200px.
The padding (20px on each side) and border (10px on each side) are included within the 200px width.
Thus, the content area width is reduced to accommodate the padding and border within the specified total width.

vh = viewport height eg. 10vh == 10%

linear-gradient: This is a function that creates a linear gradient image, which is a smooth transition between two or more colors along a straight line.

top and bottom padding 0px. right and left padding 5%

-webkit-text-stroke: 2px white;: This is a webkit-specific property that adds a stroke (outline) to the text.

2px: The width of the stroke.
white: The color of the stroke.
color: transparent;: This makes the fill color of the text transparent, meaning the inside of the text characters will be invisible, but the stroke will still be visible.

z-index: -1;: This property specifies the stack order of the element. Elements with a higher z-index value will be in front of those with a lower.

@media (min-aspect-ratio: 16/9): This media query applies styles when the aspect ratio of the viewport is at least 16:9 (wider than 16:9 or exactly 16:9). This means the viewport is relatively wide compared to its height.

@media (max-aspect-ratio: 16/9): This media query applies styles when the aspect ratio of the viewport is at most 16:9 (narrower than 16:9 or exactly 16:9). This means the viewport is relatively tall compared to its width.

For wider viewports (aspect ratio >= 16:9), the video will take the full width of the container and adjust its height accordingly.
For taller viewports (aspect ratio <= 16:9), the video will take the full height of the container and adjust its width accordingly.