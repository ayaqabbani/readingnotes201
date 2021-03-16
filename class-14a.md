# Transforms
CSS3 came new ways to position and alert elements.
Now general layout techniques can be revisited with alternative ways to size, position, and change elements.

# Transform Syntax
The actual syntax for the transform property is quite simple, including the transform property followed by the value.
The value specifies the transform type followed by a specific amount inside parentheses.

## 2D Transforms
Elements may be distorted, or transformed, on both a two-dimensional plane or a three-dimensional plane. Two-dimensional transforms work on the x and y axes, known as horizontal and vertical axes. Three-dimensional transforms work on both the x and y axes, as well as the z axis. 
* 2D Scale 
Using the scale value within the transform property allows you to change the appeared size of an element. 

* 2D Translate 
the translate value works a bit like that of relative positioning, pushing and pulling an element in different directions without interrupting the normal flow of the document.

* 2D Skew 
The last transform value in the group, skew, is used to distort elements on the horizontal axis, vertical axis, or both. The syntax is very similar to that of the scale and translate values.

* Combining Transforms 
It is common for multiple transforms to be used at once, rotating and scaling the size of an element at the same time for example, In this event multiple transforms can be combined together. To combine transforms, list the transform values within the transform property one after the other without the use of commas.

* Transform Origin 
As previously mentioned, the default transform origin is the dead center of an element, both 50% horizontally and 50% vertically. To change this default origin position the transform-origin property may be used.

* Perspective 
In order for three-dimensional transforms to work the elements need a perspective from which to transform. The perspective for each element can be thought of as a vanishing point, similar to that which can be seen in three-dimensional drawings.

## 3D Transforms
Working with two-dimensional transforms we are able to alter elements on the horizontal and vertical axes, however there is another axis along which we can transform elements. Using three-dimensional transforms we can change elements on the z axis, giving us control of depth as well as length and width.

* 3D Rotate
So far we’ve discussed how to rotate an object either clockwise or counterclockwise on a flat plane. With three-dimensional transforms we can rotate an element around any axes.

* 3D Scale
By using the scaleZ three-dimensional transform elements may be scaled on the z axis. This isn’t extremely exciting when no other three-dimensional transforms are in place, as there is nothing in particular to scale.

* 3D Translate
Elements may also be translated on the z axis using the translateZ value. A negative value here will push an element further away on the z axis, resulting in a smaller element. Using a positive value will pull an element closer on the z axis, resulting in a larger element.

* 3D Skew
Skew is the one two-dimensional transform that cannot be transformed on a three-dimensional scale. Elements may be skewed on the x and y axis, then transformed three-dimensionally as wished, but they cannot be skewed on the z axis.

# Transform Style
On occasion three-dimensional transforms will be applied on an element that is nested within a parent element which is also being transformed.

# Backface Visibility
When working with three-dimensional transforms, elements will occasionally be transformed in a way that causes them to face away from the screen. This may be caused by setting the rotateY(180deg) value for example. By default these elements are shown from the back.

# Transitions & Animations
One evolution with CSS3 was the ability to write behaviors for transitions and animations. Front end developers have been asking for the ability to design these interactions within HTML and CSS, without the use of JavaScript or Flash, for years. Now their wish has come true.

* Transitions
As mentioned, for a transition to take place, an element must have a change in state, and different styles must be identified for each state. The easiest way for determining styles for different states is by using the :hover, :focus, :active, and :target pseudo-classes.

* Transitional Property
The transition-property property determines exactly what properties will be altered in conjunction with the other transitional properties. By default, all of the properties within an element’s different states will be altered upon change. However, only the properties identified within the transition-property value will be affected by any transitions.

* Transition Duration
The duration in which a transition takes place is set using the transition-duration property. The value of this property can be set using general timing values, including seconds (s) and milliseconds (ms). These timing values may also come in fractional measurements, .2s for example.

* Transition Timing
The transition-timing-function property is used to set the speed in which a transition will move. Knowing the duration from the transition-duration property a transition can have multiple speeds within a single duration. A few of the more popular keyword values for the transition-timing-function property include linear, ease-in, ease-out, and ease-in-out.

* Transition Delay
On top of declaring the transition property, duration, and timing function, you can also set a delay with the transition-delay property. The delay sets a time value, seconds or milliseconds, that determines how long a transition should be stalled before executing. 

# Shorthand Transitions
Declaring every transition property individually can become quite intensive, especially with vendor prefixes. Fortunately there is a shorthand property, transition, capable of supporting all of these different properties and values. Using the transition value alone, you can set every transition value in the order of transition-property, transition-duration, transition-timing-function, and lastly transition-delay. Do not use commas with these values unless you are identifying numerous transitions.

# Animations
Transitions do a great job of building out visual interactions from one state to another, and are perfect for these kinds of single state changes. However, when more control is required, transitions need to have multiple states.
* Animations Keyframes
To set multiple points at which an element should undergo a transition, use the @keyframes rule.
* Animation Name
Once the keyframes for an animation have been declared they need to be assigned to an element. To do so, the animation-name property is used with the animation name, identified from the @keyframes rule, as the property value.

# Customizing Animations
Animations also provide the ability to further customize an element’s behavior, including the ability to declare the number of times an animation

# Shorthand Animations
Fortunately animations, just like transitions, can be written out in a shorthand format. This is accomplished with one animation property, rather than multiple declarations.

# 8 SIMPLE CSS3 TRANSITIONS THAT WILL WOW YOUR USERS
CSS3 has introduced countless possibilities for UX designers, and the best thing about them is that the coolest parts are really simple to implement.
1. Fade in
Having things fade in is a fairly common request from clients. It’s a great way to emphasize functionality or draw attention to a call to action.

2. Change color
Animating a change of color used to be unbelievably complex, with all kinds of math involved in calculating separate RGB values and then recombining them. 

3. Grow & Shrink
To grow an element, you used to have to use its width and height, or its padding. But now we can use CSS3’s transform to enlarge, Shrinking an element is as simple as growing it.

4. Rotate elements
CSS transforms have a number of different uses, and one of the best is transforming the rotation of an element.

5. Square to circle
A really popular effect at the moment is transitioning a square element into a round one, and vice versa.

6. 3D shadow
3D shadows were frowned upon for a year or so, because they weren’t seen as compatible with flat design, which is of course nonsense, they work fantastically well to give a user feedback on their interactions and work with flat, or fake 3D interfaces.

7. Swing
Not all elements use the transition property. We can also create highly complex animations using @keyframes, animation and animation-iteration.

8. Inset border
One of the hottest button styles right now is the ghost button; a button with no background and a heavy border.
We can of course add a border to an element simply, but that will change the element’s position. We could fix that problem using box sizing, but a far simpler solution is the transition in a border using an inset box shadow.