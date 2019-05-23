

Tufte Bootstrap
===============================================================================
[Edward Tufte](https://en.wikipedia.org/wiki/Edward_Tufte) uses distinctive, simple, well-set typography; extensive sidenotes; and tight integration of graphics and charts. `tufte-bootstrap` brings that style to the [Bootstrap](https://getbootstrap.com) framework. 

This project is directly inspired [Tufte CSS](https://github.com/edwardtufte/tufte-css), which is based on [Tufte-LaTeX](https://tufte-latex.github.io/tufte-latex/) and the [R Markdown Tufte Handout](http://rmarkdown.rstudio.com/examples/tufte-handout.pdf).

![screenshot](https://raw.githubusercontent.com/dylan-k/tufte-bootstrap/gh-pages/assets/img/screenshot.png)


Getting Started
-------------------------------------------------------------------------------
The file *index.html* is a very simple example of what Tufte Bootstrap can do. You'll learn the most if you [browse the example web page demo](https://dylan-k.github.io/tufte-bootstrap). You might also want to [read the HTML](https://github.com/dylan-k/tufte-bootstrap/blob/gh-pages/index.html) markup.


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


Contributors
-------------------------------------------------------------------------------

 - Dylan Kinnett (project maintainer)
 - You?


License
-------------------------------------------------------------------------------

Released under the MIT license. See [LICENSE](https://github.com/edwardtufte/tufte-css/blob/gh-pages/LICENSE).
