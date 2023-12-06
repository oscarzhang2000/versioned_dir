---
title: "Introducing Version Control with Git"
output: html_document
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```

## Writing markdown (Bonus Chapter)

You may have noticed that we used `.md` as the file extension for all of our text files.
This is because we were writing files using a simple markup language called 
[markdown](https://www.markdownguide.org).

Markdown is a very simple format that is used by tools such as GitHub to render 
nice web pages. Notice how the `## Hello World` from `README.md` is rendered
as a nice bold header on the GitHub web page.

Markdown is a very simple text language that is a bit like a wiki language, and allows plain text to be easily converted to a richly formatted webpage.

Believe it or not, this entire course and website are written in markdown! And all hosted on GitHub! To see, you can see the raw text for this page [here](https://raw.githubusercontent.com/chryswoods/siremol.org/master/chryswoods.com/introducing_git/markdown.Rmd) (in this case, this workshop is written using a flavour
of markdown called "R Markdown", which is used to write documentation and books for the R programming language).

The combination of GitHub and Markdown allows you to easily build wiki-like websites and documentation, and it is now becoming common best practice for software projects on GitHub to have associated documentation and `README.md` files written in Markdown.

## Exercise

Create a new file called `markdown.md` and experiment with writing some markdown. When you have written something, add it to the repository, commit the change, and then push it to GitHub, e.g.
