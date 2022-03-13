# OfficeUIFabricIconGenerator component
This component allows one to generate the SVG code for an icon picked among the whole list of the Office UI Fabric Icons (which can be [found here](https://uifabricicons.azurewebsites.net/)). This SVG code can then be used in an *Image* control in any Power Apps application.

## How do I use it ?
Here are the instructions on how to use this component:
- **Import** the application on your tenant
- **Play** the application
- **Select** an icon, set its rotation angle and its color
- **Copy** to the clipboard the SVG code in the *Icon image data* field's blue box
- **Go** to your application's screen where you wish to use this icon
- **Add** a new *Image* control to your screen
- In the **Image** property of your *Image* control, **paste** the code your have in your clipboard

## How does it look ?
Here is a capture of how the component looks:

![ComponentCapture](images/OfficeUIFabricIconGenerator.png)

## HISTORY changes
**v1.0** [ 11-nov-2019 ]
- Initial version

**v1.1**  [ 19-nov-2019 ]
- Added icons count right next to the search box
- Added icon names below icons
- Fixed number of icon columns showed when resizing component
- Added icon rotation
- Added icon color hint
- Replace icons scroll bar with paging buttons
- Fixed larger icons width

**v2.0** [ 13-mar-2022 ]
- Added latest official icons: now 2254 icons!
- Removed component MSAPP file as the application should be used instead
- Updated use instructions above on this page
- Removed notes above on this page
- Updated capture