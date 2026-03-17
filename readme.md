# 📊 WhatsApp Chat Analyzer

A comprehensive data analysis web application that transforms exported WhatsApp chat data into actionable insights. Built with Streamlit, this tool allows users to visualize messaging patterns, activity timelines, and linguistic habits.

---

## ✨ Key Features

- **Top Statistics:** Total messages, word count, media shared, and links shared.
- **Activity Timelines:** View messaging trends over days and months.
- **User Heatmaps:** Identify the most active participants in a group.
- **Linguistic Analysis:**
  - **Most Common Words:** Filtered to remove "stop words" for meaningful results.
- **Emoji Analysis:** Breakdown of the most frequently used emojis.
- **Dynamic Filtering:** Toggle between "Overall" group stats or specific user analysis.

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Frontend | Streamlit |
| Data Processing | Pandas |
| Regex | `re` (for chat parsing) |
| Visualization | Matplotlib |
| Utilities | `urlextract`, `emoji`, `collections` |

---

## 🚀 How to Run

**1. Clone the Repository:**
```bash
git clone https://github.com/your-username/whatsapp-chat-analyzer.git
cd whatsapp-chat-analyzer
```

**2. Install Dependencies:**
```bash
pip install streamlit urlextract pandas matplotlib emoji
```

**3. Run the App:**
```bash
streamlit run app.py
```

---

## 📂 Project Structure

```
whatsapp-chat-analyzer/
│
├── app.py                # Main entry point for the Streamlit dashboard
├── preprocessor.py       # Cleans and transforms raw .txt chat files into structured DataFrames
├── helper.py             # Logic for calculating stats, timelines, and common words
└── stop_hinglish.txt     # List of common filler words (Hinglish/English) to improve word cloud accuracy
```

---

## 📝 Usage Note

To use the analyzer, export your WhatsApp chat **(without media)** as a `.txt` file. Upload this file via the sidebar in the application to begin the analysis.
