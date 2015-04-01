# reStructuredText Preview package

Show the pandoc-rendered HTML markdown to the right of the current editor using
`ctrl-shift-m`

Live Update scrolls to cursor position when editing. You can also toggle scrolling preview together with editor (like StackEdit for example).

It can be activated from the editor using the `ctrl-shift-m` key-binding and is
currently enabled for `.markdown`, `.md`, `.mdown`, `.mkd`, `.mkdown`, `.ron`, `.txt` and `.rst` files.

For a better way to preview math than default `--webtex`, you can try a pandoc filter like this one: <https://gist.github.com/lierdakil/6a95278d02256a74a0fc>

This package use `pandoc` library and `language-reStructuredText` package.

## pandoc

install and set PATH.

http://johnmacfarlane.net/pandoc/installing.html

## language-reStructuredText

`language-reStructuredText` is atom package. Please install before use this.

https://atom.io/packages/language-restructuredtext
