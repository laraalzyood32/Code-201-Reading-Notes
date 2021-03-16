# transform :
With CSS3 came new ways to position and alter elements. Now general layout techniques can be revisited with alternative ways to size, position, and change elements.
All of these new techniques are made possible by the transform property
# The transform property comes in two different settings :
1. two-dimensional : Two-dimensional transforms work on the x and y axes, known as horizontal and vertical axes
2.three-dimensional:  transforms work on both the x and y axes, as well as the z axis. These three-dimensional transforms help define not only the length and width of an element,
 but also the depth.
# The actual syntax for the transform property is quite simple, including the transform property followed by the value. The value specifies the transform type followed by
a specific amount inside parentheses.
 Example : transform: scale(1.5);
 
 # 2D Rotate
The transform property accepts a handful of different values. The rotate value provides the ability to rotate an element from 0 to 360 degrees.
Using a positive value will rotate an element clockwise, and using a negative value will rotate the element counterclockwise.

# 2D Scale
Using the scale value within the transform property allows you to change the appeared size of an element. The default scale value is 1.

# 2D Translate
The distance values used within the translate value may be any general length measurement, most commonly pixels or percentages. 
Positive values will push an element down and to the right of its default position while negative values will pull an element up and to the left of its default position.

# Combining Transforms
It is common for multiple transforms to be used at once, rotating and scaling the size of an element at the same time

# Using multiple transform declarations will not work, as each declaration will overwrite the one above it. The behavior in that case would be the same as if you were to set
the height of an element numerous times.

# Transform Origin
As previously mentioned, the default transform origin is the dead center of an element, both 50% horizontally and 50% vertically. To change this default origin position 
the transform-origin property may be used.The transform-origin property can accept one or two values. When only one value is specified, that value is used for 
both the horizontal and vertical axes. If two values are specified, the first is used for the horizontal axis and the second is used for the vertical axis.

# Transform Origin
As previously mentioned, the default transform origin is the dead center of an element, both 50% horizontally and 50% vertically. To change this default origin position the transform-origin property may be used.

The transform-origin property can accept one or two values. When only one value is specified, that value is used for both the horizontal and vertical axes. If two values are specified, 
the first is used for the horizontal axis and the second is used for the vertical axis.

# 3D dimension 
# 3D rotate : three-dimensional transforms we can rotate an element around any axes. To do so, we use three new transform values,
 including rotateX, rotateY, and rotateZ.
 # 3D Scale
By using the scaleZ three-dimensional transform elements may be scaled on the z axis.

 # 3D Translate
Elements may also be translated on the z axis using the translateZ value. A negative value here will push
 an element further away on the z axis, resulting in a smaller element. Using a positive value will pull 
 an element closer on the z axis, resulting in a larger element.

 # With CSS3 transitions you have the potential to alter the appearance and behavior of 
 an element whenever a state change occurs, such as when it is hovered over, focused on, 
 active, or targeted. Animations within CSS3 allow the appearance and behavior of an element 
 to be altered in multiple keyframes. Transitions provide a change from one state to another,
  while animations can set multiple points of transition upon different keyframes.

  # The easiest way for determining styles for different states is by using the :pseudo-classes.
  hover, :focus, :active, and :target .
  # Transitional Property
The transition-property determines exactly what properties will be altered in conjunction with 
the other transitional properties .
 # Transition Duration
The duration in which a transition takes place is set using the transition-duration property.
 The value of this property can be set using general timing values, including seconds (s)
  and milliseconds (ms). 
  # Transition Timing
The transition-timing-function property is used to set the speed in which a transition will move. 
# Transition Delay :
The delay sets a time value, seconds or milliseconds, that determines how long
 a transition should be stalled before executing.

 # Animations
Transitions do a great job of building out visual interactions from one state to another,
 and are perfect for these kinds of single state changes.
 # Customizing Animations
Animations also provide the ability to further customize an element’s behavior, including the ability to declare the number of times an animation runs, as well as the direction in which an animation completes.

Animation Iteration :
By default, animations run their cycle once from beginning to end and then stop. 
To have an animation repeat itself numerous times .
# Animation Direction
 you may also declare the direction an animation completes using the animation-direction property
