# svg.textwrap.js
This is a plugin for the [svg.js](http://svgjs.com) library to do a best possible wrap on the SVG.Text element's specified width.

Svg.textwrap.js is licensed under the terms of the MIT License.

## Usage

Include this plugin after including svg.js in your html document. Do not forget to specify the width of the text element that is to be wrapped, otherwise no wrapping will occur.

If this plugin is used, by defualt all text items are going to be text wrapped. To avoid text wraping on an element there are two options:

-If no width is set for the SVG.Text object at creation time, no wrapping will occure.

-If widh is specified for a given element, it's textWrapped flag can be toggled throgh it's ```javascript
textWrapped({boolean} ) ``` method. This allows fine-grained text wrap adjustments, and runtime text wrap update.

The plugin fits in to the framework, so all other things work the same as specified in the SVG.Text documentation.

## Dependencies
There are no dependencies on other plugins.
