Docblock
====================

A perl script to convert plain text to documentation formatted lines, with initial comment characters and hard-wrapped to 80 characters. Paragraph breaks are preserved.

By Joachim Noreiko.
Released under GPL yada yada.

Usage
-----

$ docblock < myfile.txt

Input file should be plain text, with double linebreaks to mark paragraphs and no linebreaks elsewhere.

Todo
----

- allow single linebreaks (and ignore them).
- allow the comment character string to be present at the start of lines (and ignore it), in effect, allow text that's already formatted as docblock as input and reflow it (for the case where you've added or removed words and broken the 80-char limit in places).
- you idea (and patch! ;) here.



