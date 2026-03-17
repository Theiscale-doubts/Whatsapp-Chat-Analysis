WhatsApp Chat Analysis (Streamlit App)

A simple yet powerful WhatsApp Chat Analyzer built using Python and Streamlit.
Upload your exported chat file and get meaningful insights like user activity, word usage, emoji trends, and timelines.

Features

Top Statistics

Total Messages

Total Words

Media Shared

Links Shared

Most Active Users

Identify top contributors

Percentage contribution of each user

Most Common Words

Removes Hinglish stopwords

Displays top 25 most used words

Emoji Analysis

Most frequently used emojis

Pie chart visualization

Timeline Analysis

Monthly activity trends

Daily message patterns

Tech Stack

Python

Streamlit

Pandas

Matplotlib

Regex (re)

emoji

urlextract

Project Structure

app.py → Main Streamlit app

helper.py → Analysis functions

preprocessor.py → Data preprocessing

stop_hinglish.txt → Stopwords list

README.md

How It Works

Export your WhatsApp chat as a .txt file

Upload the file in the app

The system:

Cleans raw chat data

Extracts users, messages, timestamps

Performs analysis and visualization

Run Locally

Install dependencies:
pip install -r requirements.txt

Run the app:
streamlit run app.py

Notes

Works with standard WhatsApp exported chat format

Supports both group and personal chats

Detects media messages and links
