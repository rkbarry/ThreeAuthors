# ThreeAuthors
This is the old Springer basic .bst file modified to give the first three authors for papers with four or more authors and all the authors if there are three or less.

This .bst file was originally created and was copyrighted by Patrick W Daly. Since it left copyright in 2004, I made a change to it to make it only give at most three authors. I make no gaurantee about functionality. 

From inside your .tex file just call this in the normal way:

\documentclass [11pt]{article}

\usepackage[authoryear]{natbib}
\bibliographystyle{Three_Authors}

\begin{document}
\nocite{*}
\bibliography{export-bibtex-2}
\end{document}
