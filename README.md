# Levy_CV

Creating PDF:

1. Update content.md
2. Shell: 
	`pandoc content.md -o content.tex`
3. Build Levy_CV.tex in Sublime or with 
	`latexmk -cd -e -f -lualatex -interaction=nonstopmode -synctex=1 Levy_CV.tex`

Original idea from [Craig Eley](http://craigeley.com/09-05-2013/formatting-your-cv-with-markdown-and-latex/) with additional improvements by [Talha Oz](https://github.com/oztalha/resume).
