A LaTeX template for making a PDF footer that can be overlayed on
other PDFs.

Prerequisites
-------------

* LaTeX
* pdftk

Instructions
------------

1. Edit footer.tex

2. Run `pdflatex footer`

3. Run `pdftk input.pdf stamp footer.pdf output output.pdf`