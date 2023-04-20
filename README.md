# KWIC Searcher

This Java software provides a graphical user interface to search and visualise keywords in local documents and online web pages based on their
word form, lemma or [POS tag](https://www.ling.upenn.edu/courses/Fall_2003/ling001/penn_treebank_pos.html):

![View of the GUI](images/KWICSearcherGUI.png)

### Instructions

1. Download .jar file.
2. Run it (Java SDK needed).
3. By clicking on "file" a file navigator pops up. Alternatively you can copypaste the URL to a web page.
4. Type a search term.
5. Pick one between word form, lemma and POS tag.
5. Choose to display the whole sentence or just a few neighbouring words.
6. Click on the magnifying glass to search.
7. Optionally, save your search as XML.


### Resources:

- **Swing** environment (GUI).
- **Apache OpenNLP** library (models: _en-sent.bin_, _en-token.bin_, _en-pos-maxent.bin_, _en-lemmatizer.bin_).
- **JSoup** library (web scraping).


### Note

The source code of this project is not yet publicly available because parts of this program are a graded task for
students enrolled in the Computational Linguistics program at the University of Tübingen.
