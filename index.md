# Connor McClellan Astronomy
\
<img style="float:left; margin-right:30px" src="img/mcclellan_headshot.png" width=500px>


## About Me

*My pronouns are he/him.*

I am a 6th-year PhD candidate studying at the University of Virginia.

In my academic research, I use numerical radiation hydrodynamics simulations to explore astrophysical problems ranging from exoplanet atmospheres to thermonuclear explosions on the surfaces of neutron stars.


### About This Webpage

This site is compiled from a collection of Markdown files which are rendered to HTML using [Pandoc](https://pandoc.org/). The formatting is handled with [this CSS file](./stylesheets/tufte.css) and [this HTML5 template](./stylesheets/tufte.html5), which are based on the [Tufte CSS](https://edwardtufte.github.io/tufte-css/) stylesheet. The Pandoc command used to compile each HTML file is

```bash
pandoc --katex --from markdown+tex_math_single_backslash --filter pandoc-sidenote \
--to html5+smart --template='./stylesheets/tufte.html5' --css './stylesheets/tufte.css' \
-o [FILENAME].html 'Connor McClellan Astronomy.md' [FILENAME].md
```

The file `'Connor McClellan Astronomy.md'` contains the site index, which is prepended to each HTML file and inserts links to other pages in the margins.
