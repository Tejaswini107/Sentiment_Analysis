# Sentiment Analysis on Product Reviews

## Overview
This project performs sentiment analysis on Amazon product reviews using Python and TextBlob. The goal is to classify customer reviews into Positive, Negative, and Neutral sentiments, visualize sentiment distribution, and derive business insights from customer feedback.

## Dataset
The project uses the Amazon Fine Food Reviews dataset.

Dataset file used:
- Reviews.csv

For this analysis, the first 5,000 reviews were used.

## Project Workflow
1. Loaded product review data using Pandas
2. Explored dataset shape, columns, and review text
3. Cleaned the dataset by removing null and duplicate reviews
4. Selected required columns: review text and score
5. Calculated sentiment polarity using TextBlob
6. Classified reviews as Positive, Negative, or Neutral
7. Visualized sentiment distribution using charts
8. Generated insights and business recommendations

## Technologies Used
- Python
- Pandas
- TextBlob
- Matplotlib
- Seaborn
- Regular Expressions
- Collections Counter

## Visualizations
The project includes:
- Sentiment count bar chart
- Sentiment percentage pie chart
- Polarity score distribution using violin plot

## Key Insights
- A large majority of reviews were classified as positive.
- Negative reviews commonly mentioned issues related to taste, flavor, food quality, and product expectations.
- Some low-rated reviews were still classified as positive, showing a limitation of rule-based sentiment analysis.
- Businesses can improve customer satisfaction by ensuring accurate product descriptions and better packaging quality.

## Limitations
- TextBlob is a lexicon-based sentiment analyzer and may not fully understand context, sarcasm, or mixed opinions.
- The analysis uses only a subset of 5,000 reviews.
- Star ratings and sentiment polarity may not always align perfectly.

## How to Run
1. Clone this repository.
2. Place `Reviews.csv` in the project folder.
3. Install the required libraries:
```bash
pip install -r requirements.txt

jupyter notebook analysis.ipynb 

```
## Future Improvements
- Use machine learning or deep learning models for more accurate sentiment classification.
- Include TF-IDF or word embeddings for text representation.
- Build an interactive dashboard for review analysis.
- Perform aspect-based sentiment analysis to identify specific product issues.
