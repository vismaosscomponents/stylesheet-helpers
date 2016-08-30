# stylesheet-helpers - Utilities to make it easier to work with CSS stylesheets.

* `create([document]) -> { styleSheetElement, styleSheet }` - Creates and returns a new stylesheet.
* `updateProperties(document: <Document>, styleSheet: <StyleSheet>, className: <string>, properties: <field: value>)` - Updates the properties of the given styleSheet based on the given `className` and `properties`.
* `findExistingRule(document: <Document>, styleSheet: <StyleSheet>, className: <string>) -> <CssRule|null>` - Returns a rule from the given `styleSheet` based on the given `className` if it's found.

## License

MIT.
