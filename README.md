# UTPFRBeamerclass Format

## Installing

Adding to existing project:

```bash
quarto add rogerioag/utfprbeamerclass
```

Creating a new project with template:

```bash
$ quarto use template rogerioag/utfprbeamerclass

Quarto templates may execute code when documents are rendered. If you do not 
trust the authors of the template, we recommend that you do not install or 
use the template.
 ? Do you trust the authors of this template (Y/n) › Yes
 ? Directory name: › class-001-intro
[✓] Downloading
[✓] Unzipping
    Found 1 extension.
[✓] Copying files...

Files created:
 - _extensions
 - class-001-intro.qmd
 - ref.bib
$ 

```

This will install the extension and create an example qmd file that you can use as a starting place for your article.

## Using

```bash
$ cd class-001-intro
$ quarto render class-001-intro.qmd --to utfprbeamerclass-beamer
```



## Format Options

*TODO*: If your format has options that can be set via document metadata, describe them.

## Example

Here is the source code for a minimal sample document: [template.qmd](template.qmd).

