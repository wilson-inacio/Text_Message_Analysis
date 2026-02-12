# Text Message Analysis
## Project Overviw
This project analyses a text message dataset using Natural Language Processing (NLP) techniques to explore messaging behaviour, sentiment distribution and word importance. The analysis includes text preprocessing, sentiment analysis, visualization, word importance, wordcloud and geographic sentiment aggregation.

The goal of the project is to extract meaningful insights and conclusions from text messages using Python-based NLP tools and data visualization techniques.

## Objectives
* Load, clean and preprocess the data
* Sentiment analysis using VADER
* Analyze sentiment distribution and message length
* Create a choropleth map of average sentiment by country
* Visualize high-frequency terms using word cloud
* Interpret findings and key insights and discuss limitations

## Dataset
The dataset was obtained from the National University of Singapore and consists of:
* `Unnamed: 0` - Index
* `id` - Id of the sender
* `Message` - string containing the message sent
* `length` - number of characters that composes the message
* `country` - the sender's country
* `Date` - date the message was sent

## Key Findings
* Messages are predominantly friendly and informal, as is visible by the use of words such as 'lol', 'haha', 'ok', etc.
* Sentiment distribution tends toward posivite interactions, with much more positive or neutral texts than negative ones.
* Positive and negative messages tend to be much longer on average than neutral ones, showing a predesposition to write more when feeling strongly about something.
* Country-level sentiment averages are generally neutral to slightly positive, but country representations is very disparate.

## Limitations
* The data in the set is mostly made of Singaporeans and students, not being a faithful representation of the general population.
* Informal language and slang may reduce sentiment classification accuracy.
* Word clouds reflect frequency, not semantic meaning.

## Future Work
* Apply transformer-based models (e.g., BERT) for better sentiment accuracy.
* Identify conversation themes by performing topic modeling.
* Conduct a temporal analysis to explore sentiment variation over time.
* Expand dataset for cross-cultural and cross-generational comparison.

## Libraries Used
* Python
* Pandas
* Numpy
* NLTK
* Scikit-learn
* Matplotlib
* Plotly
* Regex
* WordCloud
