# md2html4cpp
## Introduction
Convert Markdown file to HTML.  
## Usage
`transform` is a class for converting.
* Constructor: `tranform conv("filename.md");`, in which `filename.md` is the filename of your Markdown file.
* Content: `conv.getContent` will return a string generated from `filename.md`;
* Table of Contents: `conv.getTableOfContents` will return a string represents the table of contents.
