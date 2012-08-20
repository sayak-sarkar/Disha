Version 1.0.0
=============

First Major Version Of BN-DISHA Released On The 20th Day Of August 2012.

Version 0.4.6
=============

Fixed Logical Bug with A-kar state.

Updated System Icon.

Special Symbol Joins Fixed.

Conjoined Character Mappings Removed.

Half Pre-Vowel entry issue Resolved.

Combinational Character issue Resolved.

Backspacing Issue for Conjoined Characters Resolved.

Init State for Halant Updated.

Version 0.4.5
=============

Fixed all major bugs with Backspacing.

Fixed mapping logic with Au-kar inputs.

Code Cleaned Up.

Reduced logical complexity.

Updated Split-Vowel implementation logic.

Created new AltGr Mapping for ক্ত.


Version 0.4.4
=============

Resolved Split-Vowel definition issues.

Backspace freeze and unexpected Backspace behaviour fixed.


Version 0.4.3
=============

Reworked code related to Backspacing.


Version 0.4.2
=============

Split-vowels support added to Backspace.


Version 0.4.1
=============

Introduced automated ZWNJ Insertion for Two-Part Split-Vowels, and Buffer Commits for Pre-Vowels.

ZWNJ no longer needed for Joint Consonant Inputs under Pre-Vowel.


Version 0.4.0
=============

Visual Style Backspace support added.

Mapping issue for the character N resolved.


Version 0.3.0
=============

ং Post-Base Join Rendering Isssue solved by added mini-states for a-kar and au-kar under pre-vowel states to replace split combination of ে+া/ৗ with ো/ৌ.

Created new mini-state halant to identify pre-vowel + consonant + halant + consonant sequences.

Added ZWNJ mapping to | using AltGr. Now on, adding ZWNJ after a consonant joint counters Pre-vowel - Consonant issue.


Version 0.2.0
=============

Fixed mappings for the symbols '+' and '-'.

Added AltGr Character Input Support.


Version 0.1.1
=============

Fixed Pre-Vowel Consonant replacement issue.


Version 0.0.3
=============

Copyright Header Updated.

Pre-vowel Processing Logic Updated.

Code Base Comment Cleaned-up.


Version 0.0.2
=============

Input mapping based prototype implemented.

States updated for identifying Dependent Vowels.


Version 0.0.1
=============

Mapping Based Input Layout Implemented.
