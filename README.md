# WhatsApp Chat Analyzer

This project aims to provide insights and analysis on WhatsApp chat data using Python. It includes functionalities to preprocess the chat data, perform statistical analysis, generate visualizations, and extract meaningful information from the chat.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/whatsapp-chat-analyzer.git
2. Install the required dependencies:
   pip install -r requirements.txt

Usage:
Preprocessing Data
The preprocess function in preprocessor.py is responsible for cleaning and structuring the raw chat data. It extracts user names, message contents, and date-time information, and creates a DataFrame with relevant columns for further analysis.

Statistical Analysis
The fetch_stats, most_busy_users, create_wordcloud, most_common_words, emoji_helper, monthly_timeline, daily_timeline, week_activity_map, month_activity_map, and activity_heatmap functions in helper.py provide various statistical insights into the chat data. They calculate message counts, word frequencies, emoji usage, activity timelines, and more, allowing users to understand patterns and trends in the chat.

Streamlit App
The app.py file contains code for a Streamlit web application that provides an interactive interface for analyzing WhatsApp chat data. Users can upload their chat data file, select specific users for analysis, and visualize statistics, timelines, word clouds, and emoji usage.
