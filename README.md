# https://annazankevich.github.io/presentation/
### CSS Grid Layout 
#### Slide 1
CSS Grid layouts are definitely one of the most exciting developments in CSS for years.
#### Slide 2
It is a 2-dimensional system, meaning it can handle both columns and rows, unlike flexbox which is
largely a 1-dimensional system.
#### Slide 3
What about browser support?
As of March 2017, most browsers shipped native, unprefixed support for CSS Grid: Chrome (including on Android), Firefox, Safari (including on iOS), and Opera. Internet Explorer 10 and 11 on the other hand support it, but it's an old implementation with an outdated syntax. 
#### Slide 4
CSS Terminology
Grid container
Grid item
Grid line
Grid cell
Grid track
Grid area
Grid gap
#### Slide 5
Before diving into the concepts of Grid it's important to understand the terminology. Since the terms involved here are all kinda conceptually similar, it's easy to confuse them with one another if you don't first memorize their meanings defined by the Grid specification. But don't worry, there aren't many of them.
Grid Container
The element on which display: grid is applied. It's the direct parent of all the grid items. In this example container is the grid container.
#### Slide 6
Grid Lines
The lines between columns are called column lines.The lines between rows are called row lines.
#### Slide 7
Grid Cell
The space between two adjacent row and two adjacent column grid lines. It's a single "unit" of the grid. Here's the grid cell between row grid lines 1 and 2, and column grid lines 2 and 3.
#### Slide 8
Grid Area
The total space surrounded by four grid lines. A grid area may be comprised of any number of grid cells. Here's the grid area between row grid lines 1 and 3, and column grid lines 1 and 3.
#### Slide 9
Grid Track
The space between two adjacent grid lines. You can think of them like the columns or rows of the grid. Here's the grid track between the second and third row grid lines.
#### Slide 10
The gap CSS property sets the gaps (gutters) between rows and columns.
#### Slide 11
When should we use grid
Choose grid layout for larger scale layouts which aren’t linear in their design, but for small-scale
layouts use flexbox. If you only need to define a layout as a row or a column, then you probably need flexbox. If you
 want to define a grid and fit content into it in two dimensions — you need the grid.
#### Slide 12
Display Property
 Create a grid container
 Step 1 Define a grid
 Step 2 To find on an element where you want to a grid to appear number
 Step 3 Place items within the grid
####  Slide 13
 For create Grid Container we declare display grid or grid-inline
 Now we have a grid-contaner.
 Then we decide how many rows and colums we want. We are using grid-template-columns and grid-template-rows.
#### Slide  14
Fraction
Fr is a fractional unit and 1fr is for 1 part of the available space.
#### Slide  15
The grid-template-areas property specifies areas within the grid layout.
You can name grid items by using the grid-area property, and then reference to the name in the
grid-template-areas property
#### Slide  16
Then you use property on individual child items and you declare the name of the area you want the element to appear
And this is allowed us to do great responsive web desigh. And you responsive code and media queries become very simple. Anyone who read this code understand all. And everything just work.
