## Beamer LaTeX template

This respository contains a Beamer LaTeX template designed for presentations by members of both the University and University Hospital at Poitiers.

## Complete the title page

At the top of the [`template.tex`](template.tex) file, edit the information about your presentation. Update the author, title, date, and author fields. 

```latex
%%% Modify the presentation's bibliographic details
\title{Presentation Title}
\date{DD MM YYYY}
\author{Firstname Lastname}
```
## Add sections

To add the section to the outline, add `\section{Your Section Name}` to the `template.tex` file.  You can also add subsections: `\section{Your Subsection Name}`.

```latex
\section{Methods}
\subsection{Studied population}
```

## Compil LaTex

An easy way to edit and compile LaTeX in a code editor is to use 'TexMaker' which is available on Linux, MacOs, and Windows.
