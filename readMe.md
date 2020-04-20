# CV: Benjamin D. Peterson

This is my repo for my updated CV. The template was taken from Steven V. Miller (https://github.com/svmiller/svm-r-markdown-templates).
I just downloaded his svm-latex-cv.tex file, but didn't fork the entire branch.

## Set up Git

This project is going to be stored here: `/Users/benjaminpeterson/Documents/orderInTheKingdom/CV`.
First I needed to set up git on the folder:

```
cd /Users/benjaminpeterson/Documents/orderInTheKingdom/CV
git init
#atom .gitignore
git add .gitignore
git commit -m "Added gitignore file"
git remote add origin https://github.com/petersonben50/CV.git
git push origin master
```

## Set up instructions

Here's my set-up workflow for this, which is based on [this](http://svmiller.com/blog/2016/03/svm-r-markdown-cv/) and [this](https://medium.com/@sorenlind/create-pdf-reports-using-r-r-markdown-latex-and-knitr-on-macos-high-sierra-e7b5705c9fd).
First, I needed to download the LaTeX engines.
I used the [MacTeX site](http://www.tug.org/mactex/mactex-download.html) to do this.
It's a large file to download (3Gb), so it takes a while.

Now I can make my CV!
I'll make edits to the CSS engine as I go along.
I did delete the section that doesn't allow bullet points or lists.
