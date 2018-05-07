#Inheritance, Specificity, Selectors, Display Types, UI Building

CSS Inheritence .parent > .child > .grandchild
Global Tags vs Specific tags

Specificity overwrites. Think of it like a waterfall.

Top to bottom matters. Left to right matters.
If all things are equal, The class furthest to the right wins and the class closest to the bottom wins.

> '*' < elements < classes, psuedo-classes, attributes < IDs < inline styles < !important

Display Types:
`display: static`
`display: none` (The boxes are completely removed from the page as opposed to `visibility: hidden`)
`display: block`
`display: relative` - Displays box relative to its surroundings
`display: flex`
`display: inline` - displays the bare minimum of what the box can hold.
`display: inline-block` - allows block elements to sit next to each other
