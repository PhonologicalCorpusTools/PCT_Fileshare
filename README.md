# PCT_Fileshare
*Files to share publicly related to PCT*


When using PCT, certain special (PCT-specific) files are created. These include .corpus files (for PCT's storage of your corpora), .feature files (for storage of your transcription-to-feature files), .searches files (for storing saved search paramaters), and various .txt files (usually for listing specific results or errors that PCT encounters). 

This GitHub repository holds copies of the built-in .corpus and .feature files, which can be used for back-up or for direct download purposes. There are also two 'master' feature files in .xlsx format ("anything2hayes.xlsx" and "anything2spe.xlsx"), which show how each transcription system's symbols get interpreted in each feature system. These can be downloaded for inspection and/or to serve as a starting point for creating a new transcription to feature system.

The repository also includes various 'support' files, such as handouts from past workshops and example 'raw' corpora of various types.

To use the .corpus and .feature files with PCT, you should save them to your PCT working directory. Be default, your PCT working directory is either

“C:\\Users\\[USER NAME]\\Documents\\PCT\\CorpusTools\\” (for Windows machines), or “~/Documents/PCT/CorpusTools/” (for macOS or Linux machines).

You will find several sub-directories in this directory:

 * “CORPUS” is the place for the corpus files you created or downloaded (cf. https://corpustools.readthedocs.io/en/latest/loading_corpora.html).
 * “ERRORS” is where you can find error messages for the environment exhaustivity (cf. https://corpustools.readthedocs.io/en/latest/predictability_of_distribution.html).
 * “FEATURE” is the folder where all your feature files are saved (cf. https://corpustools.readthedocs.io/en/latest/transcriptions_and_feature_systems.html).
 * “SEARCH” is where you can find recent phonological searches (recent.searches) and saved searches (saved.searches). See https://corpustools.readthedocs.io/en/latest/phonological_search.html#saving-searches for how to save a search.

If you are downloading the .corpus or .feature files from this GitHub repository (https://github.com/PhonologicalCorpusTools/PCT_Fileshare), you should put them into your local CORPUS or FEATURE folder to make sure PCT knows how to access them. Also, please download the file by clicking on it on GitHub and then choosing the "Download File" button from GitHub, NOT by right-clicking the file name and downloading -- the latter will save a pointer to the file rather than the file itself and cause PCT to crash.

Please note that the working directory will not exist if you have never run PCT.

The other folders in this directory, "Example_raw_corpus_files" and "Workshop_materials", are simply public-facing repositories of files, which you are welcome to download and store locally. They do not have any direct interaction with PCT, though the raw corpora could be loaded into PCT and subsequently turned in to .corpus files.
