# 🌍 Green ML for Satellite Collision Prediction 🚀

This project demonstrates how **Green Machine Learning (lightweight ML)** can help in **Space Sustainability** by predicting satellite collision risk efficiently.  
We use a **Decision Tree Classifier**, which is lightweight, transparent, and consumes less computational power compared to heavy ML models.

---

## 💡 Motivation
- Space is getting crowded with satellites and debris.  
- Traditional ML models are accurate but require **heavy computation → more energy → more carbon footprint**.  
- Our solution: **Green ML (Decision Tree)** → faster, lighter, and greener.  

---

## ⚙️ How It Works
1. Input parameters for a satellite:
   - **Orbit (km)**
   - **Velocity (km/s)**
   - **Debris Density (objects/m³)**  
2. Train a **Decision Tree** on sample satellite collision data.  
3. Predict whether a satellite has **Low Risk (0)** or **High Risk (1)** of collision.  

---

## 🛰️ Example Results
### Dataset Sample
| Orbit (km) | Velocity (km/s) | Debris Density | Risk |
|------------|-----------------|----------------|------|
| 7000       | 7.8             | 2              | Low  |
| 7200       | 8.1             | 3              | High |

### Model Accuracy
### Decision Tree Visualization
![Decision Tree](tree_example.png)

### Prediction Output
---

## 🌱 Why Green ML?
- **Lightweight algorithm** → less computation.
- **Energy efficient** → reduces carbon footprint.  
- **Practical for onboard satellite AI** → runs on limited hardware.  

---

## 🚀 Future Scope
- Use real satellite datasets (NASA, ESA).  
- Compare with heavy models (Random Forest, Neural Networks).  
- Deploy as a cloud-based API for satellite companies.  

---

## 📂 Files
- `satellite_prediction.ipynb` → Jupyter Notebook with code.  
- `README.md` → Project documentation.  

---

## 👩‍💻 Author
**Annimol R B** — B.Tech IT | Aspiring Data Scientist | Passionate about Green AI & Space Sustainability 🌍✨
