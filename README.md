# Insights on Edgar Allen Poe's language use in his gothic short stories<br>

**1. Corpus**<br>
The corpus contains four short stories written by the American author Edgar Allen Poe (1809-1849): *The Assignation*, *The Black Cat*, *The Masque of the Red Death*, and *The Tell-Tale Heart*. These short stories constitute parts of his gothic fiction.<br>

**2. Target audience and intended use of the corpus**<br>
The corpus can be used by anyone interested in Edgar Allan Poe’s gothic literature especially from the perspective of his language use.<br>

**3. Text selection criteria**<br>
I aimed to select texts that can be downloaded as plain text files and that are openly accessible. I intended to gather short stories of the same genre, so that features of one specific style can be investigated and revealed through a series of texts. Another aspect I took into consideration is the limit of the number of word tokens (preferably not more than 10,000) stated in the instructions of Assignment 4. <br>

**4. Data collection process**<br>
I accessed the short stories through the Gutenberg project (https://www.gutenberg.org/), and downloaded them as plain text files with UTF-8 encoding. <br>
Source: https://www.gutenberg.org/ebooks/2148<br>

**5. Cleaning and pre-processing steps**<br>
I removed extra spaces from the text files (see Jupyter Notebook).<br>
**6. Tools and annotations**<br>

**7. File format description**<br>
The files in the data directory are the four short stories as text files (poe_the assignation.txt, poe_the black cat.txt, poe_the masque of the red death.txt, poe_the tell-tale heart.txt). <br>

Other files include: <br>
- the metadata about the short stories in a CSV file (metadata.csv) <br>
- the Jupyter Notebook (CD_Assignment4.ipynb) <br>
- the short stories annotated with spaCy tags in a CSV file (poe_short_stories_with_spaCy_tags.csv) . <br>

**8. Description of columns in the CSV file containing annotations**<br>

| Columns | Description |
| ------------- | ------------- |
| Filename | the name of the file |
| Author | the name of the author of the short story |
| Title | the title of the short story |
| Language | the language of the short story |
| Genre | the genre of the short story |
| First published | the year in which the short story was first published |
| Text | the short stories as plain texts |
| Doc |  |
| Tokens |  |
| Lemmas |  |
| POS | part of speech category tags |
| Proper_Nouns | words tagged as proper nouns |
| Adjectives | words tagged as adjectives |
| Named Entities | named entity tags |
| NE-words | words tagged as named entities |


![a photo of Edgar Allan Poe](https://media.poetryfoundation.org/uploads/media/default/0001/21/bd5c888c4689e6cd3583bbe7575a1a2cad3487f6.jpeg?w=1274&h=&fit=max&key=3&sig=8d502e04711b2041ace345b267647ca4bfe0881cdc1ec890ddc9c8b0f81331c3&1274)
