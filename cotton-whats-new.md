---
---


# WHAT'S NEW IN VERSION 11

[Cotton Markdown Tables](https://m.pffy.dev/cotton) is constantly improving. Here are some of the recently added features:

  + Added a YouTube thumbnail generator

### HOW IT WORKS

In cell A1, enter the canonical YouTube watch URL, surrounded by double brackets:
```
<<https://www.youtube.com/watch?v=w3jLJU7DT5E>>
```

Now, insert a new note to cell A1:

```
what is github?
```

This note annotates the YouTube video thumbnail. 

Next, run any Cotton Markdown tables conversion. The YouTube generator syntax converts to the following Markdown syntax:

```
[![what is github?](https://img.youtube.com/vi/w3jLJU7DT5E/mqdefault.jpg "what is github?")](https://www.youtube.com/watch?=w3jLJU7DT5E)
```

Here is what it looks like:

[![what is github?](https://img.youtube.com/vi/w3jLJU7DT5E/mqdefault.jpg "what is github?")](https://www.youtube.com/watch?=w3jLJU7DT5E)

Video information is also added to footnotes below the Markdown table.

- - - -

### RECENTLY ADDED

  + Added support for `=HYPERLINK` formula
  + Added support for spreadsheet hypertext formatting
  + Added support for underline font style
  + Improved empty cell handling for large tables
  + Added support for exporting notes as footnotes
  + Improved GitHub rendering of special characters
  * Added support for line breaks (multi-line text)
  * Added support for converting checkboxes to text checkboxes
  * Updated list of supported monospace Google fonts
  * Added [compatibility chart](https://github.com/pffy/markdown-table#compatibility) for Markdown editors.
  * Released open source copy of this add-on
  * UI fixes

### ADDED IN PREVIOUS VERSIONS

  * Added support for bold, italic, and strike-through font styles
  * Added support for converting monospace (fixed-width) fonts to code syntax
  * Added support for skipping hidden rows and columns
  * Added support for multi-select ranges
  * Added exporter for multiple named ranges to a single document
  * Added exporter for multiple sheets to a Markdown table group file

### CORE FUNCTIONALITY
  + Export selected range
  * Copy to clipboard
  * Save Markdown document to Google Drive™
  * Download Markdown document to desktop



{% include footer.md %}
