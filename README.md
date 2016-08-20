# tex-doc

[![Travis&#x2011;CI Build Status](http://img.shields.io/travis/yitzchak/tex-doc/master.svg?label=Linux/OSX%20build)](http://travis-ci.org/yitzchak/tex-doc) [![AppVeyor Build Status](http://img.shields.io/appveyor/ci/yitzchak/tex-doc/master.svg?label=Windows%20build)](http://ci.appveyor.com/project/yitzchak/tex-doc) [![David](http://img.shields.io/david/yitzchak/tex-doc.svg)](http://david-dm.org/yitzchak/tex-doc)

Access TeX documentation from inside [Atom](http://atom.io).

## Installing

Use the Atom package manager and search for "tex-doc", or from a shell run

```bash
apm install tex-doc
```

## Prerequisites

This package relies on a TeX installation. Currently [TeX Live](https://www.tug.org/texlive/) and [MikTeX](http://miktex.org/) are supported.

## Usage

Either select or move the cursor to a keyword in a TeX or LaTeX document and press <kbd>Ctrl</kbd>-<kbd>Alt</kbd>-<kbd>H</kbd> open the most relevant document or press <kbd>Ctrl</kbd>-<kbd>Alt</kbd>-<kbd>L</kbd> to open list of relevant documents.

Text based documents can be opened in Atom by selecting the `Show Result in Atom` option in the settings page. If the
[pdf-view](https://atom.io/packages/pdf-view) is installed then pdf documents will also be opened in Atom when `Show Result in Atom` is enabled. All other other documents will be opened using either texdoc or mthelp, depending on which one is selected in your settings.

## Status

Please note that this package is in a **beta** state.
