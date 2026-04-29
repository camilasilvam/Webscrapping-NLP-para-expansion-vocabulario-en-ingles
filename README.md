# English Vocabulary Mining Pipeline

## Overview

This project automates the extraction and analysis of English vocabulary from transcript-based learning resources.

Given an Excel file containing hyperlinks to transcripts, the pipeline:

1. Navigates through each link
2. Extracts transcript text using web scraping
3. Cleans and preprocesses the text
4. Identifies the most frequent words
5. Detects phrasal verbs (special focus)
6. Generates a clean frequency ranking
7. Maps each word to the transcripts where it appears

The final output helps optimize English vocabulary study by prioritizing the most relevant and repeated words.

---

## Technologies Used

* Python
* Pandas
* BeautifulSoup
* Requests
* SpaCy
* NLP preprocessing
* Frequency analysis
* Excel automation

---

## Input

Excel file containing transcript URLs:

`data/input/links.xlsx`

Example:

| url                  |
| -------------------- |
| https://example1.com |
| https://example2.com |

---

## Output

### transcripts.xlsx

Contains all extracted transcript texts.

### frequent_words.csv

Contains:

* word
* frequency
* transcript source


## Business Value

This solution reduces manual vocabulary extraction time and improves language learning efficiency by focusing on high-frequency words and phrasal verbs with real contextual usage.
