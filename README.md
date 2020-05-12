# Introducing WindNODE ABW at oemof user meeting, spring 2020

Using [RLI's beamer theme](https://github.com/rl-institut/beamer_theme)

## Building PDF slides

```
pandoc -t beamer --filter pandoc-citeproc --bibliography bib/slides.bib --pdf-engine=xelatex -o WindNODE_oemof_spring_meeting_2020_slides.pdf slides.md
```

Note: If you use **pandoc version <2.0**, replace `--pdf-engine` by `--latex-engine=` to process the Markdown file.

## Packages you might need

```
sudo apt get install texlive
sudo apt get install texlive-fonts-extra
sudo apt get install pandoc
sudo apt get install xetex
```
