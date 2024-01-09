
<!-- README.md is generated from README.qmd. Please edit that file -->

# RAC Foundation Technical Report Format Template

This is a Quarto template that assists you in creating an RAC Foundation
technical report.

## Creating a new report

You can use this as a template to create a report. To do this, use the
following command in the terminal window of RStudio (in the
project/folder of your choice):

``` bash
quarto use template RACFoundation/RACF-technical-report
```

This will install the extension and create an example qmd file that you
can use as a starting place for your report.

## Installation for existing document

You may also use this format with an existing Quarto project or
document. From the quarto project or document directory, run the
following command to install this format:

``` bash
quarto install extension RACFoundation/RACF-technical-report
```

## Example

<div>

[![](examples/template.png)](examples/template.pdf)

</div>

## Errors

If you get an error where you get something like “!pdfTeX error:
pdflatex.exe (file bchb8a.pfb): cannot open Type 1 font file for reading
==\> Fatal error occurred, no output PDF file produced!”, this is caused
by an installation issue with TinyTex, resulting in a required font not
appearing where it should be.
