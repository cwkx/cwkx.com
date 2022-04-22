# cwkx.com sources

This website is based on [suckless.org](https://suckless.org/) and follows the [suckless philosophy](https://suckless.org/philosophy/). It is simple HTML and CSS. I didn't want to use markdown or any horrible third party system such as jekyll, hugo, or wordpress.

The only time saving script is [genbib.py](/data/genbib.py) which converts the BibTeX [cgw.bib](/data/cgw.bib) into html, then injects it into `publications.html` and `index.html` accordingly. This is kept tidy using [BibTeX tidy](https://flamingtempura.github.io/bibtex-tidy/) with sort fields `-year -month -day`.
