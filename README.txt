

Tufte Bootstrap
===============================================================================
[Edward Tufte](https://en.wikipedia.org/wiki/Edward_Tufte) uses a distinctive style in his handouts: simple, with well-set typography, extensive sidenotes, and tight integration of graphics and charts. `tufte-css` brings that style to HTML documents.

This project is an attempt to build web pages in that style, using [Bootstrap](https://getbootstrap.com). It is directly inspired [Tufte CSS](https://github.com/edwardtufte/tufte-css), which is based on [Tufte-LaTeX](https://tufte-latex.github.io/tufte-latex/) and the [R Markdown Tufte Handout](http://rmarkdown.rstudio.com/examples/tufte-handout.pdf).


Getting Started
-------------------------------------------------------------------------------
The file *index.html* is a very simple example of what Tufte Bootstrap can do. You'll learn the most by browsing the demo as well as by reading the html markup.


Project Scope and Status
-------------------------------------------------------------------------------
Tufte Bootstrap is a intended to become a Bootstrap theme. It is currently in a very early stage, as a simple css overwrite with bootstrap classes added directly into the html.

TO DO:

- [ ] Use mixins instead of html classes
- [ ] make provision for bootstrap's medium screensize and smaller
- [ ] apply link styles from Tufte CSS
- [ ] use boostrap's "collapse" component to make stretchtext
- [ ] add ability hide/show the marginnotes and sidebotes
- [ ] add a [sidebar](https://www.codeply.com/go/3e0RAjccRO/bootstrap-4-collapsing-sidebar-menu)?
- [ ] "night mode" inverted colors
- [ ] oldstyle figures where appropriate


Contributing
-------------------------------------------------------------------------------
If you notice something wrong or broken, let us know by opening an issue, or better yet, a pull request with how you think it should be fixed.

Please document your issues and fixes thoroughly. This means a clear description of the concern, steps on how to reproduce it, and (if possible) before and after screenshots and links to prior discussions or commits. Please keep pull requests to one change at a time.

Fixes and new functionality should be tested against `index.html` on screens as small as an iPhone 4 and as big as, well, as big as you use normally. (If you don't have a mobile device handy, fake different devices with your browser's developer tools.)

See the Issues page, especially Help Wanted, for opportunities to contribute. Keep our style guide in mind:


Contributors
-------------------------------------------------------------------------------

 - Dylan Kinnett (project maintainer)
 - You?


License
-------------------------------------------------------------------------------

Released under the MIT license. See [LICENSE](https://github.com/edwardtufte/tufte-css/blob/gh-pages/LICENSE).