IJCLab Beamer theme
=================

This is a beamer theme designed to mimic the PPT style for IJCLab slides available on the intranet:

              https://intranet.ijclab.in2p3.fr/communication-evenements/bureautique/

1) Update Beamer to a recent version (the template works for version 3.57 and later)

2) You can already check if the compilation works by pdflatexing the file example.tex directly

3) For later use, it bettter to put the files beamer...themeIJCLab.sty in the appropriate folders. In order to do this, go to your folder

texmf-local/tex/latex/beamer/base/themes/

and copy the following files in the corresponding subfolders :

- inner : beamerinnerthemeIJCLab.sty- outer :  beamerouterthemeIJCLab.sty and the subfolder beamerouterthemeIJCLab-fig- theme : beamerthemeIJCLab.sty- color : beamercolorthemeIJCLab-inner.sty and beamercolorthemeIJCLab-outer.sty

3) Run texhash (or sudo texhash if directories are indicated as not writable) in order to update ls-R, so that latex knows in which folder it shoud look for each .sty file.

4) You can then latex any presentation using the IJCLab Beamer theme without keeping all the files beamer...themeIJCLab.sty in the same folder.% Copyright 2022 by Sébastien Descotes-Genon
%
% This file may be distributed and/or modified
%
% 1. under the LaTeX Project Public License and/or
% 2. under the GNU Public License.