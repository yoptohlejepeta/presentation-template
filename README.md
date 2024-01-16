# wildcat
A beamer theme for Northwestern University.

## Overview
This beamer theme uses branding guidelines (colors, fonts, and logos) from [Northwestern University](https://www.northwestern.edu/brand/visual-identity/). The design mimics Northwestern's facets Zoom backgrounds, and the style files build on the amazing Stack Exchange answer by [Claudio Fiandrino](https://tex.stackexchange.com/questions/146529/design-a-custom-beamer-theme-from-scratch). This is not an official, Northwestern-approved beamer template: This is simply my own attempt to make a simple, modern beamer theme. 

## How do I use this?
You will simply need to have all the .sty files in the source folder in your LaTeX file's working directory. Then add `\usetheme{wildcat}` to your preamble. See source/wildcat-example.tex for an example document. 

## Fonts
For the font theme to work, you will need to have the Campton and Akkurat Pro fonts installed on your system. I am going to work on an "Overleaf Friendly" font theme in the future, but for now it may break if you don't have those fonts installed. You will also need to use XeLaTeX to compile, similar to the Metropolis theme (using Fira Sans fonts).

## Stability
I highly doubt this is stable. This is still a work in progress. So, if you come across any errors, please send me a message via GitHub!

## Coming Soon
Here are my plans for what I want to add:
- More interesting block environments (adding facet design and a border to the block title and body)
- More color themes (light version, plus other pallettes entirely)
- Ability to easily change (or remove) the logo from preamble
