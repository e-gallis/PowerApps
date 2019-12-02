# ShadowBox component
This component shows a rectangle with a configurable drop shadow and colouring edge.

## Notes
v1.1: now, use the **MarginLeft**, **MarginRight**, **MarginTop** and **MarginBottom** output parameters to fit your shadow easily to your desired control.
For example:
- Let's say you have a control called *cmpColorPicker* to which you'd like to apply a shadow
- Add a ShadowBox component to your screen and set its position and size as follow:
```
    o ShadowBox.X = cmpColorPicker.X - ShadowBox.MarginLeft
    o ShadowBox.Y = cmpColorPicker.Y - ShadowBox.MarginTop
    o ShadowBox.Width = cmpColorPicker.Width + ShadowBox.MarginLeft + ShadowBox.MarginRight
    o ShadowBox.Height = cmpColorPicker.Height + ShadowBox.MarginTop + ShadowBox.MarginBottom
```

## Properties
Here are the properties available to configure the box:
### Input
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
### Output
- **MarginLeft** (number) = distance between the left border of the component and the left border of the inner box
- **MarginRight** (number) = distance between the right border of the component and the right border of the inner box
- **MarginTop** (number) = distance between the top border of the component and the top border of the inner box
- **MarginBottom** (number) = distance between the bottom border of the component and the bottom border of the inner box

## Examples
Using all these properties can allow you to create from simple box shadows to nice visual cards...

Drop shadow placed behind a text input box:

![TextInputDropShadow](images/TextBoxDropShadow.gif)

Nice visual cards where some text and icon controls have been placed in front of the shadow box:

![VisualCard1](images/ShadowBoxVisualCard1.png)

![VisualCard2](images/ShadowBoxVisualCard2.png)

![VisualCard3](images/ShadowBoxVisualCard3.png)

## HISTORY changes
**v1.0** [ 10-oct-2019 ]
- Initial publish

**v1.1**  [ 01-dec-2019 ]
- Added margins output parameters
