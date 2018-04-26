# Getting Started with CSS Grid 

* `display:grid` on parent element
* `grid-template-columns` on parent, can use any metric, `fr` is most common. Can also use `repeat()` here.
* `align-items`, `justify-items` on parent -OR- `align-self`, `justify-self` on child
* use `grid-gap-columns`, `grid-gap-rows`, or `grid-gap` to put space between elements. 
* pseudo-selector `nth-child()` is useful with css-grid - it can take even, odd, or the 3n+0 pattern.
* use `grid-auto-rows: minmax(100px, auto)` to set the row height to 100px min, auto max
* use `overflow-y:auto` on the child element to have it scroll for overflowing content
* use `grid-column` and `grid-row` to control the placement of children elements within the grid
* use grids within grids (gridception)
