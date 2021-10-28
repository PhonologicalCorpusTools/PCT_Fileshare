There are two folders: SPE and Hayes. These refer to the feature values that are used for interpreting transcription symbols: either based on the Sound Pattern of English SPE; Chomsky & Halle 1968) or Bruce Hayes' Introductory Phonology textbook (2009). Within each folder, you will see multiple files, each with a name like ipa2spe or ipa2hayes. The convention for these file names is to put the name of the transcription system first (IPA, Klatt, Arpabet, etc.), then the numeral '2' (representing the concept of 'to'), and then the name of the feature system (SPE or Hayes). So e.g., 'ipa2hayes' is a feature file that gives information for all IPA symbols to be interpreted using Hayes' feature system.

The .feature files are ones that can be read only within PCT itself. The .xlsx files are provided as 'master', human-readable versions of all the .feature files, with each tab in the spreadsheet representing one .feature file. 

To download a file, please click on the file name and then select the "Download" button from within GitHub, rather than, say, right-clicking on the file name, which won't download the right type of file and may cause PCT to crash. 

1. SPE feature systems
- Feature files in this folder have two additional columns ('consonantal' and 'syllabic') to the existing (i.e., pre-2020) SPE features.
- Rhotic vowels were removed as the SPE book did not cover them.
- Featural specifications in xx2spe.feature are aligned to ipa2spe.feature as the baseline (i.e., each segment in transcription systems was first translated to IPA and then values are given following ipa2spe).
- anything2spe.xlsx provides all information including where to find justification for each valuation and correspondence between each transcription system and IPA.

2. Hayes feature systems
- Rhotic vowels are specified as suggested in Hayes (2008, p. 99)
- Several corrections were made on feature values to align with the Hayes textbook.
- Diphthongal features were added.
- Featural specifications in xx2hayes.feature are aligned to ipa2hayes.feature as the baseline (i.e., each segment in transcription systems was first translated to IPA and then values are given following ipa2hayes).
- anything2hayes.xlsx provides all information including where to find justification for each valuation, and correspondence between each transcription system and IPA.
