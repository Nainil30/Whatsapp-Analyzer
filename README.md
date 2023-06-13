# Whatsapp-Analyzer
A Streamlit WebApp that analyzes WhatsApp chat data 


# WhatsApp Chat Amayzer 📱💬

The objective of this project is to develop an interface for analyzing WhatsApp chats for businesses. The interface will allow users to upload their WhatsApp chat in text format and generate a report with interactive graphs. 

## Project Overview

The report will include analysis such as:

### Total Messages 📩

- Total number of messages
- Total number of words
- Number of media messages
- Number of links shared

### Chat Activity 📊

- Daily and monthly chat activity
- Most busy day and month
- Weekly activity map

### User Analysis 👥

- Most busy users

### Word Analysis 📝

- Top and common words in the conversation
- Emoji analysis

## Prerequisites

To develop this project, you should be familiar with Python basics and syntax, as well as the following libraries:

- Pandas 🐼
- Matplotlib 📊
- Streamlit 🌐

## How to Export Chat from WhatsApp? 📥

To export a WhatsApp chat for analysis, follow these steps:

1. Open the chat you want to analyze and click the three dots in the top right corner.
2. Click "More" and select "Export Chat" without media.
3. Share or download the text file of the chat. Make sure to convert the date and time setting to a 24-hour format before uploading the chat file.

## Data Analysis: Project Development Steps 🚀

1. **Create DataFrame from Chat File**
2. **Separate the Message and User Name**
3. **Breaking the Date Column into Different Columns**
4. **Display Basic Statistics for Data Analysis**

To find the most frequent words in WhatsApp chat data, we need to clean the data by removing group notifications, media omitted text, and stop words. If your chat data is in multiple languages, you can download a stop words file that supports both languages. The "remove stopwords" function checks each message for stop words and excludes them. The "remove punctuation" function removes any punctuation using the string module of Python and regular expressions (RegEx).

5. **Get the Total Number of Messages**
6. **Get the Total Number of Words**
7. **Get the Number of Media Messages**
8. **Get the Total Number of Links Shared**
9. **Find the Busiest Users in Group**
10. **Display Top Words in a Chat**
11. **Find the Top 20 Most Common Words**
12. **Emoji Analysis**
13. **Time-based Analysis**
14. **Monthly Chats Timeline**
15. **Daily Timeline**
16. **Day-based Activity Map**
17. **Monthly Activity Map**
18. **Which Time User Remains Active?**

## Creating Streamlit Web App after Data Analysis 🌐

After performing data analysis, you can create a Streamlit web app to display your results. Streamlit is a Python web framework that allows you to build data apps without front-end knowledge. 

To get started:

1. Create a project folder and install the required libraries.
2. Create the following Python files to organize your code:
   - `Preprocessor.py` for data preprocessing functions
   - `helper.py` for analysis functions
   - `app.py` for the main Streamlit code
3. Write the code in the respective files.
4. Run the app on your localhost by opening the command prompt in the project directory and running the appropriate command.

## Running the App on your localhost 🖥️

We are done with the coding, and now you must be thinking of how it will look on the server. Open the command prompt in the project file directory and run the following command. After running, you will get a localhost URL to copy and open
