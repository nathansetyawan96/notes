# Pandoc  

## Description

 Pandoc is a Universal Document Converter.

... for text markup `*italic*` -> `<i>italic</i>`

... for standalone files.

Pandoc can convert documents to/from:

  *  HTML formats: XHTML, HTML5, and HTML slide shows using Slidy, reveal.js, Slideous, S5, or DZSlides.
  *  Word processor formats: Microsoft Word docx, OpenOffice/LibreOffice ODT, OpenDocument XML
  *  Ebooks: EPUB version 2 or 3, FictionBook2
  *  TeX formats: LaTeX, ConTeXt, LaTeX Beamer slides
  *  PDF via LaTeX
  *  Lightweight markup formats: Markdown (including CommonMark), reStructuredText, AsciiDoc, MediaWiki markup, DokuWiki markup, Emacs Org-Mode, Textile
    Custom formats: custom writers can be written in lua.
    * And [more][1].

## Installation

> sudo apt install pandoc

## Usage

> pandoc [input file] [options] [output file]

* [input file] - .md, .txt. .docx, .latex, .wiki, .org, .html, .odt. For multiple files *.extention.
* [options] - -s, -o, --smart, --normalize.
  + --smart (Produce typographically correct output).
  + --normalize (Remove repeated spaces, other cleanup).
  + --toc (Generate table of contents to output document).
  + -s (Produce standalone document. Without this pandoc will output to terminal)
  + -o (Output to a file.)
* [output file] - Name of output file. Will convert to extension.
* If input files are not in the same folder, you need to include file paths, too.

## Pandoc Markdown
To get a description of pandoc’s markdown syntax:
> man pandoc_markdown

---
[1]: http://pandoc.org/
