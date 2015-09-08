At every moment, when you select an HTML element, either from the code or using the inspect tool it will show in the style panel (1) all the styles that apply to it.

![](.guides/img/elements-panel/style-of-an-element.png)

## The Styles panel

There are 4 zones in the Styles panel

1. The CSS style sources.
1. The box view which displays in blue the size of the element, its padding (green), its border (yellow) and its margins (orange).
1. The Computed styles which display the final computed styles for the element.
1. The Rendered Fonts.

![](.guides/img/elements-panel/the-style-panel.png)

## (1) CSS style sources

 1. Inline style attached to the element (here there is none).
 1. Style from the external stylesheets, along with the position in the file, here : `style.css:12` which means from line 12 in the file style.css, you can click on this and it will open style.css in the Source panel.  
 1. User agent stylesheet, which is a default style that the browser has for all HTML elements.
 1. Inherited styles, here from the body tag. You may notice in (5) that the line is crossed, meaning this property is discarded by a property that has a stronger CSS precedence, here the `color:blue;` from above wins.
 
 ![](.guides/img/elements-panel/-1--style-sources.png)
 

## (2) Box view and dimensions

Here you can see a visual representation of the dimensions of the current element, its borders, its padding and margins. We will see more in the next unit about all these properties.

![](.guides/img/elements-panel/-2--box-and-dimensions.png)


## (3) Computed styles

This is the final computed style that is applied to the element. That is the style that was selected and applied by the browser using the rules of precedence we discussed in the previous units, as well as style that might have been modified by Javascript. It is the current active style on the element.

![](.guides/img/elements-panel/-3--computed-styles.png)

## (4) Rendered Fonts

This is a list of the Fonts used to render this elements along with the number of glyphs used. This allows us to know what fonts were actually used when we defined multiple ones in the CSS. Here we defined : `Arial, sans-serif;` and we see the `Arial` was found and used.

![](.guides/img/elements-panel/-4--rendered-fonts.png)

## Try it ! 
Go back to the other browser tab we opened to play with the developer tools (or <a href="introduction/index.html" target="_blank">open it again</a> if you closed it) and put your mouse over different elements of the page to see how the Style panel changes directly and shows the styles of the different elements.