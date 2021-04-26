# examNord
This is a package with Rmarkdown template for producing Exam tasks.
The usage of template ensures a compliance with requirements as they are in Spring 2018.

To use package, it should be installed.

## Installation
Before usage of this template, you should install this package: 

`devtools::install_github("ev-ant/examNord")`

## To use

After the installation, this package needs to be loaded:

`library("examNord", lib.loc="<local_library_location>")`

When creating a new Rmarkdown, choose an option *"From Template"* and select the one with name *"Exam tasks at Nord University"*.

If package `"examNord"` is loaded, but there is no mentioned template in the list, restart R session.

# More on usage

Currently, the template loads a minimum of packages to ensure work mostly with text. If some extra \LaTeX packages are needed, add them into a `custom.tex` file. The next packages will be loaded anyway:

* `\usepackage{lmodern}`

* `\usepackage{amssymb,amsmath}`

* `\usepackage{ifxetex,ifluatex}` 

* `\usepackage{fixltx2e}` % provides \textsubscript

* `\usepackage{geometry}`

* `\usepackage{hyperref}`

* `\urlstyle{same}`  % don't use monospace font for urls

* `\usepackage{graphicx,grffile}`

* `\usepackage{titling}`
* `\usepackage{xunicode}`
* `\usepackage{xltxtra}`
* `\usepackage{fancyhdr}`
* `\usepackage{titlesec}`

Since the template relies on extra files with specification of style, an update unsures that **only new `.Rmd`** will get updated template.
An easy solution to use template with updated styling, is to copy `examNord.sty` and `frontpage.tex` to your older folders. 

To ensure a proper total number of pages in header, keep command `\noAttachment` at the very end of the document.
