# sub-cipher-solver
Basic substitution cipher solver following Carnegie Mellon and Cambridge English dictionaries

Solving paradigms:
Program maintains list of English words that are found in both aforementioned dictionaries for reference
Program also maintains a map from each word to its abstraction, in substitution cipher style, e.g. 
Printer -> ABCDEFB
Bookkeeper -> ABBCCDDEDF
Mississippi -> ABCCBCCBDDB

Program has two embedded frequency lists, one for "typical" English text, and another for dictionary words

To use:
Run the Python script and input ciphered text
