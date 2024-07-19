# LLM_content_analysis
Here lies all the code I used to do things for my master's thesis, studying the policy narratives on air pollution in India. It consists of a notebook through which I extracted text data into dataframes, an exploratory analysis of that data, and processing the data using large language models.

# Article Extractor 
This is what I used to take all the content from the news articles I downloaded in docx format and put them into a comma separated values file to use in Python

# Initial Analysis of Articles
This is what I used to get a description of the data. Things like the word count distribution, distribution of articles across the years, word cloud of columns, etc.

# Gemini
This is what I used to make API calls to Gemini for automated coding.

# Analysis of Coded Articles
This is what I used to analyze the distributions of narrative elements, make N-grams of characters, etc.

# Narrativity Index
Here, I make the narrativity index distributions for the coded articles.

# Setting Plot Thesis
Here, I plot the settings as identified in the articles. The area in the settings should be aggregated to a district level, which will involve a fair amount of manual work, but in the end it yields a beautiful map of India with the settings highlighted according to count.

# Sequential Model - RAG
Here, you can use an LLM of your choice, all you need is a HuggingFace Token. Retrieval Augmented Generation has also been enabled to add the codebook or other relevant data to reduce LLM hallucination.

# Manually Coded Articles
This is the dataset of 297 articles that I manually annotated using the codebook developed.
