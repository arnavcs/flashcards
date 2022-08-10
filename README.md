# Flashcards
A cli tool to add terms and practice with a flashcard set for unix based systems.

## Storing Terms
Terms are stored in ${HOME}/.local/share/flashcards by default, and a new file is created for every new flashcard set.

## Help
Usage:
    flashcards [-s <set>] [-w <word>] [-m <meaning>]
    flashcards -h | -U | -V

Options:
    -s the flashcard set to be used ('default' if unspecified)
    -w the word
    -m the meaning
    -h show help text and exit
    -U fetch an update from github and exit
    -V print the version number and exit

Notes:
    If both the word and meaning are specified, a new flashcard will be added to the set.
    If only one of the word and meaning are specified, a matching flashcard will be searched for in the set.
    If neither are specified, a random flashcard will be displayed from the set.
