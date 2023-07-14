# Ebook-MSTSORTSExporter
MSTS and Open Rails Exporter Add-On for Blender 2.8+


AsciiDoctor Source code, license CC-BY-SA-4.0 

This is the first draft of version 4.4 migrated to using ASCIIDOCTOR-PDF.


# To BUILD this document from AsciiDoctor source you need:

## Install Ruby

Have the RUBY programming language installed.   https://rubyinstaller.org/

## Install AsciiDoctor - pre-release

Install AsciiDoctor-PDF with the following command: `gem install asciidoctor-pdf --pre`

## Install Rouge syntax highlighter

Install Rouge with the following command: `gem install rouge`

## Assembling the document

I use the following command to create the PDF document output:


asciidoctor-pdf -r asciidoctor-diagram -a pdf-themesdir=themes -a pdf-theme=test -a pdf-fontsdir=fonts book.adoc -o MSTSORTSExporter.pdf

NOTE: ASCIIDOCTOR formatting code is ALMOST github compatible...  so GITHUB tries to render it... (It just doesn't really work)


You can use the script `makeit.bat` to convert the document to PDF


