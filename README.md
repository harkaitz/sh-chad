CHAD
====

A man(1) like command for accessing user notes.

## Help

chad

    Usage: chad { -V | [-e[x]] [CAT] [NAME] | -k TERM }
    
    Fast note accessing tool, similar to man(1). Notes are written
    in markdown language (.md) and stored in a directories listed
    in $CHADPATH (by default ~/.chad:/usr/share/doc/chad).
    
      -V                 : Show configuration variables.
      -e[x] [CAT] [NAME] : Edit note [in a gui].
      -k TERM            : Search term in notes.
      [CAT] NAME         : Open note with less(1) or $READER.
      (empty)            : List categories.
    
    You can configure the text editor by setting $EDITOR and $XEDITOR, by
    default "vi" and "xterm -e vi" are used.

## Collaborating

For making bug reports, feature requests, support or consulting visit
one of the following links:

1. [gemini://harkadev.com/oss/](gemini://harkadev.com/oss/)
2. [https://harkadev.com/oss/](https://harkadev.com/oss/)
