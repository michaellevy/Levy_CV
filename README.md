# Levy_CV

To compile:

Update content.md
```
pandoc content.md -o content.tex  
latexmk -cd -e -f -lualatex -interaction=nonstopmode -synctex=1 Levy_CV.tex
```


Original idea from [Craig Eley](http://craigeley.com/09-05-2013/formatting-your-cv-with-markdown-and-latex/) with additional improvements by [Talha Oz](https://github.com/oztalha/resume).
