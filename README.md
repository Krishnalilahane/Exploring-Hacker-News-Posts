# Exploring-Hacker-News-Posts
This repository contains the analysis of Hacker News posts to explore trends, user engagement, and content types.

## Overview

This project involves analyzing data from Hacker News to understand the following:
- Trends in post popularity and engagement over time.
- Distribution and types of content that attract more attention.
- Sentiment and topic modeling of posts to gauge general sentiment and prevalent themes.

## Data

The dataset used in this analysis includes:
- **Post Titles:** Title of the post.
- **URL:** URL associated with the post.
- **Text:** The body text of the post.
- **Score:** The score given to the post.
- **Time:** Timestamp when the post was created.
- **Type:** Type of post (e.g., comment, story).
- **Other Metadata:** Includes fields like parent, descendants, ranking, deleted status, and timestamp.

## Installation

To set up the project locally, follow these steps:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/krishnalilahane/Exploring-Hacker-News-Posts.git
   cd hacker-news-posts-analysis
   ```

2. **Install Required Packages:**
   Create a virtual environment and install the necessary packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

### Data Analysis

Run the analysis scripts to perform various data analyses:
- **Exploratory Data Analysis (EDA):** `analysis/eda.py`
- **Sentiment Analysis:** `analysis/sentiment_analysis.py`
- **Topic Modeling:** `analysis/topic_modeling.py`

### Visualization

Generate visualizations to illustrate findings:
- **Trend Analysis:** `visualizations/trend_analysis.py`
- **Sentiment Distribution:** `visualizations/sentiment_distribution.py`

### Reports

Generate detailed reports based on the analysis:
- **Summary Report:** `reports/summary_report.md`
- **Presentation:** `reports/presentation.pptx`

## Key Insights

1. **Word Cloud of Post Titles:** Common terms include "Unknown," "Title," "Ask," "HN," and "Show," with a focus on tech giants and startups.
2. **Sentiment Distribution:** Most titles have neutral sentiment, suggesting an informational nature rather than emotionally charged content.
3. **Engagement Trends:** Analysis shows fluctuations in comments and post scores, with notable trends in post quality and user engagement.

## Recommendations

1. **Focus on Informational Titles:** Craft clear and descriptive titles to attract more readers.
2. **Leverage Popular Topics:** Prioritize content related to trending tech topics.
3. **Encourage Engaging Post Types:** Promote "Ask HN" and "Show HN" posts to boost engagement.
4. **Improve Title Quality:** Address issues with generic or placeholder titles.

## Contribution

Contributions are welcome! If you have suggestions, improvements, or bug fixes, please open an issue or submit a pull request.
