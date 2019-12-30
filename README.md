My CV, composed in LaTeX.

Recommended installation:

```
$ sudo apt install texlive-full
```

Recommended compilation:

```
$ pdflatex -output-directory=build cv.tex
$ biber --output-directory build cv
$ pdflatex -output-directory=build cv.tex
```
