# Messenger_Analysis
Analysis of my personal data from Messenger, made in RMarkdown. I do not upload data used in project, as it includes sensitive informations.
You can downoload your own Messenger data by Settings -> Download Your Information, then check "Messages", set format as JSON and tap "Create file".
I try to regularly update file and creates new function, as I find it pretty interesting to analyze my Messenger usage. For now, code include:
* data import and preparing (I did it in Python, cause I failed with attempts to prperly read Facebook JSON file in R - bad encoding for special signs in polish alphabet)
* countplot - activity during time in conversation
* messages sent by user
* data cleaning for text analysis - include stopwords removing (there are also some stopwords specific for conversation, you could ignore that), emojis and special signs cleaning, unifying polish special signs (e.g. "ą") with their latin prototypes and some common cleaning steps
* barplot and wordcloud with most popular words in conversation
* animated plot with messages sent by users with time dimension
Potential next steps include reaction's network analysis, activity by hours, finding specific words for users and emoji analysis.
