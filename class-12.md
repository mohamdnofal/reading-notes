# CHART.JS

- Charts are far better for displaying data visually than tables and have the added benefit that no one is ever going to press-gang them into use as a layout tool. They’re easier to look at and convey data quickly.

- A great way to get started with charts is with Chart.js, a JavaScript plugin that uses HTML5’s canvas element to draw the graph onto the page. 

**Creating a Chart:**

- It's easy to get started with Chart.js. All that's required is the script included in your page along with a single `<canvas>` node to render the chart.

**`<canvas>` element:**

- At first sight a `<canvas>` looks like the `<img>` element, with the only clear difference being that it doesn't have the src and alt attributes. Indeed, the `<canvas>` element has only two attributes, width and height.

- The `<canvas>` element differs from an `<img>` tag in that, like for `<video>`,`<audio>`, or `<picture>` elements, it is easy to define some fallback content, to be displayed in older browsers not supporting it, like versions of Internet Explorer earlier than version 9 or textual browsers. You should always provide fallback content to be displayed by those browsers.

**Drawing shapes with canvas:**

- Unlike SVG, `<canvas>` only supports two primitive shapes: rectangles and paths (lists of points connected by lines). All other shapes must be created by combining one or more paths. Luckily, we have an assortment of path drawing functions which make it possible to compose very complex shapes.

**Applying styles and colors:**

- Colors: Up until now we have only seen methods of the drawing context. If we want to apply colors to a shape, there are two important properties we can use: fillStyle and strokeStyle.

**Drawing text:**

- The canvas rendering context provides two methods to render text:

1- ***fillText(text, x, y [, maxWidth]):***

- Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.

2- ***strokeText(text, x, y [, maxWidth]):***

- Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.