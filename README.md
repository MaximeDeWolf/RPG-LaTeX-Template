# D&D 5e LaTeX Template

This is an attempt at a D&D 5e LaTeX template. The color scheme is close to the original source books, as are the fonts. The fonts chosen are included by default in TeX Live.

The template compiles with pdflatex.

![Preview](https://github.com/anoderay/DND-5e-LaTeX-Template/raw/master/scrot.png)


### Installation

Just clone the repo. From terminal:

```sh
$ git clone https://github.com/anoderay/DND-5e-LaTeX-Template.git 5e-template
$ cd 5e-template
$ pdflatex example.tex
```

### Package Options
- bg-letter: Loads a letter-sized background-image
- bg-a4: Loads an A4-sized background-image
- bg-print: Loads a printer-friendly background-image (only decal at the bottom)
- bg-full: Loads the full background-image 

Per default "bg-letter" and "bg-full" are loaded.

### Todo's

 - Consider implementing more complex tables for monsters, etc.
 - Clean up the table-preset
 - Add indentation within the boxes
 - Remove indentation after the boxes + fix space before and after the boxes
 - Reduce space after subsubsection

### Image Credit

 - Credit for the background Image goes to http://lostandtaken.com/
 
### Version
0.2
