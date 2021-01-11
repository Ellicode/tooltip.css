# Welcome to tooltip.css !
Tooltip.css is another library that finishes with ".css" 😑. This library is only a CSS library that can create tooltips. For a full documentation, go on the official website [here](https://www.ellicode.com/tooltip.css/).
## Installation
Tooltip.css is created by Ellicode and the CDN, too is on Ellicode. See below :arrow_down:
```html
<link rel="stylesheet" href="https://www.ellicode.com/tooltip.css/lib/tooltip.min.css">
```
## Getting started
To make a tooltip, you need to add the ```data-tooltip``` attribute and the ```.--ttip-container``` class to the tooltip element. Write the tooltip text inside this attribute. This is simple, huh? but the class is very long...
```html
<span class="--ttip-container" data-tooltip="Here is the popup!">Hover me to show the popup!</span>
```
***
⚠️ **Warning** You can't use the tooltips with an element with a ::before CSS statement. To fix that, you need to wrap the element to another span element. See below.
```html
<span class="class attributes...">element...</span>
```
:point_up: **Info** In your HTML file, the dashed underline will not appear:point_up: **Inf In your HTML file, the dashed underline will not appear
