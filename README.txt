NLP LAB JUPYTER NOTEBOOKS
Vardhaman College of Engineering — NLP Lab (A8708, R22)

CONTENTS
- Experiment 1(a): Word tokenization
- Experiment 1(b): Sentence tokenization
- Experiment 2(a): Remove numbers, punctuation and whitespace from a file
- Experiment 2(b): Word frequency in a file
- Experiment 3: Morphological analysis / POS tagging
- Experiment 4(a): WordNet synonyms
- Experiment 4(b): WordNet antonyms
- Experiment 5(a): Stemming vs lemmatization
- Experiment 5(b): WordNet lemmatization by POS
- Experiment 6(a): Print stop words
- Experiment 6(b): Remove stop words
- Experiment 7(a): Jaccard distance
- Experiment 7(b): Edit distance
- Experiment 8(a): Collocation extraction
- Experiment 8(b): Marriage relationship extraction with spaCy
- Experiment 9: POS and parse tree
- Experiment 10: Bigrams and trigrams
- Experiment 11: Customer review analysis case study

HOW TO USE
1. Extract this ZIP.
2. Open Jupyter Notebook or JupyterLab.
3. Open the desired .ipynb file.
4. Run cells from top to bottom.
5. For file-based experiments, create input.txt or test.txt in the notebook's working directory using the example data shown in the notebook notes.
6. Some experiments download NLTK datasets on first run and therefore need internet access the first time.
7. Experiment 8(b) needs spaCy and the en_core_web_sm model. Install with:
   %pip install spacy
   !python -m spacy download en_core_web_sm
8. Experiment 11 uses nltk, pandas and numpy. Install missing packages with:
   %pip install nltk pandas numpy

Expected outputs are included in each notebook as a markdown section. Outputs involving lexical databases, NLP models or statistical rankings may vary slightly by software/data version.
