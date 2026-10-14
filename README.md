<div align="center">
<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=Poppins&weight=800&size=26&duration=3500&pause=1500&color=8E9A3B&center=true&vCenter=true&width=900&height=70&lines=%F0%9F%8C%B1%20Soil%20Nutrition%20%26%20Fertilizer%20AI" alt="Soil Nutrition & Fertilizer AI"/>

<b><i>Predict soil fertility and recommend fertilizers</i></b>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1000&color=36BCF7&center=true&vCenter=true&width=700&lines=%F0%9F%8C%B1%20Soil%20fertility%20prediction;%F0%9F%A7%AA%20Smart%20fertilizer%20recommendation;%F0%9F%A4%96%20Two%20ML%20models%20%2B%20Flask" alt="Typing SVG" />

<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/> <img src="https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white" alt="Flask"/> <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" alt="scikit-learn"/> <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas"/> <img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite"/> <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter"/> <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5"/>

<img src="https://img.shields.io/github/stars/PreciousBharath/SOIL-NUTRITION-PREDICTION?style=social" alt="stars"/> <img src="https://img.shields.io/github/forks/PreciousBharath/SOIL-NUTRITION-PREDICTION?style=social" alt="forks"/> <img src="https://img.shields.io/github/last-commit/PreciousBharath/SOIL-NUTRITION-PREDICTION?style=flat-square&color=blueviolet" alt="last commit"/> <img src="https://img.shields.io/github/repo-size/PreciousBharath/SOIL-NUTRITION-PREDICTION?style=flat-square&color=success" alt="repo size"/>
</div>

---

## 🌱 About the Project

Two ML models in one app: the first predicts **soil fertility / nutrition** from soil parameters, and the second **recommends the right fertilizer** based on soil type, crop and nutrient levels. Every prediction is saved in the user's **history**.

## ✨ Key Features

- 🔬 **Soil nutrition** prediction (pH category, season, photoperiod, soil type...)
- 🧪 **Fertilizer recommendation** by soil & crop
- 📜 Per-user prediction **history** (SQLite)
- 🔐 Register / login
- 📓 Separate notebooks for both models

## 🧠 How It Works

```mermaid
flowchart LR
S["🧪 Soil Parameters"] --> N["🤖 Nutrition Model"] --> F["🤖 Fertilizer Model"] --> R["🌱 Recommendation"]
```

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Language | Python 3 |
| Data & ML | Pandas · NumPy · scikit-learn |
| Notebook | Jupyter |
| Web App | Flask + Jinja2 templates |
| Frontend | HTML5 · CSS3 |
| Database | SQLite |

## 📂 Project Structure

```text
SOIL-NUTRITION-PREDICTION/
├── app.py
├── soil nutrition.ipynb · Fertilizer.ipynb
├── Soil Nutrients.csv · Fertilizer Prediction.csv
├── models/ (model.pkl, model1.pkl)
├── encoders/ (le_*.pkl)
├── instance/users.db
└── templates/ (home, nutrition, fertilizer, history, login, register)
```

## 🚀 Getting Started

```bash
git clone https://github.com/PreciousBharath/SOIL-NUTRITION-PREDICTION.git
cd SOIL-NUTRITION-PREDICTION
pip install flask flask-sqlalchemy pandas numpy scikit-learn
python app.py
```

## 🤝 Contributing

Contributions, issues and feature requests are welcome! Feel free to ⭐ star the repo and open a pull request.

## 👨‍💻 Author

<div align="center">

**Bharath** — Software Developer · Project Engineer · Technical Trainer

<a href="https://github.com/PreciousBharath"><img src="https://img.shields.io/badge/GitHub-PreciousBharath-181717?style=for-the-badge&logo=github"/></a>
<a href="https://linkedin.com/in/connectbharath"><img src="https://img.shields.io/badge/LinkedIn-connectbharath-0A66C2?style=for-the-badge&logo=linkedin"/></a>

### 🍔 EAT · 💻 CODE · 😴 SLEEP · 🔁 REPEAT

⭐ **If you found this project useful, give it a star!** ⭐

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

</div>
