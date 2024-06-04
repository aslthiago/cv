cv
==

clean
-----
latexmk -cd -C src/cv.tex

compile
-------
latexmk -cd -pdf src/cv.tex

watch
-----
latexmk -quiet -cd -pvc -pdf src/cv.tex
