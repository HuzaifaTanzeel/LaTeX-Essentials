


# LaTeX Workshop on Overleaf

Welcome to the LaTeX Workshop on Overleaf! This README serves as a guide to the workshop, covering key topics and providing LaTeX code examples. If you're new to LaTeX or want to learn more, you're in the right place.

![MLSA](https://github.com/HuzaifaTanzeel/LaTeX-Essentials/blob/main/download.jpg)

## Table of Contents
- [Introduction](#introduction)
- [Getting Started](#getting-started)
- [Basic Document Structure](#basic-document-structure)
- [Table of Contents](#table-of-contents-format)
- [Formatting Text](#formatting-text)
- [Mathematics](#mathematics)
- [Lists](#lists)
- [Tables](#tables)
- [Figures and Images](#figures-and-images)
- [Adding a URL](#adding-a-url)
- [References and Citations](#references-and-citations)
- [Additional Resources](#additional-resources)

## Introduction
LaTeX is a powerful typesetting system commonly used for creating documents with complex formatting. In this workshop, you will learn the basics of LaTeX, and we'll provide hands-on examples you can try on Overleaf.

## Getting Started
Before we dive into LaTeX, make sure you have an Overleaf account and access to a web browser. Overleaf is a user-friendly online LaTeX editor that allows collaborative editing.

## Basic Document Structure
In LaTeX, a document consists of a preamble and the document body. We will cover the basic structure of a LaTeX document.

```latex
\documentclass[12pt,a4paper]{article}

\begin{document}

\end{document}
```


### LaTeX Tags
- Document Class: `\documentclass{class}`

## Table of Contents Format

```latex
\tableofcontents
```


## Formatting Text
LaTeX provides various commands for text formatting, such as font styles, sizes, and text alignment.

```latex
\section{}
\subsection{}
```

### LaTeX Tags
- Font Styles: `\textbf{}` (bold), `\textit{}` (italic)
- Font Sizes: `\tiny`, `\small`, `\large`
- Text Alignment: `\centering`, `\raggedleft`

## Mathematics
LaTeX is widely used in scientific and mathematical documents. You will learn how to write mathematical expressions and equations.

### LaTeX Tags
- Inline Math: `$...$`
- Display Math: `\[...\]`
- Mathematical Symbols: `\frac{}`, `\sum`, `\sqrt{}`, `\int`

## Lists
Lists are a common part of documents. LaTeX allows you to create both ordered and unordered lists.

```latex
\begin{itemize}
\item \textbf{Digital Stethoscope}
\end{itemize}
```

### LaTeX Tags
- Unordered List: `\begin{itemize} \item ... \end{itemize}`
- Ordered List: `\begin{enumerate} \item ... \end{enumerate}`

## Tables
Tables are essential for presenting data in a structured way. You will learn how to create tables in LaTeX.

```latex
\begin{tabular}{|c|l|r|}
\hline
Column 1 (centered) & Column 2 (left-aligned) & Column 3 (right-aligned) \\
\hline
Item 1 & Description of Item 1 & $19.99$ \\
Item 2 & Description of Item 2 & $29.95$ \\
Item 3 & Description of Item 3 & $14.50$ \\
\hline
\end{tabular}
```

### LaTeX Tags
- Table Environment: `\begin{tabular} ... \end{tabular}`
- Column Alignment: `c`, `l`, `r`
- Adding Borders: `\hline`

## Figures and Images
LaTeX makes it easy to insert figures and images into your documents.

```latex
\begin{figure}[H]
\centering
\includegraphics[width=1\textwidth,height=6cm]{pic.PNG}
\caption{A sample image with a caption.}
\end{figure}
```

### LaTeX Tags
- Inserting a Figure: `\begin{figure} \includegraphics{image-file} \end{figure}`
- Figure Captions: `\caption{Your caption}`


## Adding a URL

```latex
\url{https://imaginecup.microsoft.com/en-us}
```

## References and Citations
Learn how to create and manage references and citations using BibTeX.

```latex
\cite{Xbook}
```

### LaTeX Tags
- Citation: `\cite{key}`
- BibTeX File: `\bibliography{myreferences}`
- Citation Style: `\bibliographystyle{plain}`

## Additional Resources
- [Overleaf](https://www.overleaf.com/): An online LaTeX editor with collaborative features.

This README provides a brief overview of the topics covered in this LaTeX workshop. Feel free to explore each section for more details and examples. Happy LaTeXing!

### .BIB FILE
```bibtex
@article{Xarticle,
    author    = "Smith, John",
    title     = "The Impact of LaTeX on Document Typesetting",
    journal   = "Journal of LaTeXology",
    volume    = "42",
    number    = "3",
    pages     = "123-135",
    year      = "2022",
    month     = "June",
    note      = "This is a sample note for the article.",
}

@book{Xbook,
    author    = "Doe, Jane",
    title     = "LaTeX for Beginners",
    publisher = "Academic Press",
    volume    = "2",
    number    = "5",
    series    = "LaTeX Series",
    address   = "New York",
    edition   = "2nd",
    year      = "2021",
    month     = "December",
    note      = "This is a sample note for the book.",
}
```

### Thank You for Attending
