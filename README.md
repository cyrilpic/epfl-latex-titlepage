# epfl-latex-titlepage

Simple title pages for latex documents with "EPFL style"

## Usage

Start by copying the package file `epfl_titlepage.sty` in your LaTeX project folder and make sure the EPFL logo (named `epfl`) is available in your graphic search path.

```latex
% in the preamble
\usepackage[style]{epfl_titlepage}

% where style can be master or candidacy

% ...

\title{My awesome project}
\author{My Name}

\project{Master thesis}

\professor{Prof. Tournesol}
\supervisor{Tintin and Milou}

% And then in the document
\maketitle
```
