# Banking Feedback Sentiment Analysis

This project analyzes customer feedback from a banking dataset using Natural Language Processing (NLP) techniques in Python. The goal is to classify customer reviews into Positive, Negative, and Neutral sentiments and visualize the results for better business understanding.

## Project Objective

The objective of this project is to:
- analyze customer feedback data,
- identify sentiment patterns,
- understand the proportion of positive, negative, and neutral reviews,
- and highlight common words used in negative feedback.

## Tools and Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- TextBlob
- WordCloud
- Jupyter Notebook

## Dataset

The dataset contains banking customer feedback sentences stored in a CSV file.

## Project Workflow

1. Imported the required Python libraries.
2. Loaded the banking feedback dataset using Pandas.
3. Created a sentiment analysis function using TextBlob polarity.
4. Classified each sentence as Positive, Negative, or Neutral.
5. Calculated sentiment counts and percentages.
6. Visualized sentiment distribution using a pie chart.
7. Filtered negative reviews separately.
8. Merged negative reviews into one text string.
9. Generated a word cloud for negative feedback.

## Key Insights

- Most reviews were Neutral.
- Positive reviews formed the second-largest group.
- Negative reviews were the smallest segment, but they highlighted issues like credit, loan delays, service, fees, and app-related problems.

## Output Visuals

- Sentiment Percentage Pie Chart
- Negative Reviews Word Cloud

## Files in This Repository

- `banking_feedback_sentiment_analysis.ipynb`
- `banking_feedback.csv`
- `README.md`

## How to Run the Project

1. Download the repository files.
2. Open the notebook in Jupyter Notebook or JupyterLab.
3. Install the required libraries if needed:
   ```bash
   pip install pandas numpy matplotlib seaborn textblob wordcloud
   ```
4. Run all notebook cells step by step.

## Learning Outcome

This project helped strengthen practical skills in:
- sentiment analysis,
- text preprocessing,
- data visualization,
- and exploratory analysis using Python.

## Author

**Tushar**
Aspiring Data Analyst | Python | Excel | SQL | Data Visualization
