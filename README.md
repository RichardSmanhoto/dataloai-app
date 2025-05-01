# 🧠 DataloAI

**DataloAI** is a smart data analysis platform that turns raw information into interactive charts, reports, and insights using artificial intelligence. Connect your data sources (like Shopify, VTex, or CSV files), and let the AI automatically generate visualizations and analyses for you.

---

## 🚀 Features

- 📊 Automatic chart generation from connected data  
- 💬 Natural language interaction: "Show sales by product"  
- 🛒 E-commerce data support (sales, products, customers)  
- 🌐 Simple web interface built with Streamlit  
- 🤖 OpenAI-powered insights and analysis  

---

## 📁 Project Structure

```text
dataloai/
├── src/               # Main source code
├── data/              # Simulated data (CSV, JSON, etc.)
├── notebooks/         # Prototypes and tests
├── requirements.txt   # Dependencies
└── README.md          # This file
```

---

## ⚙️ How to Run Locally

1. Clone the repository:

```bash
git clone https://github.com/your-user/dataloai.git
cd dataloai
```

2. Create a virtual environment:

```bash
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows
```

3. Install the dependencies:

```bash
pip install -r requirements.txt
```

4. Run the application:

```bash
streamlit run src/app.py
```

---

## 🔐 OpenAI API Key

Create a `.env` file and add your OpenAI key:

```env
OPENAI_API_KEY=sk-xxxxxxxxxxxxxxxxxxxx
```
