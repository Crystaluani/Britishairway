# Key Steps & Achievements:

# Web Scraping:
Utilized BeautifulSoup and requests to scrape 1000+ reviews from British Airways' profile page across 10 pagination levels.

# Data Cleaning & Preprocessing:

Removed noise such as HTML tags, special characters, dates, flight numbers, and repeated phrases.

Standardized text by expanding abbreviations (e.g., “BA” to “British Airways”) and dropping meaningless or overly short content.

Final dataset saved as cleaned_airline_reviews.csv.

# Exploratory Data Analysis (EDA):

Identified most frequent keywords using Counter.

Created visualizations: word cloud for top terms and sentiment score distribution using TextBlob.

# Sentiment Analysis:

Applied TextBlob to assign polarity scores to reviews.

Classified sentiments into Positive, Negative, and Neutral, revealing that ~67% of the reviews were positive.

# Machine Learning Model:

Built a Logistic Regression classifier using TF-IDF vectorization for text features.

Achieved an accuracy of 72.5% in predicting sentiment.

Evaluated performance via confusion matrix and classification report.

# Impact:
The project showcases how automated sentiment analysis can be applied to large-scale customer feedback to inform business strategy, enhance user experience, and prioritize service improvements.
