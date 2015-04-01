# reStructuredText Preview package

Show the pandoc-rendered HTML markdown to the right of the current editor using
`ctrl-shift-m`

Live Update scrolls to cursor position when editing. You can also toggle scrolling preview together with editor (like StackEdit for example).

It can be activated from the editor using the `ctrl-shift-e` key-binding and is
currently enabled for `.markdown`, `.md`, `.mdown`, `.mkd`, `.mkdown`, `.ron`, `.txt` and `.rst` files.

For a better way to preview math than default `--webtex`, you can try a pandoc filter like this one: <https://gist.github.com/lierdakil/6a95278d02256a74a0fc>

## Usage

This package use `pandoc` library(not atom package) and `language-reStructuredText` package. So, install each.

### pandoc

install and set PATH.

http://johnmacfarlane.net/pandoc/installing.html

### language-reStructuredText

`language-reStructuredText` is atom package. Please install before use this.

https://atom.io/packages/language-restructuredtext

## Test

Use pandoc library's test files(`.rst`, `.jpg`).

https://github.com/jgm/pandoc/tree/master/tests

`rst-reader.rst` may be good.

https://github.com/jgm/pandoc/blob/master/tests/rst-reader.rst
