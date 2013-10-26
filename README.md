### SCP Book

Seeing how the old PDF project seems to be available but more or less dead and also formatted as simple ODT files, I set out to create a more flexible version of the database.

The original idea was to capture it in a form compatible with eBook readers like the Amazon Kindle, seeing how that turned out to be more of a hassle starting out, I chose to start off with a PDF version typeset in LaTeX. Formatting was to be the same of the old PDF project, same font, same background and so forth. This proved to be more than tiresome and unflexible, so I dropped it in favor of a classic LaTeX format (take a look at the main.pdf a few commits back if you're interested in the old format). The first 41 SCPs were added by hand before I started a first draft of the .mobi file for eBook readers.

This is where the project currently stands. To go on something along the lines of [Beautiful Soup](http://www.crummy.com/software/BeautifulSoup/) will have to be used to scrape the content from the wiki, don't know why I ever started going manual. Just seemed to be fun at the time (and I apparently hadn't read the first 40 SCPs).