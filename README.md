# reStructuredText Preview package

Show the pandoc-rendered HTML markdown to the right of the current editor using
`ctrl-shift-e`

Live Update scrolls to cursor position when editing. You can also toggle scrolling preview together with editor (like StackEdit for example).

It can be activated from the editor using the `ctrl-shift-e` key-binding and is
currently enabled for `.markdown`, `.md`, `.mdown`, `.mkd`, `.mkdown`, `.ron`, `.txt` and `.rst` files.

For a better way to preview math than default `--webtex`, you can try a pandoc filter like this one: <https://gist.github.com/lierdakil/6a95278d02256a74a0fc>

## Dependency

This package use `pandoc` library(not atom package) and `language-reStructuredText` package. So, install each.

### pandoc

install and set PATH. **This is not atom package.**

http://johnmacfarlane.net/pandoc/installing.html

### language-reStructuredText

`language-reStructuredText` is atom package. Please install and update before use this. **v0.4.0 or later is required.**

https://atom.io/packages/language-restructuredtext

## Usage

Keybind is `ctrl-shift-e`.

Or, Packages -> reStructuredText Preview Pandoc -> Toggle Preview

## Test

Use pandoc library's test files(`.rst`, `.jpg`).

https://github.com/jgm/pandoc/tree/master/tests

`rst-reader.rst` may be good.

https://github.com/jgm/pandoc/blob/master/tests/rst-reader.rst
