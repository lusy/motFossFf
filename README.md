# motFossFf

This repository contains a talk on the motivation in the FOSS and [Freifunk](https://freifunk.net/) (a community network project in Germany) communities given in February 2016.
The talk is in German language.

## paper

You can also view the corresponding [paper](https://github.com/lusy/hausarbeiten/tree/master/motivFossCn) on github.

## attribution

I'd like to thank thousand times to all freifunk activists who've sacrificed their time to talk to me about the project and their motivations to participate.

## to view the presentation

* checkout this repo
* checkout [revealjs](https://github.com/hakimel/reveal.js) in the same directory under the name `reveal.js`
* open the `slides.html` file in your browser

## to build the slides

* checkout this repo
* checkout [revealjs](https://github.com/hakimel/reveal.js) in the same directory under the name `reveal.js`
* edit the source of the slides: the `slides.md` file

* install [pandoc](https://github.com/jgm/pandoc/releases/)

### html slides

use `pandoc -s --mathjax -i -t revealjs slides.md -o slides.html` to convert the slides to a html presentation

### latex slides

use `pandoc -t beamer slides.md -o slides.pdf` to convert the slides to a latex beamer presentation


## license

This talk is licensed under the Creative Commons Attribution-ShareAlike 4.0 (CC BY-SA 4.0) License. For more detailed information, visit [https://creativecommons.org/licenses/by-sa/4.0/](https://creativecommons.org/licenses/by-sa/4.0/)
