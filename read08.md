# HTML layout

## Key Concepts in Positioning Elements

* CSS treats each HTML element as if it is in its own box. This box will either be a block-level box or an inline box.

* Block-level elements start on a new line

* Inline elements flow in between surrounding text

## containing elements

If one block-level element sits inside another block-level element then the outer box is known as the containing or parent element.

### normal flow 

(position: static)

In normal flow, each block-level element sits on top of the next one. Since this is the default way in which browsers treat HTML elements, you do not need a CSS property to indicate that elements should appear in normal flow.

### Relative Positioning

(position:relative)

Relative positioning moves an element in relation to where it would have been in normal flow. For example, you can move it 10 pixels lower than it would have been in normal flow or 20% to the right.

### Absolute Positioning

(position:absolute)

When the position property is given a value of absolute, the box is taken out of normal flow and no longer affects the position of otherelements on the page.

### Fixed Positioning

(position:fixed)

Fixed positioning is a type of absolute positioning that requires the position property to have a value of fixed. It positions the element in relation to the browser window. Therefore, when a user scrolls down the page, it stays in the exact same place.

### Overlapping Elements

(z-index)

When you use relative, fixed, or absolute positioning, boxes can overlap. If boxes do overlap, the elements that appear later in the HTML code sit on top of those that are earlier in the page. If you want to control which element sits on top, you can use the z-index property.

### clearing floats

The clear property allows you to say that no element (within the same containing element) should touch the left or righthand sides of a box. It can take the following values:

* left:The left-hand side of the box should not touch any other elements appearing in the same containing element.

* right:The right-hand side of the box will not touch elements appearing in the same containing element.

* both:Neither the left nor right-hand sides of the box will touch elements appearing in the same containing element.

* none:lements can touch either side.




