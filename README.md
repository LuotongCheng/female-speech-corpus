# Exploring the Power of Female American Political Speeches in the 20th Century
## Introduction
Female American political speeches of the 20th century have played a crucial role in shaping political discourse, challenging gender norms, and contributing to gender equality. This research aims to analyze and explore the most significant speeches by female political figures during this era. 
## Potential Research Questions
- What are the key semantic features present in these speeches?
- What were the popular political topics during the 20th century?
- How did these speeches by females contribute to shaping political discourse?
- What role did these speeches play in advancing women's rights and influencing societal change?
## Documentation
###  Corpus Description
The corpus consists of data collected on the most significant female American political speeches of the 20th century. The data was collected through web scraping from the [American Rhetoric website](https://www.americanrhetoric.com/top100speechesfemales.htm) and is stored in CSV formats.
According to the [copyright policy](https://www.americanrhetoric.com/copyrightinformation.htm), some artifacts on the website are in the public domain and can be used freely by the public. These artifacts include certain rhetorical artifacts found in the "Top 100 Speeches" where the data of the corpus has been collected from. 
###  Target Audience and Intended Use
The target audience for this corpus is students, researchers, historians, linguists, cultural analysts, and the general public interested in studying female American political speeches. The corpus can be used for various purposes such as linguistic analysis, gender studies, political discourse analysis, etc.
###  Text Selection Criteria
The selection of speeches for this corpus was based on "THE TOP 100 SPEECHES," which is the 100 most significant American political speeches of the 20th century. The selection criteria were derived from a list compiled by [Professors Stephen E. Lucas and Martin J. Medhurst](https://www.americanrhetoric.com/newtop100speeches.htm).  Dr. Lucas is Evjue-Bascom Professor in the Humanities and Professor of Communication Arts at the University of Wisconsin at Madison. Dr. Medhurst (1952-2021) was the Distinguished Professor of Rhetoric and Communication at Baylor University (Texas).Given the focus on gender, only speeches by female speakers from the top 100 were included in this corpus.
###  Data Collection Process
1. Manually searching for the most famous speeches by women in the 20th century on the American Rhetoric website.
2. Creating a dataframe containing the speaker's name and the corresponding link to their speech transcript.
3. Using web scraping techniques to collect the speech transcripts of each link.
4. Saving the transcripts and metadata of the speeches in a CSV file.
###  Cleaning and Preprocessing Steps
During the web scraping process, the transcript texts were almost cleaned by removing white spaces, newline characters (\n), tab characters (\t), and carriage return characters (\r). The cleaned text was then joined into a single string for further processing.
###  Annotations and Tools Used
The corpus includes annotations such as tokens, lemma, part-of-speech (POS) tags, proper nouns, nouns, adjectives, named entities, and named entity words (NE words). The tools used for these annotations are pandas and spaCy.
###  Format of Files in the Corpus
The corpus includes a CSV file that contains the following variables:
- Title: Title of the speech
- Year: Year of the speech in standard year format
- Speaker: Name of the speaker
- Transcript: Full text of the speech
### Quality Check
1. Data collection process involves the selection of the most famous speeches by women in the 20th century on the American Rhetoric website. The criteria may be subjective and include biases of individual researchers and institutions.
2. Data Cleaning and Preprocessing aims to enhance the accuracy and quality of the data.
3. Corpus Size is small. It may not encompass all significant speeches by women during 20th century. Also, there is a need for considering various political parties, races, and ethnicities to provide a more comprehensive representation.
## Output CSV File with Annotations
- Doc: Document or text file processed by the spaCy library.
- Tokens: Individual words or text units.
- Lemmas: Base or normalized forms of words.
- POS: Part-of-speech tags indicating grammatical category.
- Proper nouns: Names of specific people, places, organizations, etc.
- NOUN: Nouns used in speeches.
- Adjectives: Adjectives used in speeches. 
- Named entities: Specific named objects mentioned in the text identified by spaCy library.
- NE words: Words identified as named entities within the text.
## Files
- CSV file: women_speech.csv contains basic information of each speech.
- Codes (Jupyter Notebook): corpus_collecting.ipynb records the corpus collecting, processing, cleaning process. women_speech.ipynb records the analysis and annotations of the corpus.
- women_speech_annotated.csv: file with all corpus data and annotations.  
