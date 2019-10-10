# ShadowBox component
This component shows a rectangle with a configurable drop shadow and colouring edge.

## Properties
Here are the properties available to configure the box:
- **ShadowOffsetX** (number) = horizontal position of the shadow (positive: to the right; negative: to the left)
- **ShadowOffsetY** (number) = vertical position of the shadow (positive: to the bottom; negative: to the top)
- **ShadowBlur** (number) = integer value to specify how much the shadow should be blurred
- **ShadowColor** (string) = color for the shadow (color can be: color name, #rrggbb or rgb(rr,gg,bb))
- **ShadowOpacity** (number) = value between 0 and 1 to specify the shadow opacity (0 is transparent, 1 is opaque)
- **BoxFill** (string) = fill color for the inner box (color can be: color name, #rrggbb or rgb(rr,gg,bb))
- **BoxOpacity** (number) = value between 0 and 1 to specify the inner box fill color opacity (0 is transparent, 1 is opaque)
- **BoxBorderWidth** (number) = width value for the inner box border (in pixels)
- **BoxBorderColor** (string) = color for the inner box border (color can be: color name, #rrggbb or rgb(rr,gg,bb))
- **ShowEdge** (boolean) = displays a colouring edge inside the box
- **EdgePosition** (string) = position of the colouring edge (values can be: top, right, bottom, left)
- **EdgeWidth** (number) = width of the colouring edge (in pixels)
- **EdgePadding** (number) = padding between the inner box border and the colouring edge (in pixels)
- **EdgeColor** (string) = color for the colouring edge (color can be: color name, #rrggbb or rgb(rr,gg,bb))

### Examples
Using all these properties can allow you to create from simple box shadows to nice visual cards...

Drop shadow placed behind a text input box:
![TextInputDropShadow](images/TextBoxDropShadow.gif)

Nice visual cards:
![VisualCard1](images/images/ShadowBoxVisualCard1.png)

![VisualCard1](images/images/ShadowBoxVisualCard2.png)

![VisualCard1](images/images/ShadowBoxVisualCard3.png)