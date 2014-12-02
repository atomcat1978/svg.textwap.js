# svg.textwrap.js
This is a plugin for the [svg.js](http://svgjs.com) library that overrides `SVG.Text`'s default `text` and `tspan` methods so as to support line wrapping.

svg.textwrap.js is licensed under the terms of the MIT License.

## Usage

Include this plugin after including svg.js in your html document. Do not forget to specify the `width` of the text element that is to be wrapped, otherwise no wrapping will occur.

If this plugin is used, then by default all text items will be text wrapped. To avoid text wrapping on an element there are two options:

* If no `width` is set for the `SVG.Text` object at creation time, no wrapping will occur.

* If a `width` is specified for a given element, wrapping for that element can be toggled through the `{element}.textWrapped({boolean})` method. This allows fine-grained text wrap adjustments and runtime text wrap update.

The plugin complies with the framework, so all methods specified in the [official documentation](http://documentup.com/wout/svg.js#text) (should) work as expected.

## Dependencies
There are no dependencies, other than svg.js itself.
