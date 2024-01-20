# Documentation

## Corpus

This is a corpus containing all the lyrics of Mazzy Star's albums.

Mazzy Star is an American alternative rock band.

The language of the corpus is English.

It consists of metadata csv files, metadata and linguistic annotation csv files, and preprocess and annotation process codes on a Jupyternotebook file.

Metadata and data sources are <https://www.azlyrics.com/m/mazzystar.html> and <https://genius.com/artists/Mazzy-star>

If there are any missing items, please provide me with the information. I will supply as soon as possible.

The corpus may be updated in the future if Mazzy Star realise new creations.

## Target Audience 

Mazzy Star fans

Researchers in the field of linguistics, music, culture analysis, literature, media, .etc

## Intended Use

 Multiple linguistic analysis
 
 For appreciation
 
## Text Selection Criteria

Every song of the Mazzy Star's works is contained in this corpus. Any duplicated song is removed.


## Data Collection Process

I downloaded the text from the website.


## Cleaning and/or Preprocessing Steps

removing extra spaces in the texts
 
merging the metadata csv and txt files

## Annotations 

tool: spaCy

annotations: Doc, tokens, lemmas, POS, proper nouns, named entities, corresponding words to named entities

## Format of the Files in the Corpus

txt and csv 

## Description of the Columns in the CSV File.

TITLE: file name of each txt, also the title of the song

ALBUM: the album that the song of the lyric belongs to
	
YEAR	: the year when the song/album/EP released

TYPE	: in which form the song of the lyric was released, in an album, in the EP , or as the single

Text: the contents of the lyric

Doc: the original text and all of the linguistic annotations obtained when spaCy processed the text

Tokens: a list of tokens where the words, spaces, and punctuation markers in the Tokens column are separated by commas

Lemmas: the retrieval of the dictionary root word of each word

POS: the simple universal part-of-speech of each token in a text (such as noun, verb, adjective, adverb), and detailed tagging, which uses a larger, more fine-grained set of part-of-speech tags (for example 3rd person singular present verb)

Proper_Nouns	: words which have been fitted with the proper noun tag

Named_Entities: tags of named entities in the text, such as names, dates, organizations, and locations

NE_Words:objects of named entity tags


