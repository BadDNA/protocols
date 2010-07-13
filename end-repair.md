Title: End\-polishing for cut DNA fragments
Author: Travis C. Glenn1,2, [Kenneth L. Jones1,2, Myriam Belanger2,3, Roger Nilsen2] and Brant C. Faircloth4
Address1: Department of Environmental Health Science, University of Georgia, Athens, GA 30602\-2102, USA
Address2: Georgia Genomics Facility, University of Georgia, Athens, GA 30602\-2102, USA
Address3: Department of Infectious Diseases, University of Georgia, Athens, GA 30602\-2102, USA
Address4:  Department of Ecology and Evolutionary Biology, University of California, Los Angeles, CA 90095, USA
Contact: Travis C. Glenn
ContactEmail:  travisg _at_ uga _dot_ edu

### Summary

Following random shearing, the resulting DNA strands can be ragged (versus blunt) and/or incompatible due to the way that shearing breaks the DNA backbone.  We will fill in the ragged ends using the Klenow fragment which can fill in recessed 3’ ends while removing 3’ overhangs.  We will also phosphorylate the 5’ ends using polynucleotide kinase.

### Goal

To repair/polish sheared DNA ends. 

### Detailed Steps

1. Assuming you are starting with ~5 ug of DNA, use the following recipe for a 30 uL reaction in a 0.2 mL tube:

    | Volume        | Name                                      |        SKU    |
    : --------------| :-----------------------------------------|:--------------:|
    3.0 uL          | 10x Ligase Buffer                         | NEB # B0202S  |
    4.0 uL          | dNTP’s  (0.25 mM each -> 33 uM final) [1] | NEB # N0446S  |
    1.0 uL          | DNA Polymerase I - Klenow * [2]           | NEB # M0210   |
    1.0 uL          | T4 Polynucleotide Kinase                  | NEB # M0201S  |
    1.0 uL          | dH2O                                      | Amresco # E476-100ML |
    ----            |                                           |               |
    + 20.0 uL         | Shredded DNA fragments (~5 ug)          |               |

    [1]:  use 1 unit/ug of DNA.  DO NOT use the exo- version (NEB #M0212S) here!  The target is 1 unit / ug of DNA; the enzyme is 5 units/uL; adjust volume used as necessary if DNA used varies significantly from 5 ug.

    [2]:  use 1 unit/300 pmol ends [10 units/uL]

1. Mix by pipetting up and down gently
2. Place in thermal cycler and run the program DNA_Polish:
    
    * 1 cycle of 25 C for 15 => hold at 15 C

3. Clean the samples by doing a Min-Elute. This will get rid of the dNTPs.