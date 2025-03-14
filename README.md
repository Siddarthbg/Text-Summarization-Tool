# Text-Summarization-Tool

*COMPANY*: CODTECH IT SOLUTION

*NAME*: Siddarth B.G

*INTERN ID*: CT08WU25

*DOMAIN*: Artificial Intelligence

*DURATION*: 8 WEEKS

*MENTOR*: NEELA SANTOSH

*DESCRIPTION*: This Python script is a web scraper and text summarizer that extracts and condenses information from the website **https://mvjce.edu.in/** using **BeautifulSoup, urllib, re, and NLTK**. It first imports the necessary libraries, including BeautifulSoup for parsing HTML, urllib for fetching the webpage, re for cleaning text, and NLTK for natural language processing. The script downloads and reads the webpage content, extracting all paragraph (`<p>`) elements into a single text string. It then cleans the text by removing citations, extra spaces, non-alphabetic characters, and stopwords. The script tokenizes the text into sentences and words, calculates word frequencies, and normalizes them by dividing each frequency by the maximum occurrence. Next, it assigns scores to sentences based on the importance of the words they contain, ignoring sentences longer than 30 words to keep the summary concise. Finally, it selects the **top 7 most significant sentences** using the `heapq.nlargest()` function and prints them as a summary. While the script effectively summarizes webpage content, it has some limitations, such as missing NLTK stopwords (which requires downloading), indentation errors, and a hardcoded URL. Enhancements like making the URL dynamic, adjusting the number of summary sentences, and refining text processing would make it more robust. Overall, this script demonstrates a simple yet effective approach to **automated text summarization** using web scraping and natural language processing. 

*OUTPUT*:
