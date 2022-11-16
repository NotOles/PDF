# PDF

## Why Are These Well Known PDF Files Here?

These well known pdf files are widely available on the internet. Remarkably, however, Github's web user interface (UI) seems to allow Chrome browser's [High Contrast](https://chrome.google.com/webstore/detail/high-contrast/djcfdncoelnlbldjfhinnjlhdjlikmph?hl=en) accessibility extension to invert the display color of pdf files. Viewing pdf files rendered with white text on a black background allows visually challenged people like me to read the files.

## How Does Github's UI Allow Chrome's High Contrast Extension To Work With PDFs?

Although Chrome's High Contrast accessibility extension works great for me on other types of files, High Contrast doesn't seem to work on pdfs read with Chrome. High Contrast seems to fail with pdfs read with Chrome regardless of whether the pdf files are downloaded from the web or read locally. Why, then, does High Contrast work when the pdf file is displayed via Github?

A quick look at the source code of a pdf page accessed on Github seems to show that the pdf is displayed inside an [Inline Frame Element (iframe).](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/iframe) I haven't figured out the magic that occurs within the iframe that allows Chrome's High Contrast extension to work with pdfs. If you know the secret, I'd be grateful for a hint! 

## Alternatives To Github + High Contrast

The [Chrome DarkPDF extension](https://chrome.google.com/webstore/detail/darkpdf/cfemcmeknmapecneeeaajnbhhgfgkfhp?hl=en) from [ArshSB](https://github.com/ArshSB/DarkPDF) is yet another gift to visually challenged people. DarkPDF seems to work on my Chromebook for both web pdfs and pdfs accessed locally. However, DarkPDF seems to render pdfs as light gray text on a darker gray background. In other words, DarkPDF is great, but some visually challenged people need even more contrast than DarkPDF seems to offer.

[Here](https://ourtechroom.com/tech/preview-pdfs-chrome-dark-mode/) is a discussion of additional methods to view pdf files in dark mode with Chrome.

## A Possible Disadvantage Of PDF Display Via Github

A possible disadvantage of the Github pdf UI might be that one may have to keep clicking "More Pages" every 5 pages or so. Maybe there is a way that I haven't yet discovered to open an entire pdf file completely. If you know how to open an entire pdf file inside Github's iframe, please tell me.

## Thanks To Github And Google!

Thanks to Github for making it possible for me to read pdf files with Chrome's High Contrast accessibility extension! Thanks to Google for the High Contrast accessibility extension itself!

## C and Xv6

If you are interested in learning more C in the context of the Xv6 operating system, you might want to visit the [Xv6 Study Group.](https://metalvps.com/Xv6) 
