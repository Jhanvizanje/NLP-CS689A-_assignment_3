Python Version: Python 3.9.7 

Base: conda

Warning:
This Python interpreter is in a Anaconda environment.

## Dependencies

The code provided in this repository requires the following dependencies:

- [NLTK](https://www.nltk.org/): A platform for building Python programs to work with human language data.
- [Sacremoses](https://github.com/alvations/sacremoses): A tokenizer and detokenizer for various NLP tasks.
- [Pandas](https://pandas.pydata.org/): A powerful data manipulation library.
- [Regex](https://docs.python.org/3/library/re.html): A module for working with regular expressions.
- [Mock](https://docs.python.org/3/library/unittest.mock.html): A library for testing in Python.
- [Transformers](https://github.com/huggingface/transformers): A state-of-the-art natural language processing library.
- [MosesTokenizer](https://github.com/alvations/sacremoses): A tokenizer for various languages.
- [Bitsandbytes](https://pypi.org/project/bitsandbytes/): A library for working with bytes and bits.
- [SciPy](https://www.scipy.org/): A library for mathematics, science, and engineering.
- [Accelerate](https://github.com/huggingface/accelerate): A library for distributed training and inference in PyTorch.
- [Datasets](https://github.com/huggingface/datasets): A library for accessing and exploring datasets and evaluation metrics.
- [Sentencepiece](https://github.com/google/sentencepiece): A tokenizer and detokenizer library for various NLP tasks.
- [rouge]

Steps to Run Assignment:
1. Extract 231110021_Assignment3.zip in your local system. 
2. Open 231110021.ipynb file in your idle environment.
3. Change the data path according to your file location(second cell), I have used Gujarati text corpus,English text corpus and Marathi text corpus.
4. Run the ipynb file in your preffered IDE.

Output:-
1. Translation output is generated in below mentioned text files.
- NLLB 200
    - [eng_to_gu.txt] english to gujarati translation
    - [gu_toen.txt] gujarati to english translation
    - [gu_to_mr.txt] gujarati to marathi translation
    - [mr_to_gu.txt] marathi to gujarati translation
- IndicTrans
    - [eng_to_gu_mbart.txt] english to gujarati translation
    - [gu_to_en_mbart.txt] gujarati to english translation
    - [gu_to_mr_mbart.txt] gujarati to marathi translation
    - [mr_to_gu_mbart.txt] marathi to gujarati translation
- chatGPT output is stored in variables only in the 231110021.ipynb file



