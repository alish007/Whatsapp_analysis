
# WhatsApp-Chat-Analysis


## Content

1. [Description](#description)
2. [Project structure](#project-structure)

## Description

WhatsApp-Chat-Analyzer web app allows user to get analysis of their whatsapp chat data. User can see analysis of overall group (including all users) as well as of individual users.
User can get analysis of messages, timeline of usage, activity map, wordcloud, most active users, etc. All of these analysis can be shown for both overall group and individual
user.

## Project structure

```   
  ├── app.py                      Streamlit python application file 
  ├── helpers.py                  python file that contains helper functions for chat analysis 
  ├── datapreprocessing.py        python file for preprocessing raw text data from chat to dataframe
  ├── requirements.txt            list of all required libraries used in app
  ├── stop_hinglish.txt           contains all stop words 
  
``
