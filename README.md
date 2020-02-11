# FIIT-BP-template

Un-official template for Bachelor's thesis.

If you have any suggestions, please submit an issue or pull request!

You may [check out the preview](preview.pdf) to see whether you like it.

## Usage

Just clone, and explore and use.

### Language setting

__To change the language from Slovak to English, please edit values.tex like so:__

From:
```
\newcommand{\FIITlanguage}[0] {slovak}
%\def\FIITlagEN{}
```

To:
```
\newcommand{\FIITlanguage}[0] {english}
\def\FIITlagEN{}
```

This will then use variables without the SK suffix.


### Folder/File structure

- __assets__ - contains any assets used in the project
- __content__ - this folder contains the actual content of the document
- __pages__ - this folder contains main pages (title, cover, annotation, etc.)
- __templates__ - this folder contains templates for parts of the document (components of pages, etc.)
- `bibliography.bib` - contains sample bibliography
- `initialize.tex` - contains initializations that happen after the document begins
- `main.tex` - is the main document file - containing the actual structure of the document
- `packages.tex` - contains includes for packages, and some custom commands
- `values.tex` - contains global variables (author, title, etc., font size, ...) and language selection
