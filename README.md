# uic_fyp_thesis_template
UIC FYP Thesis Template (Remaster from CST FYP template (word version))



## LaTeX Template

Author: [@ECWU](https://github.com/ecwu)

A LaTeX template based on the FYP template (word version) provided by the BNU-HKBU UIC CST programme.

### Files structure

1. [DIR] `assets`: a place for all asset materials like figures, codes, PDFs, etc. Files are not limited to stored there, just a pre-created folder to help you keep everything nice and clean.

2. [DIR] `frontpage`: Only one file `declaration.tex` is inside the folder, it defined the declaration for the "original statement" from the author(s).

    > The name of the "original statement" is defined by myself, it is not the official name for the page.

3. [FILE] `confidential.tex`: For every "non-final version" thesis, a watermark with text "**Confidential Review Copy. DO NOT DISTRIBUTE.**" will show on every page of the document. This file defined the style and content to implement this watermark. More about non-final/final version, please check `3.1`

4. [FILE] `fypref.bib`: BibTeX-File which stored all your cited materials. For more about BibTeX file Format please check [BibTeX Format Description](http://www.bibtex.org/Format/) from bibtex.org.

    > The default bibliography style is `IEEE Transactions (ieeetr)`

    > BibTeX: This software together with LaTeX can help you easily cite and create a bibliography list.

5. [FILE] `thesis.preamble.tex`: All Included Packages, settings. Create this separate file for project tidiness. Sure you will need to add extra packages sometime in the future, please remember the order of the package in this file matters.

6. [FILE] `thesis.sty`: Style file (kind of like a CSS file in a website), handling font size, linespace, logo, and elements location. The modified title page is also defined there. With hardcoded course name, course code, and programme name. You can change those here if you want.

7. [FILE] **`thesis.tex`**: The most important file, I am sure you will write lots of your hard work here. I try to keep everything understandable with a comment. One thing I want to point out. For `\thesisfinalcopy` on line 20, it is for setting the file status to the non-final/final version. "non-final version" result in the watermark on every page.

Feel free to create an issue if you have any problems.