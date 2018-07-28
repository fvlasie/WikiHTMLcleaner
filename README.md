# WikiHTMLcleaner
A Perl script for cleaning the Wikipedia specific detritus from the HTML code of article pages.

Test with:

`curl "https://en.wikipedia.org/w/index.php?title=Hello&action=render" | perl WikiHTMLcleaner.txt | pbcopy`

Paste into Safari's Develop>Snippet Editor to see the results.

This is desinged to work with the output of Wkipedia's &action=render URL option which returns only the HTML of the article requested by the title= argument.
