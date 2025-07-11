![Python](https://img.shields.io/badge/Python-3.10-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Made with Jupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange)

# 📊 The Impact of AI on ASEAN Industry and Economy

> 🏅 **Top 10 Finalist** — Infographic Competition RASIO 8.0 (ASEAN-level)  
> 🏩 Organized by FMIPA Universitas Padjadjaran — *Statistics Day 2024*

---

## 📌 Overview

This project explores how **Artificial Intelligence (AI)** adoption is reshaping industrial productivity and economic growth across **ASEAN countries**.
We forecast **GDP by industry** using deep learning models and summarize results in an infographic format for public understanding.

- 📍 **Region**: Southeast Asia (ASEAN)  
- 🌐 **Scope**: Industry-level economic forecasting  
- 🤖 **Model**: LSTM Neural Network with time series data

---

## 🧵 Storyline & Key Highlights

### 1. Background
- 72% of companies globally are adopting AI.
- Southeast Asia is emerging as a digital transformation hub.

### 2. Research Focus
- Analyze AI adoption in key sectors: Tech, Finance, Government, Healthcare
- Forecast GDP growth by industry using LSTM

### 3. Key Insights
- ASEAN GDP by industry forecasted to reach **$3722 Bn USD by 2025**
- Highest AI adoption: **Tech (17%)**, **Finance (15%)**, **Telecom (15%)**
- Top manufacturing-based GDP contributors:  
  🇹🇭 Thailand (27%), 🇲🇾 Malaysia (24.8%), 🇸🇬 Singapore (21.6%), 🇮🇩 Indonesia (18.3%)

### 4. Real-world Use Cases in Manufacturing
- 🤖 Robotics Automation: Amazon warehouses
- 🛠️ Predictive Maintenance: Infrastructure Monitoring
- ✅ Quality Control: Samsung, Nvidia chip lines
- 🚚 Supply Chain Optimization: BMW inventory flow

---

## 🧠 Forecasting Model

> **LSTM (Long Short-Term Memory)** was used for multi-year GDP trend forecasting.

- Scaled time-series data using MinMaxScaler
- Built LSTM model with sliding windows (5-year sequences)
- Trained on historical GDP by industry (2015–2022)
- Evaluated with MSE loss metric

**📊 Result:** Model predicts **~2.74% GDP growth** in 2025

---

## 📁 Project Structure

```
impact-of-ai-asean/
├── forecasting-notebook.ipynb        # Main LSTM model
├── data/Book1.csv                    # Raw GDP data
├── images/
│   ├── infographic-final.png         # Competition infographic
│   └── chart_gdp_trend.png          # Forecast visualization
├── certificates/
│   └── RASIO_Farrel_Certificate.pdf # Proof of finalist
├── originality-statement.pdf
└── README.md
```

---

## 🏆 Competition Achievement

**RASIO 8.0** — Padjadjaran Statistics Olympiad 2024  
Organized by: Himpunan Mahasiswa Statistika, FMIPA UNPAD  
Track: Infographic Competition (ASEAN-wide)  
Theme: *"The Impact of AI on Industry and Economy in Southeast Asia"*  
✨ **Selected as Top 10 Finalist** (Infographic Track)

---

## 👨‍💼 Team Members
- Farrel Julio Akbar
- Muhammad Bayu Syuhada
- Jeremia Susanto

---

## 🛠️ Tools & Stack
- Python 3.10  
- Jupyter Notebook  
- TensorFlow / Keras (LSTM)  
- Pandas, Matplotlib  
- Time Series Forecasting, Scaling, Sliding Window

---

## 📚 References
- [TensorFlow Docs](https://www.tensorflow.org/)
- [Keras LSTM Guide](https://keras.io/api/layers/recurrent_layers/lstm/)
- [World Bank GDP Data](https://data.worldbank.org/indicator/NY.GDP.MKTP.CD)
- [AI Adoption Reports - McKinsey](https://www.mckinsey.com/capabilities/quantumblack/our-insights/global-survey-the-state-of-ai-in-2022)

---

## 📄 License
MIT License — Free to explore, fork, and reuse with attribution.

---

## 📬 Contact
- 🌐 [LinkedIn](https://www.linkedin.com/in/farrel-julio-427143288)  
- 📂 [Portfolio (Notion)](https://linktr.ee/Julio-analyst)  
- ✉️ farelrel12345@gmail.com
