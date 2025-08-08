
### Preview

[Download/View my resume (PDF)](maanas-resume.pdf)

### NOTE:

This repository is a fork of [Sourabh Bajaj's Software Engineer Resume](https://github.com/sb2nov/resume), adapted for my personal use.  
The template is based on LaTeX and is designed for a single-page, one-column resume for software developers.

### Quick start

Get started quickly using [Overleaf](https://www.overleaf.com/latex/templates/software-engineer-resume/gqxmqsvsbdjf) template.

### Build using Docker

```sh
docker build -t latex .
docker run --rm -i -v "$PWD":/data latex pdflatex maanas-resume.tex
```