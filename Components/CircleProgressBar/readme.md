# CircleProgressBar component
This component is a configurable circle progress bar.

## Component properties
Here are the properties available to configure the progress bar:
- **Max** (number) = maximum value (default is **100**)
- **Value** (number) = actual progress value (default is **50**)
- **ShowLabel** (boolean) = shows/hides the label in the center (default is **True**)
- **LabelSize** (number) = font size for the label in the center (default is **20**)
- **BarBgR, BarBgG, BarBgB** (numbers) = red, green and blue components for the color of the background progress circle (the grey one on the capture above)
- **BarR, BarG, BarB** (numbers) = red, green and blue components for the color of the actual progress circle (the cyan one on the capture above)
- **BarBgWidth** (number) = width for the background progress circle
- **BarWidth** (number) = width for the actual progress circle
- **LineCapRound** (boolean) = if True, the line cap for drawing the circles is 'round', otherwise it's 'square' (default is **True**)

### Examples
Set the **LineCapRound** property of the component to **False** if you want your progress bar look like this:
![CircleProgressBar-square](images/CircleProgressBar-square.png)

### Updates
- **05-20-2019**: fixed the **ShowLabel** property that was not effective + added new **LineCapRound** property
