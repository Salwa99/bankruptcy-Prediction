# 🔍 BankruptcyPro - Prédiction de Faillite d'Entreprise

**BankruptcyPro** est une application Web interactive développée avec **Streamlit** permettant d’évaluer le **risque de faillite d’une entreprise** à partir de quatre indicateurs financiers clés. Elle intègre deux modèles d’apprentissage automatique : **Random Forest** et **XGBoost**.

---

## 🚀 Fonctionnalités

- 🔐 Interface de connexion sécurisée
- 📊 Saisie interactive des indicateurs financiers
- 🧠 Prédiction du risque de faillite avec Random Forest et XGBoost
- 📈 Statistiques de performance des modèles
- 📑 Documentation intégrée
- 📥 Export des rapports d’analyse
- 🎨 Design personnalisé avec CSS et animations Lottie

---

## 🛠️ Technologies utilisées

- **Frontend** : Streamlit, Plotly, Lottie
- **Backend** : Python
- **Machine Learning** : Scikit-learn, XGBoost
- **Modèles** :  
  - `random_forest_4_features.pkl`  
  - `xgboost_model.pkl`

---

## 📊 Indicateurs financiers utilisés

1. **Net Income to Total Assets**
2. **Net Worth / Assets**
3. **Persistent EPS (Earnings Per Share)**
4. **Retained Earnings / Total Assets**

---


---

## ▶️ Lancer l'application

1. **Cloner le projet** :

```bash
git clone https://github.com/Salwa99/bankruptcy-Prediction.git
cd bankruptcy-Prediction
```

2. **Créer un environnement virtuel :**

```bash
python -m venv venv
source venv/bin/activate  # ou venv\Scripts\activate sous Windows
```

3. **Installer les dépendances :** 

```bash
pip install -r requirements.txt
```

4. **Lancer l'application :** 
```bash
streamlit run app_streamlit_prediction_rf_xgb.py
```

### 📸 Aperçu

- Tableau de bord interactif avec indicateurs clés

- Visualisations personnalisées avec Plotly

- Prédiction et analyse explicative

- Statistiques comparatives entre modèles


## 👨‍💻 Développé par

- **Salwa Ballouti**


## 📄 Licence

Ce projet est distribué sous la licence MIT.
Vous êtes libre de l’utiliser, le modifier et le distribuer à condition de conserver les mentions de copyright et la licence.
