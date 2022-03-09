# Welcome to the DQW Text app repository! 📚

This repo contains the DQW text streamlit app code, however, the streamlit apps have been split into 5 for maintenance purposes:

- [Main Streamlit app 📊](https://share.streamlit.io/soft-nougat/dqw-ivves/app.py)
- [Tabular Data Section 🏗️](https://share.streamlit.io/soft-nougat/dqw-ivves_structured/main/app.py)
- [Audio Data Section 🎶](https://share.streamlit.io/soft-nougat/dqw-ivves_audio/main/app.py)
- [Text Data Section 📚](https://share.streamlit.io/soft-nougat/dqw-ivves_text/main/app.py)
- [Image Data Section 🖼️](https://share.streamlit.io/soft-nougat/dqw-ivves_images/main/app.py)


The packages used in the application are in the table below.

| App section                |     Description    |     Visualisation    |     Selection    |     Package             |
|----------------------------|--------------------|----------------------|------------------|------------------|                       
|     Text                   |                    |                      |         x        |     [NLTK](https://github.com/nltk/nltk)  |
|     Text                   |                    |                      |         x        |     [SpaCy](https://github.com/explosion/spaCy)               |
|     Text                   |          x         |                      |         x        |     [TextBlob](https://github.com/sloria/TextBlob)            |
|     Text                   |          x         |           x          |                  |     [WordCloud](https://github.com/amueller/word_cloud)           |
|     Text                   |          x         |                      |         x        |     [TextStat](https://github.com/shivam5992/textstat)            |


## Unstructured data - text

Key points addressed:
- Frequency - Count most common words with WordCloud package in Python. This is the quickest way of seeing what the handled data contents are, in addition, it provides visualisation in form of word clouds. 
- Analyse sentiment with TextBlob in case of classification tasks. We can investigate the polarity of the text and represent it in form of bar graphs. 
- Investigate readability of data with Textstat, typically used for determining readability, complexity, and grade level of a corpus. 
- Topic analysis.
- Provide an automated preprocessing based on methods on the market.

To complete the key points, the following subsections are created:
- Preprocessing of the data with file download option
- Basic analysis methods like number of unique words, characters
- N-gram analysis with NLTK
- PoS tagging with NLTK
- NER with SpaCy
- Topic analysis with LDA, including optimal number of topics generation with u_mass coherence score

## How to run locally

1.	Installation process:

    Create virtual environment and activate it - https://packaging.python.org/guides/installing-using-pip-and-virtual-environments/
    
    Clone or download files from this repo
    
    Run pip install -r requirements.txt
    
    Run streamlit app.py to launch app

2.	Software dependencies:

    In requirements.txt

3.	Latest releases

    Use app.py
