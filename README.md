# Hotel-Review-NLP

Data source: The entire data is scrapped from TripAdvisor website

Inspired by: HNESTDS @ Kaggle

## Goal
Find Top N most similar sentences in corpus to meet the customer requirements based on hotel reviews.

## Actions
1. Data Cleaning
- lowercase
- tokenization
- stop words removal

2. Merge hotel list data & hotel review data
- combine review texts in a single column [all_review]

3. Embeddings

## Queries Sentence Input
For example, we inputs the queries as the following to find the top 5 hotels in Dubai which meet the requirements:
queries = ['hotel that is close to the airport ', 'Hotel with easy access for taxi']

## Output (Recommended hotels)
### (1) Query: hotel that is close to the airport 
Top 5 most similar sentences in corpus:
- Premier Inn Dubai International Airport Hotel
- Barjeel Heritage Guest House
- Golden Tulip Al Barsha
- Maisan Hotel
- Sleep 'N Fly Sleep Lounge

### (2) Query: Hotel with easy access for taxi
Top 5 most similar sentences in corpus:
- Premier Inn Dubai International Airport Hotel
- London Creek Hotel Apartments
- Orient Guest House
- Golden Tulip Al Barsha
- Maisan Hotel



