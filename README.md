## 📊 WhatsApp Chat Analyser

A Python-based data analysis tool to generate insightful statistics and visualizations from exported WhatsApp chat history. This project uses **Natural Language Processing (NLP)** and **data visualization** libraries to uncover patterns in group or individual chats.

---

### 🛠️ Tech Stack

* **Python 3.10+**
* **Streamlit** – to create interactive web app
* **Pandas** – data wrangling and analysis
* **Matplotlib / Seaborn** – data visualization
* **Regex (re)** – chat preprocessing
* **Numpy** – numerical operations
* **WordCloud** – for word frequency visual
* **Emoji / URLEXtract** – to analyze emojis and links
* **Scikit-learn / nltk** – (if advanced NLP like stopword filtering or clustering is used)

---

### 🚀 Features

✅ Upload `.txt` chat exports from WhatsApp
✅ Show top statistics: total messages, words, media shared, and links
✅ Identify most active users in group chats
✅ Generate word clouds and most used words
✅ Emoji analysis
✅ Timeline-based activity: monthly, daily, and weekly trends
✅ Hourly activity heatmaps
✅ Interactive UI via **Streamlit**

---

### 📁 Project Structure

```
whatsapp-chat-analyser/
├── app.py
├── preprocess.py
├── helper.py
├── stop_words.txt
├── requirements.txt
└── sample_chat.txt
```

---

### 📸 Screenshots

> Add images here:

* 📈 Message timeline
* 📅 Activity heatmap
* 💬 Word cloud
* 📊 User stats

---

### 🧪 How to Run

#### 📦 Step 1: Clone the repository

```bash
git clone https://github.com/namanp09/whatsapp-chat-analyser
cd whatsapp-chat-analyser
```

#### 📦 Step 2: Install dependencies

It’s recommended to use a virtual environment:

```bash
pip install -r requirements.txt
```

#### 🚀 Step 3: Run the app

```bash
streamlit run app.py
```

---

### 📝 How to Use

1. Export your WhatsApp chat as `.txt` file from your phone (without media).
2. Open the app in your browser.
3. Upload the file and choose analysis options.
4. View detailed visual insights instantly.

---

### 💡 Sample Analysis

* Total Messages: 3,245
* Media Shared: 215
* Most Active Time: 9 PM
* Top Emoji: 😂
* Most Active User: Alice

---

### 🔐 Privacy Disclaimer

* This tool runs **locally**.
* No data is stored or shared externally.
* Safe to use on private chats.

---

### 📈 Future Scope

* Sentiment analysis of messages
* Compare multiple chat groups
* Dark mode support for UI
* Export graphs as PDF/PNG
* Dashboard view using Plotly

<img width="1440" alt="Screenshot 2025-06-27 at 5 37 01 PM" src="https://github.com/user-attachments/assets/3b7de751-0165-4279-8c98-c893140e605e" />
<img width="1440" alt="Screenshot 2025-06-27 at 5 37 10 PM" src="https://github.com/user-attachments/assets/7fd8477d-b652-45f6-908b-8e3ac2eb18c2" />
<img width="1440" alt="Screenshot 2025-06-27 at 5 37 53 PM" src="https://github.com/user-attachments/assets/33f92d4f-6ed6-48e9-848d-b61829246dad" />

