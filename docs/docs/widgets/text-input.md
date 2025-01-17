---
id: text-input
title: Text Input
---
# Text Input

Text Input widget lets users enter and edit text.

:::tip
The Text Input should be preferred when user input is a single line of text.
:::

## How To Use Text Input Widget

<iframe height="500" src="https://www.youtube.com/embed/ke5DTJje260" title="Text Input Widget" frameborder="0" allowfullscreen width="100%"></iframe>

## Properties

### Default value

The default value that the widget will hold when the app is loaded.

### Placeholder

It specifies a hint that describes the expected value.

## Events

<div style={{textAlign: 'center'}}>

![ToolJet - Widget Reference - Text input event List](/img/widgets/text-input/events.png)

</div>

### On change
This event fires whenever the user types something on the text input.

### On Enter Pressed
This event fires whenever the user presses the enter button on keyboard after entering some text on text input component.

### On focus
This event fires whenever the user clicks inside the text input component.

### On blur
This event fires whenever the user clicks outside the text input component.

:::info
Check [Action Reference](/docs/actions/show-alert) docs to get detailed information about all the **Actions**.
:::

## Validation

### Regex

Use this field to enter a Regular Expression that will validate the password constraints.

### Min length

Enter the number for a minimum length of password allowed.

### Max length

Enter the number for the maximum length of password allowed.

### Custom validation

If the condition is true, the validation passes, otherwise returns a string that should be displayed as the error message. For example: `{{components.passwordInput1.value === 'something' ? true: 'value should be something'}}`.

### General
#### Tooltip

A Tooltip is often used to specify extra information about something when the user hovers the 
mouse pointer over the widget.

Under the <b>General</b> accordion, you can set the value in the string format. 
Now hovering over the widget will display the string as the tooltip.

<div style={{textAlign: 'center'}}>

![ToolJet - widget- button](/img/tooltip.png)

</div>

## Layout

### Show on desktop

Toggle on or off to display the widget in desktop view. You can programmatically determine the value by clicking on `Fx` to set the value `{{true}}` or `{{false}}`.
### Show on mobile

Toggle on or off to display the widget in mobile view. You can programmatically determine the value by clicking on `Fx` to set the value `{{true}}` or `{{false}}`.

## Styles

### Text Color
Use this property to set the color of the text inside the text input component. You can select the color from the color picker or set the value using Hex color code.

### Border Radius
Use this property to modify the border radius of the widget. The field expects only numerical values from `1` to `100`, and default is `0`. 

### Visibility
It is to control the visibility of the widget. If `{{false}}` the widget will not be visible after the app gets deployed. It can only have boolean values i.e. either `{{true}}` or `{{false}}`. By default, it's set to `{{true}}`.

### Disable
This property only accepts boolean values. If set to `{{true}}`, the widget will lock and become non-functional. By default, its value is set to `{{false}}`.

:::info
Check the **component specific actions** available for this component **[here](/docs/actions/control-component)**.
:::
