Folder 'Supplemental-Materials/Nonlinear-ED/Part-I/' contains wxMaxima scripts
supporting the article '*On resonant generation of electromagnetic modes in nonlinear
electrodynamics. Part 1: Classical approach*'.

**Section 4.1**   One-dimensional cavity  / Single pump mode.   Use script '*(Section 4.1)   1D-Cavity Mono.wxmx*'

**Section 4.2**   One-dimensional cavity  / Two pump modes.     Use script '*(Section 4.2)   1D-Cavity Duo.wxmx*'

**Section 5.1**   Rectangular cavity      / Single pump mode.   Use script '*(Section 5.1)   3D-Cavity Mono.wxmx*'

**Section 5.2**   Rectangular cavity      / Two pump modes.     Use script '*(Section 5.2)   3D-Cavity Duo.wxmx*'

**Section 5.2.1** Rectangular cavity      / Two pump modes / Resonant solution for the 2 w1 - w2 signal mode. 
                                                                Use script '*(Section 5.2.1) 3D-Cavity Duo Special.wxmx*'

Generally, the scripts are designed to be easily configurable: the last three scripts slightly differ from each other
on initalisation stage, as well as the first two ones. For convenience and simplicity, the individual copies have been
made and set up for corresponding sections.

**Dependency**: all scripts rely on 'VCALC.MAC' package for CAS Maxima. File 'vcalc.mac' should be present either among
maxima's search directories or besides the scripts. A copy of 'VCALC.MAC' can be obtained from: https://homeweb.csulb.edu/~woollett/vcalc.mac

**Backups**: As long as some calculations take too much time (especially when general indices are processed) all scripts
export their results into external files. Note that some folders must be created manually before running each script for
the first time (see details inside the scripts).

The longest calculations are those for Section 5.2 and Section 5.2.1. Therefore, precomputed results (exported by the
corresponding scripts) are available in folders 'TM + TE' and 'TM(110) + TE(011)' respectively. They can be loaded into
scripts with the help of maxima's command *load(pathToFile)*, where one specifies 'pathToFile'. To begin with, try loading
all files from selected folder (into proper script, of course) and then execute 'Stage III' only.
