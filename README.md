# BLEU-score
To calculate the BLUE score

The Python program will take a two paths as parameters: the first parameter will be the path to the candidate translation (a single file), and the second parameter will be a path to the reference translations (either a single file, or a directory if there are multiple reference translations). The program will write an output file called bleu_out.txt which contains a single floating point number, representing the BLEU score of the candidate translation relative to the set of reference translations.

> python calculatebleu.py /path/to/candidate /path/to/reference
