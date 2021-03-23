# Grid Column start:
we can devide our page into Identical sectors using Grid-templarte-rows and Grid-template-columns.<br />

### after that we can use the following commands to CSS our page using *grid*:

1. grid-column-start: will make change to vertical border from the left in the grid.
by putting the no. of sector.

2. grid-column-end: 
we can define where to end our works in which sector.<br />

#(Note: we can give grid-column-start and grid-column-end negative values.<br /> 
For example, we can set it to -1 to specify the first grid line from the right.).

>> Instead of defining a grid item based on the start and end positions of the grid lines, we can define it based on your desired column width using the span keyword. Keep in mind that span only works with positive values.


3. grid-column: is a shorthand property that can accept both values at once, separated by a slash.

* One of the things that sets CSS grids apart from flexbox is that you can easily position items in two dimensions: columns and rows. grid-row-start works much like grid-column-start except along the vertical axis.*


4. grid-area : accepts four values separated by slashes: grid-row-start, grid-column-start, grid-row-end, followed by grid-column-end.

### if grid items aren't explicitly placed with grid-area, grid-column, grid-row, etc., they are automatically placed according to their order in the source code. We can override this using the order property, which is one of the advantages of grid over table-based layout.

### Grid also introduces a new unit, the fractional fr. Each fr unit allocates one share of the available space. For example, if two elements are set to 1fr and 3fr respectively, the space is divided into 4 equal shares; the first element occupies 1/4 and the second element 3/4 of any leftover space.