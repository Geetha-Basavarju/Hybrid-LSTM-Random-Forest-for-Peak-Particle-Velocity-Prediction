# PPV-Hybrid-Predictor 🚀
A hybrid **LSTM + Random Forest** model for predicting **Peak Particle Velocity (PPV)** in mining and construction blasting operations.

## 🔍 Overview
Blast-induced ground vibrations are a major safety concern in mining and construction.  
This project proposes a **hybrid deep learning + machine learning approach**:
- **LSTM** captures temporal dependencies in blasting parameters.
- **Random Forest** ensures robust final predictions.

Goal: Identify safe blasting zones while minimizing **environmental and human risks**.

## ⚙️ Tech Stack
- Python, TensorFlow / PyTorch
- scikit-learn, pandas, numpy
- Matplotlib / Plotly for visualization

## 📂 Project Structure
- `data/` → sample dataset  
- `notebooks/` → exploration & experiments  
- `src/` → modular source code (preprocessing, models, training)  

## ▶️ How to Run
```bash
# Clone repo
git clone https://github.com/Geetha-Basavaraju/PPV-Hybrid-Predictor.git
cd PPV-Hybrid-Predictor

# Install dependencies
pip install -r requirements.txt

# Run training
python src/hybrid_model.py
