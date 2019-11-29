# UltimateColorPicker component
This color picker component will automatically calculate a palette of light and dark shades based on a list of main colors you will provide.

![UltimateColorPicker](images/UltimateColorPicker.png)

## Features
Here is the list of features provided with this color picker:
- Customizable title
- Title can be hidden
- Customizable main colors (center row in the palette)
- Automatic light and dark shades palette based on main colors
- Customizable color square size and padding between squares
- Customizable selected color background (usefull when alpha < 1)
- Active color in color picker palette is pin-pointed by a bullet point
- Selected color can be set in Hex mode or in RGB mode
- RGB color and alpha values can be set using sliders or with the keyboard
- Output of selected color in multiple formats: Power Apps color, Hex, RGBA separated values, "RGBA(r,g,b,a)" string
- *COMING SOON* - Customizable number of shades for the palette
- *COMING SOON* - Responsive component

## Properties
Here are the properties available to configure the color picker:
### Input
- **DefaultColor** (color) = default selected color (in the form #rrggbb)
- **Title** (string) = title for the component
- **ShowTitle** (boolean) = shows or hides the component's title
- **MainColors** (table) = main colors list in the form: *Table({Value: "#rrggbb"},{Value: "#rrggbb"},...)*
- **ShadesCount** (number) = number of shades in the palette (*COMING SOON*)
- **ColorSquareSize** (number) = size, in pixels, for the palette color squares
- **ColorSquaresPadding** (number) = padding between the palette color squares
- **SelectedColorBg** (color) = color for the background behind the selected color square
### Output
- **SelectedColor** (color) = picked color value in Power Apps color format
- **Red** (number) = red value for the picked color
- **Green** (number) = green value for the picked color
- **Blue** (number) = blue value for the picked color
- **SelectedAlpha** (number) = alpha value for the picked color
- **SelectedRGB** (string) = picked color in RGBA string format: *RGBA(&lt;r&gt;,&lt;g&gt;,&lt;b&gt;,&lt;a&gt;,)*
- **SelectedHex** (string) = picked color in Hex format: *#rrggbbaa*
- **SelectedButton** (string) = button clicked (value can be: *OK* or *CANCEL*)