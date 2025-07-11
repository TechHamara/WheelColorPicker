<div align="center">
<h1><kbd>🧩 WheelColorPicker</kbd></h1>
An extension for MIT App Inventor 2.<br>
A color picker component developed by TechHamara using Fast technology, offering a user-friendly interface for selecting colors with various options such as wheel type, density, and sliders for lightness and alpha.<a href='https://t.me/techhamara91/' target='_blank'>Telegram</a> | <a href='https://github.com/TechHamara/' target='_blank'>GitHub</a><br><a href='https://buymeacoffee.com/techhamara/extras/' target='_blank'>BuyMeaCoffee</a> | <a href='https://m.youtube.com/c/TECHHAMARA?sub_confirmation=1' target='_blank'>YouTube</a><br><a href='https://github.com/TechHamara/Th_Free_Extensions' target='_blank'><small><u>Find More Extension</u></small></a><br><a href='https://github.com/TechHamara/Th_Extensions_List/blob/main/LICENSE.md#terms-and-conditions-for-the-extension' target='_blank'><small><u>Terms & Conditions</u></small></a>
</div>

## 📝 Specifications
* **
📦 **Package:** io.th.wheelcolorpicker
💾 **Size:** 43.64 KB
⚙️ **Version:** 1.0
📱 **Minimum API Level:** 21
📅 **Updated On:** [date=2025-07-11 timezone="Asia/Calcutta"]
💻 **Built & documented using:** [FAST](https://community.appinventor.mit.edu/t/fast-an-efficient-way-to-build-extensions/129103?u=jewel) <small><mark>v2.8.4</mark></small>

## <kbd>Events:</kbd>
**WheelColorPicker** has total 3 events.

### ColorChanged
Event raised when the color is changed

| Parameter | Type
| - | - |
| newColor | number

### ColorSelected
Event raised when the color is selected

| Parameter | Type
| - | - |
| selectedColor | number

### WheelTypeChanged
Event raised when the wheel type is changed

| Parameter | Type
| - | - |
| newType | text

## <kbd>Methods:</kbd>
**WheelColorPicker** has total 18 methods.

### Create
Initialize inside an arrangement.

| Parameter | Type
| - | - |
| arrangement | component

### ColorHex
Get the color of the picker as a hex string

* Return type: `text`

### ColorRGB
Set the color from RGB values

| Parameter | Type
| - | - |
| red | number
| green | number
| blue | number

### ColorRGBA
Set the color from RGBA values

| Parameter | Type
| - | - |
| red | number
| green | number
| blue | number
| alpha | number

### Red
Get the red component of the current color

* Return type: `number`

### Green
Get the green component of the current color

* Return type: `number`

### Blue
Get the blue component of the current color

* Return type: `number`

### AlphaValue
Get the alpha component of the current color

* Return type: `number`

### ColorHSV
Set the color from HSV values

| Parameter | Type
| - | - |
| hue | number
| saturation | number
| value | number

### Hue
Get the hue component of the current color

* Return type: `number`

### Saturation
Get the saturation component of the current color

* Return type: `number`

### Value
Get the value component of the current color

* Return type: `number`

### FlowerWheel
Set the wheel type to FLOWER

### CircleWheel
Set the wheel type to CIRCLE

### WheelTypeString
Get the current wheel type as string

* Return type: `text`

### SelectColor
Select the current color

### ShowDialog
Show the color picker dialog

### ShowDialogWithButtons
Show the color picker dialog with custom buttons

| Parameter | Type
| - | - |
| positiveButtonText | text
| negativeButtonText | text

## <kbd>Setters:</kbd>
**WheelColorPicker** has total 14 setter properties.

### Enabled
Get or set whether the color picker is enabled

* Input type: `boolean`

### Color
Get or set the current color

* Input type: `number`

### ShowAlpha
Get or set whether to show alpha channel

* Input type: `boolean`

### Lightness
Get or set the lightness value (0.0 to 1.0)

* Input type: `number`

### Alpha
Get or set the alpha value (0.0 to 1.0)

* Input type: `number`

### WheelType
Get or set the wheel type (0 for FLOWER, 1 for CIRCLE)

* Input type: `number`
* Helper type: `Type`
* Helper enums: `Flower`, `Circle`

### Density
Get or set the density of the color wheel (2-12)

* Input type: `number`

### DialogTitle
Get or set the dialog title

* Input type: `text`

### ShowLightnessSlider
Get or set whether to show lightness slider

* Input type: `boolean`

### ShowAlphaSlider
Get or set whether to show alpha slider

* Input type: `boolean`

### ShowBorder
Get or set whether to show border

* Input type: `boolean`

### ShowColorEdit
Get or set whether to show color edit

* Input type: `boolean`

### ShowColorPreview
Get or set whether to show color preview

* Input type: `boolean`

### PickerCount
Get or set the number of color pickers (1-5)

* Input type: `number`

## <kbd>Getters:</kbd>
**WheelColorPicker** has total 14 getter properties.

### Enabled
Get or set whether the color picker is enabled

* Return type: `boolean`

### Color
Get or set the current color

* Return type: `number`

### ShowAlpha
Get or set whether to show alpha channel

* Return type: `boolean`

### Lightness
Get or set the lightness value (0.0 to 1.0)

* Return type: `number`

### Alpha
Get or set the alpha value (0.0 to 1.0)

* Return type: `number`

### WheelType
Get or set the wheel type (0 for FLOWER, 1 for CIRCLE)

* Return type: `number`

### Density
Get or set the density of the color wheel (2-12)

* Return type: `number`

### DialogTitle
Get or set the dialog title

* Return type: `text`

### ShowLightnessSlider
Get or set whether to show lightness slider

* Return type: `boolean`

### ShowAlphaSlider
Get or set whether to show alpha slider

* Return type: `boolean`

### ShowBorder
Get or set whether to show border

* Return type: `boolean`

### ShowColorEdit
Get or set whether to show color edit

* Return type: `boolean`

### ShowColorPreview
Get or set whether to show color preview

* Return type: `boolean`

### PickerCount
Get or set the number of color pickers (1-5)

* Return type: `number`

