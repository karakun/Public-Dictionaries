# Public Dictionaries
In this repositories we publish adapted dictionaries and artifacts resulting from our use of data protected by licenses requiring further publications.
The kind of license is specified within the subdirectory representing each single data source.
   
#### Contact
    Karakun AG
    Elisabethenanlage 25
    4051 BASEL, Switzerland
    
    email: hibu_at_karakun.com

## Published Data
Following kinds of data are published from every corresponding data source (for the currently considered 4 languages):
- _.input File_
  - Adapted text input file generated from the origiinal data source.
  - Each input file line has the format _citation-form ; inflected-form ; POS_
  - The input file format is used as input by the ixa-pipe-pos multilingual [Part of Speech tagger and lemmatizer](https://github.com/ixa-ehu/ixa-pipe-pos/) to create its lemmatizer dictionary, binarized as Finite State Automata (FSA) within a corresponding .dict file. 
- _.dict File_
  - This is the published FSA binary file containing the data compiled from .input file.
  - The file is used by the lemmatizer.
  - The automata are read by the ixa-pipe-pos using the [morfologik-stemming project](https://github.com/morfologik/morfologik-stemming).
- _.info File_
  - This is a property file where some dictionary meta data are listed.
  - This file must be present during the FSA generation, as well as during the FSA use as lemmatizer.


## Current Data Sources

### Wiktionary (CC-BY-SA)

The data are described in their specific language [Wiktionary page](https://en.wiktionary.org/wiki/Wiktionary:Main_Page) 

Shield: [![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

This work is licensed under a
[Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg







