# VaLexPB
VaLexPB - a lexicon of Brazilian Portuguese verb valences. https://github.com/jessemourao/VaLexPB

Author: Jessé de Sousa Mourão - jessemourao@hotmail.com

VaLexPB is a lexicon of Brazilian Portuguese verb valences, based on the LFG grammar and implemented in the Xerox Linguistic Environment - XLE. Since the lexicon was implemented as a component for the BrGram (https://github.com/LFG-PTBR/BrGram), the VaLexPB directory must be used and located in the the same directory of the config file of BrGram. 

Before using the lexicon, all the configurations for the grammar should be done. Everything that is needed is informed in the README file in the BrGram repository. 

To use the grammar with the VaLexPB, you need to compile a parser from the grammar by executing the following command on the XLE shell (ssuming your working directory is the VaLexPB folder):

create-parser config.lfg

To apply the parser on individual sentences from the testfile.lfg in the test folder, run:

parse-testfile tests/test-sentences.lfg 1 

where 1 refers to first sentence in the testfile.

For bug reports, comments, and suggestions, please write to: jessemourao@hotmail.com
