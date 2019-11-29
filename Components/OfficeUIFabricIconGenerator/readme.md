# OfficeUIFabricIconGenerator component
This component allows one to generate the SVG code for an icon picked among the whole list of the Office UI Fabric Icons (which can be [found here](https://uifabricicons.azurewebsites.net/)). This SVG code can then be used in an *Image* control in any Power Apps application.

## How do I use it ?
Here are the instructions on how to use this component:
- First, **import** the component into your Power Apps application
- Then, **create** a new screen in your application
- On that new screen, **add** the *OfficeUIFabricIconGenerator* component and give it the maximum size it can have on the screen
- When the component is selected, on the right-hand panel **activate** its *Initialize* property
- **Play** your app, being on the screen with the component
- **Select** an icon and, if needed, set its rotation angle and enter its color in the *Icon color* field
- Now, **copy** to the clipboard the SVG code in the *Icon image data* field's blue box
- Then, **go** to your application's screen where you wish to use this icon
- **Add** a new *Image* control to your screen
- In the **Image** property of your *Image* control, **paste** the code your have in your clipboard

TADAAAA! There is your Office UI Fabric icon that you can use wherever you want in your application!

## How does it look ?
Here is a capture of how the component looks:

![ComponentCapture](images/OfficeUIFabricIconGenerator.png)

## IMPORTANT notes
**NOTE 1** - This component is **not yet** compatible with Power Apps applications that use the *Phone* layout. This will be available in a future update.

**NOTE 2** - Once you have finished making your application **remove** the screen containing the *OfficeUIFabricIconGenerator* component to reduce the size of your application.

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