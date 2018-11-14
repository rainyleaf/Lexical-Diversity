# Lexical-Diversity
Code written for processing large batches of .txt files to calculate lexical diversity. Written/updated from winter 2017-spring 2018.

Files for cleaning raw .txt:

cleaner_bulk.py (requires stripPunct.py)
splitter_bulk.py
treetag-batch.py (requires TreeTagger)

files for analyzing lexical diversity of cleaned texts:
MATTR_bulk.py
Dispersion_clusters_bulk.py (requires stop_words_finder.py)
Shannon_bulk.py
disparity_bulk.py (requires senseindex(condensed).txt)
specialness1 - specialness4.py (require COCA .txt files)
it_verb_adj_to_that_bulk.py
