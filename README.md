# 📊 The Impact of AI on ASEAN Industry and Economy

> 🏅 **Top 10 Finalist** — Infographic Competition RASIO 8.0 (ASEAN-level)  
> 🏛️ Organized by FMIPA Universitas Padjadjaran — *Statistics Day 2024*

---

## 🎯 Overview

Artificial Intelligence (AI) is reshaping Southeast Asia’s industrial landscape and accelerating digital economic growth.  
In this project, we **visualize** and **forecast** the impact of AI adoption on GDP by industry in ASEAN countries using **deep learning (LSTM)**.

- 📍 **Focus**: Predictive modeling of ASEAN GDP by industry  
- 🧪 **Method**: LSTM Neural Network (TensorFlow)  
- 🎨 **Output**: Infographic finalist of RASIO 8.0 SE-ASEAN competition

---

## 🧵 Storyline

1. **Background**  
   Southeast Asia is a key player in global digital transformation. With 72% of companies worldwide using AI, it has become a core driver of industrial productivity.

2. **Research Focus**  
   - Analyze AI adoption across sectors: Tech, Finance, Government, Healthcare, etc.  
   - Forecast GDP industry growth using LSTM neural networks

3. **Key Insights**
   - 📈 ASEAN GDP by industry forecasted to reach **$3722 Bn USD by 2025**  
   - 💡 Highest AI adoption sectors: Tech (17%), Finance (15%), Telecom (15%)  
   - 🌏 Top GDP contributors by manufacturing:  
     - 🇹🇭 Thailand (27%)  
     - 🇲🇾 Malaysia (24.8%)  
     - 🇸🇬 Singapore (21.6%)  
     - 🇮🇩 Indonesia (18.3%)

4. **Real-world AI Use Cases in Manufacturing**
   - 🤖 Robotics: Amazon (pick, pack, transfer)  
   - 🛠️ Predictive Maintenance: INM (water hydrants, D.C.)  
   - ✅ Quality Control: Samsung & Nvidia (chip production)  
   - 🚚 Supply Chain: BMW (demand & inventory optimization)

---

## 🧠 Forecasting Model (LSTM)

📁 [`forecasting-notebook.ipynb`](forecasting-notebook.ipynb)  
🔧 **Tech Stack**: TensorFlow, Keras, Pandas, Matplotlib  
🔍 **Steps**:
- Scaled time-series GDP data with `MinMaxScaler`  
- Sliding window sequence of 5 years  
- Trained LSTM to predict future GDP  
- Evaluated with MSE (Mean Squared Error)

> 📊 **Result**: Model predicts **2.74% GDP growth** in 2025.

---

## 📂 Project Structure

```
impact-of-ai-asean/
│
├── forecasting-notebook.ipynb     # Main LSTM modeling notebook
├── data/Book1.csv                 # Raw GDP data (2015–2022)
├── images/
│   ├── infographic-final.png      # Infographic design
│   └── chart_gdp_trend.png        # Forecast visualization
├── certificates/                  # Official proof of finalist
│   └── RASIO_Farrel_Certificate.pdf
├── originality-statement.pdf
└── README.md
```

---

## 🏆 Competition Details

**🎓 RASIO 8.0 — Padjadjaran Statistics Olympiad 2024**  
Organized by: Himpunan Mahasiswa Statistika, FMIPA UNPAD  
Scope: ASEAN-wide student competition  
Theme: *"The Impact of AI on Industry and Economy in Southeast Asia"*  
Result: **Selected as Top 10 Finalist (Infographic Track)**

---

## 👥 Team

- Farrel Julio Akbar
- Muhammad Bayu Syuhada  
- Jeremia Susanto

---

## 📄 License

MIT License — feel free to explore and use this project with attribution.
