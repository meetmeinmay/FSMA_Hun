# FSMA_Hun

Implementation of a morphological analyzer for Hungarian nouns, which will cover
the whole noun paradigm: number, possession, non-attributive possession and case declensions.

Morphological processes to be modeled are, predominantly, vowel harmony, but also cases of suppletion and consonantal assimilation.

The term xfst will refer to Xerox Finite State Tool, 
lexc will be used to refer to Lexical Compiler – definitions and terms introduces by Beesley and Karttunen in the book “Finite State Morphology”.

The recent project is principally based on the Carol Rounds book “Hungarian. An Essential Grammar”, also as a second source I used “Practical Hungarian Grammar”, by Törkenczy


The lexc implementation is organized the following way, 
each class of nouns separated out before, almost always has its own group of continuation classes. 
For the sake of convenience each group name prefixed with its corresponding prefix: 
every group for regular is prefixed with “reg”, irregular with “irreg” and etc.
