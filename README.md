# Welcome to CounselBot 🎓

**CounselBot** is a smart career guidance chatbot designed to help students explore the most suitable career paths based on their interests and background. Built using **Python, TensorFlow, and Streamlit**, it’s intuitive, powerful, and easily customizable.

This is the official open-source repository of **CounselBot**, created and maintained by [Chaitali9482](https://github.com/Chaitali9482).

![CounselBot UI](img/21.png)

---

## 🚀 What Can CounselBot Do?

- ✅ Answer general questions about colleges, streams, subjects, and careers  
- ✅ Start an interactive **personality test** to understand the best-fit careers for you  
- ✅ Generate a **detailed report** recommending the **Top 5 professions** aligned to your profile  
- ✅ Friendly web interface — works on Windows, Linux, Mac, and Android via browser

---

## 🧠 Key Features

- 🤖 Custom-built chatbot (no third-party APIs!) using **TensorFlow** and **FastText**
- 📊 Personality test and scoring engine
- 📋 CSV-driven datasets for subjects, occupations, and graduate programs
- 📁 Web app built using **Streamlit** — fast, responsive, and customizable

---

## ⚙️ How to Set It Up

### 1. 📦 Install Dependencies

```bash
pip install tensorflow
pip install bokeh
pip install numpy
pip install pandas
pip install streamlit
pip install joblib
pip install pathlib
pip install nltk




Clone This Repository
git clone https://github.com/Chaitali9482/CounselBot.git
cd CounselBot


Run the App
python setup.py
streamlit run app.py


CounselBot/
│
├── app.py              # Main Streamlit app
├── counselor.py        # Personality test logic
├── imagify.py          # Image management utility
├── Graduate.csv        # Graduation options
├── Occupations.csv     # Career dataset
├── Subjects.csv        # Subjects dataset
├── bot.csv             # Q&A database
├── botmodel.h5         # Trained chatbot model
├── tokenizer_t.pkl     # Tokenizer
├── words.pkl           # Word index
├── img/                # Static images
└── README.md           # You're reading it

