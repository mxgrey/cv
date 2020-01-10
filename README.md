My CV, composed in LaTeX.

You may reuse this template and project structure, on the condition
that you do not claim any of my personal information as your own.

Recommended installation:

```
$ cp -r home/* ~ 
$ sudo apt install texlive-full
```

Recommended compilation:

```
$ mkdir build
$ pdflatex -output-directory=build cv.tex
$ biber --output-directory build cv
$ pdflatex -output-directory=build cv.tex
```
