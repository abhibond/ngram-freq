A program that will parse a text file and output the frequency with which pairs of two words appear next to each other in the text file. Program expects two inputs:

1. The file system path to the text file containing the lines of text
2. The file system path to a text file containing a list of the two word pairs. Each line of this file will have exactly two space separated words.

## Install & Run:

```
$ pip install -r requirements.txt
$ python ngram_freq_dict.py shakespeare.txt word-list.txt
$ python ngram_freq_cms.py shakespeare.txt word-list.txt
```