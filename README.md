# Digital project NLP
### Description
Text mining and NLP analysis on ‘The Quantified Self’ speeches transcripts.
The project goal is to exlore the discourse of the presentations that people have given about their own self-research projects. 

'The Quantified Self is an international community of users and makers of self-tracking tools who share an interest in “self-knowledge through numbers.” If you are tracking for any reason - to answer a health question, achieve a goal, explore an idea, or simply because you are curious - you can find help and support here.'

# The project steps
### Web scraping and dateset merging
BeautifulSoup and requests scraping functions by 'class' :'transcript'
### Cleaning the text and preparing for the analysis
Lower casing, removing stopwords (english language + additional) and noise, lemmatization, tokenization
### EDA
Word frequancy analysis , wordclouds, detecting bi and tri grams
### Topic modeling 
Creating the matrix, building the model and visualization of topics with labels 
### Named-entity recognition
Spacy NLP text pre-processing, entities recognition,dataframe of entities creation, visualization with wordclouds

# Installation guide
### Code and Data
<code>notebook.ipynb</code>: Python code with web scraping,  creation of the dataframe, preprocessing and cleaning the text, visualisation of the discourse and NLP analysis Named-entity recognition

The data consists of two files:
<li><code>qs-show-and-tells - qs-show-and-tells.csv</code>: dataset with 340 links to the transcrtipts, videos, topics and tools
  
<li><code>final_data.csv</code>: output dataframe with scraped transcripts, tools and topics
  
<code>requirements.txt</code>: required libraries and packages

### Credits
<li>Bastian Greshake Tzovaras <bastian.greshake-tzovaras@cri-paris.org> Long Term Fellow CRI Paris for providing the dataset
<li>The Quantified Self website https://quantifiedself.com/ for provided data

### Licensing
MIT license <code>mit</code>
