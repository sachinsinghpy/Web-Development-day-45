# Web-Development-day-45
CSS Transition


CSS Transitions
CSS transitions allows you to change property values smoothly, over a given duration.

Specify the Speed Curve of the Transition
The transition-timing-function property specifies the speed curve of the transition effect.

The transition-timing-function property can have the following values:

ease - specifies a transition effect with a slow start, then fast, then end slowly (this is default)
linear - specifies a transition effect with the same speed from start to end
ease-in - specifies a transition effect with a slow start
ease-out - specifies a transition effect with a slow end
ease-in-out - specifies a transition effect with a slow start and end
cubic-bezier(n,n,n,n) - lets you define your own values in a cubic-bezier function
The following example shows some of the different speed curves that can be used:

Example
#div1 {transition-timing-function: linear;}
#div2 {transition-timing-function: ease;}
#div3 {transition-timing-function: ease-in;}
#div4 {transition-timing-function: ease-out;}
#div5 {transition-timing-function: ease-in-out;}
Delay the Transition Effect
The transition-delay property specifies a delay (in seconds) for the transition effect.

The following example has a 1 second delay before starting:

Example
div {
  transition-delay: 1s;
}
Transition + Transformation
The following example adds a transition effect to the transformation:

Example
div {
  transition: width 2s, height 2s, transform 2s;
}
More Transition Examples
The CSS transition properties can be specified one by one, like this:

Example
div {
  transition-property: width;
  transition-duration: 2s;
  transition-timing-function: linear;
  transition-delay: 1s;
}
or by using the shorthand property transition:

Example
div {
  transition: width 2s linear 1s;
}




Property	Description
transition	A shorthand property for setting the four transition properties into a single property
transition-delay	Specifies a delay (in seconds) for the transition effect
transition-duration	Specifies how many seconds or milliseconds a transition effect takes to complete
transition-property	Specifies the name of the CSS property the transition effect is for
transition-timing-function	Specifies the speed curve of the transition effect
