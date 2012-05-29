Tel Aviv University LaTeX and LyX styles
-----------------------------------------

Alex Liberzon, May 2012
http://www.eng.tau.ac.il/~alexlib

Tel Aviv University LaTeX and LyX styles are adopted from the University of Canterbury LaTeX and LyX styles, 
created by Etienne Laliberté, June 2009
http://www.assembla.com/code/psyche/subversion/nodes/thesis?rev=5

An example in PDF
-----------------

[Link to the Thesis_main.pdf file via Google docs](https://docs.google.com/viewer?url=https%3A%2F%2Fgithub.com%2Falexlib%2Ftau_thesis_lyx_template%2Fblob%2Fmaster%2FThesis-main.pdf%3Fraw%3Dtrue)

Download 
---------

The single compressed Zip file:

https://github.com/alexlib/tau_thesis_lyx_template/zipball/master

or using Git:

        git clone git@github.com:alexlib/tau_thesis_lyx_template.git


Installation
------------


To install it:

1. copy ```tauthesis.cls``` to the appropriate LaTeX folder, e.g. under Ubuntu, copy it to: /usr/share/texmf/tex/latex
2. run "texhash" from the command line
3. copy ```tauthesis.layout``` to the appropriate LyX folder, e.g. under Ubuntu, copy it to: /usr/share/lyx/layouts
4. Reconfigure LyX by going to Tools > Reconfigure
  *   In LyX, the tauthesis style should now be available as a new document class.
  *   Make sure the TAU logo files (eps + pdf + png) are in the same folder as your document.
5. Open the Thesis-main.lyx file, and replace the fields with your text to write your thesis.
