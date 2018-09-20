# HtmlWhitespaceEliminatorToggle
This is an extension which toggles HTML file whitespace.

Convert:

 - `>(\r?\n\s*)<` --> `$1><`

Revert

 - `(\r?\n\s*)><` --> `>$1<`.

The extension will default to the first conversion if the file has mixed whitespace.

The default keyboard shortcut to both convert and revert is `Ctrl+Shift+J`.