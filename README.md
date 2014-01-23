hover
=====
###sass discoveries
constantly update css file: `sass --watch main.scss:main.css`

mixins can use elipses for an unknown # of arguments: `@mixin transform($type...) {}`

###css discoveries
#####transitions: 
`.example {`
`transition: [transition-property] [transition-duration] [transition-timing-function] [transition-delay]`
`;}`

#####ease:

`ease-in` will start the animation slowly, and finish at full speed.

`ease-out` will start the animation at full speed, then finish slowly.

`ease-in-out` will start slowly, be fastest at the middle of the animation, then finish slowly.

`ease` is like ease-in-out, except it starts slightly faster than it ends.

`linear` uses no easing.
