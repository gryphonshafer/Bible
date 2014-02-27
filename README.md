# Bible #

A creative commons literal translation of the Bible. The content is released under the [Attribution-NoDerivatives 4.0 International (CC BY-ND 4.0) license](http://creativecommons.org/licenses/by-nd/4.0/deed.en_US). You may use the content, in whole or in part, for commercial and non-commercial purposes, provided you attribute the content and do not alter the content.

Each chapter is single text file. Each file's contents is marked up using the Open Bible Markup Language (OBML). As such, the start of each text file should contain a material reference indicating the content of the file. For example: `~ Titus 1 ~`.

## Open Bible Markup Language (OBML) ##

The following is a simplified key for content markup:

    ~...~    --> material reference
    =...=    --> header
    {...}    --> cross-references
    [...]    --> footnotes
    <...>    --> red text
    ^...^    --> italic
    4 spaces --> block-quote (line by line)
    6 spaces --> block-quote + indent (line by line)
    |*|      --> notes the beginning of a verse (numbers ignored)
    #        --> line comments

Quotes (single and double) should be stored in the file as "normal" quotes (i.e. not "smart" quotes). They will be converted to "smart" quotes on material render.
