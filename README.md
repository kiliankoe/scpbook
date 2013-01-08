SCP book
=======

Seeing how the old PDF project seems to be available but more or less dead and also
formatted as simple ODT files, I set out to create a more flexible version of the
database.

The original idea was to capture it in a form compatible with eBook readers like the
Amazon Kindle, seeing how that turned out to be more of a hassle starting out, I chose
to start off with a PDF version typeset in LaTeX (I learned quite a bit of LaTeX in
the process of doing so). Formatting was to be the same of the old PDF project, same 
font, same background and so forth. This proved to be more than tiresome and unflexible, 
so I dropped it in favor of a classic LaTeX format (take a look at the main.pdf a few 
commits back if you're interested in the old format).
The first 41 SCPs are in the PDF version, which is more than I anticipated. I'll cut 
this PDF off here. It's just too tedious too go on, but I encourage any and everyone to
participate. The source files are all there. Just open the main.tex in your favorite text
or TeX editor and get going.

What I rather want to focus on is the first idea, creating the eBook version for reading
on the Kindle. Seeing how I missed this from the beginning and how I'd love reading
the SCP Wiki on the go, this will be ideal.

The methods of doing so are still a bit fuzzy though. The quickest and dirtiest way
seemed to be across the hell of Microsoft Word and then converting that into HTML which
then gets processed either through Amazon's very own KindleGen or Calibre. Definitely 
not enjoying MS Word very much, so direct HTML will probably be the way to go.
Let's see where this is going.
