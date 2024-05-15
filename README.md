# WhatsApp Chat Analyzer

## Overview
The WhatsApp Chat Analyzer is a Python-based tool for analyzing chat data exported from WhatsApp. It provides various functionalities for preprocessing the data, extracting insights, and generating visualizations to better understand communication patterns and trends within the chat.

## Modules
1. **preprocessor.py**: Contains functions for preprocessing raw chat data, extracting essential information such as messages, dates, and user details, and structuring the data into a pandas DataFrame.

2. **helper.py**: Includes helper functions for statistical analysis, visualization generation, and other data processing tasks required for chat analysis.

## Libraries Used
- `pandas`: For data manipulation and analysis.
- `matplotlib`: For creating visualizations such as plots and charts.
- `seaborn`: For enhancing the aesthetics of visualizations.
- `urlextract`: For extracting URLs from chat messages.
- `wordcloud`: For generating word cloud visualizations.
- `emoji`: For handling emojis in chat messages.
- `collections`: For counting occurrences of elements in lists.

## Functions
1. **preprocess(data)**: Preprocesses raw WhatsApp chat data and returns a structured DataFrame.

2. **fetch_stats(selected_user, df)**: Fetches statistics such as message count, word count, media messages, and links shared for the selected user or overall.

3. **most_busy_users(df)**: Identifies the most active users in the chat.

4. **create_wordcloud(selected_user, df)**: Generates a word cloud visualization based on chat messages for the selected user or overall.

5. **most_common_words(selected_user, df)**: Identifies the most common words used in chat messages for the selected user or overall.

6. **emoji_helper(selected_user, df)**: Extracts emojis used in chat messages for the selected user or overall.

7. **monthly_timeline(selected_user, df)**: Creates a timeline visualization of chat activity per month for the selected user or overall.

8. **daily_timeline(selected_user, df)**: Creates a timeline visualization of chat activity per day for the selected user or overall.

9. **week_activity_map(selected_user, df)**: Generates a map of chat activity by day of the week for the selected user or overall.

10. **month_activity_map(selected_user, df)**: Generates a map of chat activity by month for the selected user or overall.

11. **activity_heatmap(selected_user, df)**: Generates a heatmap of chat activity by day and hour for the selected user or overall.

## Implementation
To implement the project:
1. Clone the repository to your local machine.
2. Install the required libraries using `pip install -r requirements.txt`.
3. Import the necessary modules (`preprocessor`, `helper`, etc.) into your Python script.
4. Call the desired functions with appropriate parameters to analyze the WhatsApp chat data and generate insights.

## Uses
- Social network analysis
- Customer feedback analysis
- Team collaboration optimization
- Sentiment analysis
- Personal insights and reflection

