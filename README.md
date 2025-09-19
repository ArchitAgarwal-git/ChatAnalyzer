# 📊 WhatsApp Chat Analyzer

A **Streamlit web application** that analyzes WhatsApp chat exports to provide detailed insights into group and personal conversations.  
It helps you explore statistics, activity patterns, most used words, emoji analysis, and much more with interactive visualizations.  

---

## ✨ Features
- 📈 **Chat Statistics**  
  - Total messages, words, media, and links shared.  

- 🗓️ **Timelines**  
  - Monthly and daily message trends.  

- 📅 **Activity Analysis**  
  - Most active days and months.  
  - Weekly activity heatmap (hour vs. day).  

- 👥 **User Analysis**  
  - Most active users in group chats.  
  - Percentage contribution of each member.  

- ☁️ **Word Analysis**  
  - WordCloud of most frequent words (with Hinglish stopword removal).  
  - Most common words table & bar chart.  

- 😀 **Emoji Analysis**  
  - Emoji usage frequency.  
  - Emoji distribution pie chart.  

---

## 🛠️ Tech Stack
- **Python 3.8+**
- [Streamlit](https://streamlit.io/) – Web app framework  
- [Pandas](https://pandas.pydata.org/) – Data manipulation  
- [Matplotlib](https://matplotlib.org/) & [Seaborn](https://seaborn.pydata.org/) – Visualizations  
- [WordCloud](https://amueller.github.io/word_cloud/) – Generate word clouds  
- [urlextract](https://pypi.org/project/urlextract/) – Extract links from text  
- [emoji](https://pypi.org/project/emoji/) – Emoji handling  

---

## 📂 Project Structure
- app.py # Main Streamlit app
- helper.py # Helper functions for analysis
- preprocessor.py # Preprocess WhatsApp chat text
- requirements.txt # Dependencies
- stop_hinglish.txt # Hinglish stopword list

## 📥 Exporting WhatsApp Chat

1. Open WhatsApp chat (individual or group).  
2. Go to **More > Export Chat > Without Media**.  
3. Save the `.txt` file and upload it in the app sidebar.  

---

## 📊 Example Insights

- **Top Statistics**: How many messages, words, and links were shared.  
- **Activity Map**: Find the busiest days and months.  
- **Heatmap**: See at what times users are most active.  
- **WordCloud & Common Words**: Discover the most used words.  
- **Emoji Analysis**: See which emojis dominate conversations.  

---

## 🔮 Future Improvements

- Add sentiment analysis (positive/negative/neutral messages).  
- Improve multilingual stopword filtering.  
- Export reports as **PDF/CSV**.  
- Add support for media (images, audio, video metadata).  
