Daraz App Sentiment Analysis Project

A beginner-friendly sentiment analysis project using real customer reviews from the Daraz app (Google Play Store). Reviews were classified as Positive, Negative, or Neutral using Python and the VADER NLP model

## Dataset

* **Source:** Scraped from [Google Play Store - Daraz App](https://play.google.com/store/apps/details?id=com.daraz.android)
* **Collected using:** `google-play-scraper` Python library
* **Records:** 200 recent user reviews
* **Columns include:** Review Text, Rating (1–5 stars), Sentiment (Positive/Negative/Neutral)

## Project Goals

1. Collect real-world user feedback on Daraz
2. Use NLP techniques to classify reviews by sentiment
3. Visualize the overall sentiment trend
4. Derive insights to help improve user experience

## Sentiment Analysis Process

* Cleaned and structured review data
* Applied **VADER sentiment analyzer** from `nltk` to score each review
* Classified reviews into:

  • **Positive**
  • **Negative**
  • **Neutral**
* Visualized the sentiment distribution using Seaborn
  
## Visualizations & Outputs

* Sentiment distribution bar chart (Positive vs Negative vs Neutral)
* Clean CSV file with original reviews + assigned sentiment
* CSV export: `daraz_sentiment_analysis.csv`
  
## Tools & Libraries Used

* Python (Google Colab)
* `google-play-scraper`
* `nltk` (VADER Sentiment Analyzer)
* `pandas`, `seaborn`, `matplotlib`

## How to Run

1. Open the notebook in Google Colab: [Click here](https://colab.research.google.com/)
2. Copy-paste the code blocks from the repo
3. Run each cell step-by-step
4. The output CSV will be downloadable from the sidebar

## Key Learnings

* Learned how to collect data from real-world sources
* Understood how sentiment analysis works using VADER
* Gained hands-on experience with data cleaning, classification, and visualization
* Improved understanding of NLP and text processing workflows

## Future Improvements

* Include multilingual sentiment (e.g. Urdu + English)
* Apply deep learning-based models like BERT for better accuracy
* Build a dashboard using Streamlit to show live sentiment trends

## About Me

Hi! I'm **Hina** I’m passionate about exploring real-world data to uncover meaningful insights. . This is one of my NLP-based data projects — and it’s been a huge learning experience

## Contact

* GitHub: [hinazain28](https://github.com/hinazain28)
* Email: [hinazain28@gmail.com](mailto:hinazain28@gmail.com)
