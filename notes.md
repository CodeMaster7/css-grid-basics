```html
<style>
    .grid{
        display:grid;
        grid-template-columns: 1fr; <!--fr, %, px -->
        grid-template-columns: repeat(3, 1fr 2fr);
        grid-column-gap: 1em; <!-- spacing -->
        grid-row-gap: 1em; 
        grid-gap: 1em; <!-- column and row in one -->
        grid-auto-rows: 100px; <!-- row height -->
        grid-auto-rows: minmax(100px, auto); <!-- auto row height -->
    }
</style>
```


* display: grid
* grid-template-columns, measurement types
    * repeat
* viewing the grid in chrome element viewer
* grid-column-gap, grid-row-gap, grid-gap
* grid-auto-rows (row height)
* grid-auto-rows with minmax
    * overflow-y on child div to auto, hidden
* nested grid
* justify-items: (horizontal) start/center/end/stretch(default)
* align-items: (vertical) same parameters
* align-self
    * nth-child (even, odd, n3+0)
* css grid lines
* grid-template-rows
* rearrange grid with grid-lines
* overlapping elements