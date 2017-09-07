# Plasma Paper

#Compiling/Editing

Paper is in LaTeX format. Diagrams are in dia, but may remake the diagrams in
inkscape for cleanliness.

## Updating bibliography
If you're not familiar with latex, updating bibliography requires running:
```
pdflatex new.tex
bibtex new
pdflatex new.tex
pdflatex new.tex
```

## Generating figures
requires dia

```
cd figures
python dia2pdf.py
```

## Formatting

80 character width by default.

There are a couple places where reflowing will break (primarily in figures where it's sensitive to linebreaks).
