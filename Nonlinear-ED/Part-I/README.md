Directory 'Supplemental-Materials/Nonlinear-ED/Part-I/' contains wxMaxima scripts
supporting the article *'On resonant generation of electromagnetic modes in nonlinear
electrodynamics: Classical approach'*.

**Section 4.1**   One-dimensional cavity  / Single pump mode.   Use script *'(Section 4.1)   1D-Cavity Mono.wxmx'*

**Section 4.2**   One-dimensional cavity  / Two pump modes.     Use script *'(Section 4.2)   1D-Cavity Duo.wxmx'*

**Section 5.1**   Rectangular cavity      / Single pump mode.   Use script *'(Section 5.1)   3D-Cavity Mono.wxmx'*

**Section 5.2**   Rectangular cavity      / Two pump modes.     Use script *'(Section 5.2)   3D-Cavity Duo.wxmx'*

**Section 5.2.1** Rectangular cavity      / Two pump modes / Resonant solution for the 2 w1 - w2 signal mode.
                                                                Use script *'(Section 5.2.1) 3D-Cavity Duo Special.wxmx*'

Generally, the scripts are designed to be easily configurable: scripts 5.1 and 5.2.1 slightly differ from each other
in initialisation cells, as well as the scripts 4.1 and 4.2. For convenience and simplicity, the individual copies have been
made and set up for corresponding sections.

Script 5.2 functions also similar to 5.1 and 5.2.1, although it works with scalar equations instead of vector equations
(see Section 5.2 in the paper for details).

**Dependency**: all scripts rely on 'VCALC.MAC' package for CAS Maxima. File 'vcalc.mac' should be present either among
maxima's search directories or besides the scripts. A copy of 'VCALC.MAC' can be obtained from: https://homeweb.csulb.edu/~woollett/vcalc.mac

**Backups**: As long as some calculations take too much time (especially when general indices are processed) all scripts
export their results into external files. Note that some folders must be created manually before running each script for
the first time (see details inside the scripts).

The longest calculations are those for Sections 5.1, 5.2 and 5.2.1. Therefore, precomputed results (exported by the
corresponding scripts) are available in folders 'TM', 'TM + TE' and 'TM(110) + TE(011)' respectively. They can be loaded
into their scripts with the help of maxima's command *load(pathToFile)*, where one specifies 'pathToFile'. To begin with,
execute initialisation cells (3 cells in a script, marked with special comments), then try loading all files from folder
(that belongs to the script) and finally execute 'Stage III' only.
