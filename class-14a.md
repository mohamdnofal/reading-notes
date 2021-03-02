# TRANSFORMS

- The transform property comes in two different settings, two-dimensional and three-dimensional. Each of these come with their own individual properties and values.

***Transform Syntax:***

- The actual syntax for the transform property is quite simple, including the transform property followed by the value. The value specifies the transform type followed by a specific amount inside parentheses.

**2D Transforms:**

- Elements may be distorted, or transformed, on both a two-dimensional.

1 - 2D Rotate:

- The transform property accepts a handful of different values. The rotate value provides the ability to rotate an element from 0 to 360 degrees. Using a positive value will rotate an element clockwise, and using a negative value will rotate the element counterclockwise. The default point of rotation is the center of the element, 50% 50%, both horizontally and vertically.

2- 2D Scale:

- Using the scale value within the transform property allows you to change the appeared size of an element. The default scale value is 1, therefore any value between .99 and .01 makes an element appear smaller while any value greater than or equal to 1.01 makes an element appear larger.

3- 2D Translate:

- The translate value works a bit like that of relative positioning, pushing and pulling an element in different directions without interrupting the normal flow of the document. Using the translateX value will change the position of an element on the horizontal axis while using the translateY value will change the position of an element on the vertical axis.

4- 2D Skew:

- The last transform value in the group, skew, is used to distort elements on the horizontal axis, vertical axis, or both. The syntax is very similar to that of the scale and translate values. Using the skewX value distorts an element on the horizontal axis while the skewY value distorts an element on the vertical axis. To distort an element on both axes the skew value is used, declaring the x axis value first, followed by a comma, and then the y axis value.%p

**Combining Transforms:**

- It is common for multiple transforms to be used at once, rotating and scaling the size of an element at the same time for example. In this event multiple transforms can be combined together. To combine transforms, list the transform values within the transform property one after the other without the use of commas.

**Transform Origin:**

- The transform-origin property can accept one or two values. When only one value is specified, that value is used for both the horizontal and vertical axes. If two values are specified, the first is used for the horizontal axis and the second is used for the vertical axis.

**Perspective:**

- The perspective of an element can be set in two different ways. One way includes using the perspective value within the transform property on individual elements, while the other includes using the perspective property on the parent element residing over child elements being transformed.

--- 

**3D Transforms:**

- Axis along which we can transform elements. Using three-dimensional transforms we can change elements on the z axis, giving us control of depth as well as length and width.

**Transitions & Animations:**

- Animations within CSS3 allow the appearance and behavior of an element to be altered in multiple keyframes. Transitions provide a change from one state to another, while animations can set multiple points of transition upon different keyframes.

***Transitions:***

There are four transition related properties in total, including transition-property, transition-duration, transition-timing-function, and transition-delay. Not all of these are required to build a transition, with the first three are the most popular.

1- Transition Demo:

- The box will change its background color over the course of 1 second in a linear fashion.

2- Transitional Property:

- The background property is identified in the transition-property value. Here the background property is the only property that will change over the duration of 1 second in a linear fashion.

3- Transition Duration:

- The duration in which a transition takes place is set using the transition-duration property. The value of this property can be set using general timing values, including seconds (s) and milliseconds (ms). These timing values may also come in fractional measurements.

4- Transition Delay:

-  The delay sets a time value, seconds or milliseconds, that determines how long a transition should be stalled before executing. As with all other transition properties, to delay numerous transitions, each delay can be declared as comma separated values.

**Animations:**

- Transitions do a great job of building out visual interactions from one state to another, and are perfect for these kinds of single state changes. However, when more control is required, transitions need to have multiple states. In return, this is where animations pick up where transitions leave off.

***Animations Keyframes:***

- To set multiple points at which an element should undergo a transition, use the @keyframes rule. The @keyframes rule includes the animation name, any animation breakpoints, and the properties intended to be animated.

***Customizing Animations:***

- Animations also provide the ability to further customize an element’s behavior, including the ability to declare the number of times an animation runs, as well as the direction in which an animation completes.

---

**8 SIMPLE CSS3 TRANSITIONS THAT WILL WOW YOUR USERS:**

1-  Fade in:

- Having things fade in is a fairly common request from clients. It’s a great way to emphasize functionality or draw attention to a call to action.

2- Change color:

- Animating a change of color used to be unbelievably complex, with all kinds of math involved in calculating separate RGB values and then recombining them.

3- Grow & Shrink:

- To grow an element, you used to have to use its width and height, or its padding. But now we can use CSS3’s transform to enlarge.

4- Rotate elements:

- CSS transforms have a number of different uses, and one of the best is transforming the rotation of an element.

5- Square to circle:

- A really popular effect at the moment is transitioning a square element into a round one, and vice versa. With CSS, it’s a simple effect to achieve, we just transition the border-radius property.

6- 3D shadow:

- 3D shadows were frowned upon for a year or so, because they weren’t seen as compatible with flat design, which is of course nonsense, they work fantastically well to give a user feedback on their interactions and work with flat, or fake 3D interfaces.

7- Swing:

- Not all elements use the transition property. We can also create highly complex animations using @keyframes, animation and animation-iteration.

8- Inset border:

- One of the hottest button styles right now is the ghost button; a button with no background and a heavy border. We can of course add a border to an element simply, but that will change the element’s position. We could fix that problem using box sizing, but a far simpler solution is the transition in a border using an inset box shadow.