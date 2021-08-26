# PCT_Fileshare
Files to share publicly related to PCT


When using PCT, certain special (PCT-specific) files are created. These include .corpus files (for PCT's storage of your corpora), .feature files (for storage of your transcription-to-feature files), .searches files (for storing saved search paramaters), and various .txt files (usually for listing specific results or errors that PCT encounters). 

This repository holds copies of the built-in .corpus and .feature files, which can be used for back-up or for direct download purposes.

Once PCT creates or downloads these files, they are automatically saved in your local hard drive for later use. Be default, your PCT working directory is either
“C:\\Users\\[USER NAME]\\Documents\\PCT\\CorpusTools\\” (for Windows machines), or “~/Documents/PCT/CorpusTools/” (for macOS or Linux machines).

You will find several directories in this directory:

 * “CORPUS” is the place for the corpus files you created or downloaded (cf. https://corpustools.readthedocs.io/en/latest/loading_corpora.html).
 * “ERRORS” is where you can find error messages for the environment exhaustivity (cf. https://corpustools.readthedocs.io/en/latest/predictability_of_distribution.html).
 * “FEATURE” is the folder where all your feature files are saved (cf. https://corpustools.readthedocs.io/en/latest/transcriptions_and_feature_systems.html).
 * “SEARCH” is where you can find recent phonological searches (recent.searches) and saved searches (saved.searches). See https://corpustools.readthedocs.io/en/latest/phonological_search.html#saving-searches for how to save a search.

If you are downloading the .corpus or .feature files from the GitHub repository (), you should put them into your local CORPUS or FEATURE folder to make sure PCT knows how to access them.

Please note that the working directory will not exist if you have never run PCT.
