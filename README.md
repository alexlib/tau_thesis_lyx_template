Tel Aviv University LaTeX and LyX styles
-----------------------------------------

Alex Liberzon, July 2013
http://www.eng.tau.ac.il/~alexlib

Tel Aviv University LaTeX and LyX styles are adopted from the University of Canterbury LaTeX and LyX styles, 
created by Etienne Laliberté, June 2009
http://www.assembla.com/code/psyche/subversion/nodes/thesis?rev=5

An example in PDF
-----------------

[Link to the Thesis_main.pdf built online thanks to latex.aslushnikov.com](http://latex.aslushnikov.com/compile?git=https://github.com/alexlib/tau_thesis_lyx_template&target=Thesis-main.tex)
Download 
---------

The single compressed Zip file:

https://github.com/alexlib/tau_thesis_lyx_template/zipball/master

or using Git:

        git clone git@github.com:alexlib/tau_thesis_lyx_template.git


Installation
------------


Install Lyx: www.lyx.org (maybe you'll need to install separately LaTeX, maybe LyX will include everything).



To install it:

1. copy ```tauthesis.cls``` to the appropriate LaTeX folder, e.g. under Ubuntu, copy it to: /usr/share/texmf/tex/latex
2. run "texhash" from the command line
3. copy ```tauthesis.layout``` to the appropriate LyX folder, e.g. under Ubuntu, copy it to: /usr/share/lyx/layouts
4. Reconfigure LyX by going to Tools > Reconfigure
  *   In LyX, the tauthesis style should now be available as a new document class.
  *   Make sure the TAU logo files (eps + pdf + png) are in the same folder as your document.
5. Open the Thesis-main.lyx file, and replace the fields with your text to write your thesis.
