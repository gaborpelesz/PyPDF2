# History of PyPDF2

## The Origins: pyPDF

In 2005, [Mathieu Fenniak] launched pyPdf "as a PDF toolkit..."
focused on

-   document manipulation: by-page splitting, concatenation, and
    merging;
-   document introspection;
-   page cropping; and
-   document encryption and decryption.

## PyPDF2 is born

At the end of 2011, after consultation with Mathieu and others, Phaseit
sponsored PyPDF2 as a fork of pyPdf on GitHub. The initial impetus was
to handle a wider range of input PDF instances; Phaseit\'s commercial
work often encounters PDF instances \"in the wild\" that it needs to
manage (mostly concatenate and paginate), but that deviate so much from
PDF standards that pyPdf can\'t read them. PyPDF2 reads a considerably
wider range of real-world PDF instances.

Neither pyPdf nor PyPDF2 aims to be universal, that is, to provide all
possible PDF-related functionality. Note that the similar-appearing
[pyfpdf] of Mariano Reingart is most comparable to [ReportLab], in that
both ReportLab and pyfpdf emphasize document generation. Interestingly
enough, pyfpdf builds in a basic HTML→PDF converter while PyPDF2 has no
knowledge of HTML.

So what is PyPDF2 truly about? Think about popular [pdftk] for a moment.
PyPDF2 does what pdftk does, and it does so within your current Python
process, and it handles a wider range of variant PDF formats
\[explain\]. PyPDF2 has its own FAQ to answer other questions that have
arisen.

## PyPDF2 rises

The Reddit [/r/python crowd chatted] obliquely and briefly about PyPDF2
in March 2012.

## PyPDF2: Reborn

Martin Thoma took over maintenance of PyPDF2 in April 2022.


  [Mathieu Fenniak]: https://mathieu.fenniak.net/
  [pyfpdf]: https://github.com/reingart/pyfpdf
  [ReportLab]: https://www.reportlab.com/software/opensource/rl-toolkit/
  [pdftk]: https://www.pdflabs.com/tools/pdftk-the-pdf-toolkit/https://www.pdflabs.com/tools/pdftk-the-pdf-toolkit/
  [/r/python crowd chatted]: https://www.reddit.com/r/Python/comments/qsvfm/pypdf2_updates_pypdf_pypdf2_is_an_opensource/