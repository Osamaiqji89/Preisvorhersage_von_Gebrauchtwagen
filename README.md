# 🚗 Preisvorhersage von Gebrauchtwagen mittels Machine Learning

**Semesterabschlussarbeit im Modul Machine Learning (SoSe2025)**  
**Autor:** Sultan  
**Matrikelnummer:** ********  
**Studiengang:** Angewandte Künstliche Intelligenz  
**Datum:** 1. August 2025

---

## 🌐 Online-Demo

Teste die Preisvorhersage direkt im Browser:  
[🔗 Streamlit App – Gebrauchtwagen Preisvorhersage](https://preisvorhersagevongebrauchtwagenapp-t2vd4b6uebqqhtw5chlpq3.streamlit.app/#gebrauchtwagen-preisvorhersage)

---

## 📚 Inhalt

- 🔬 **Vergleich von Regressionsmodellen:** Lineare Regression, Ridge, Lasso, Decision Tree, Random Forest, XGBoost
- 🛠️ **Feature Engineering:** Entwicklung neuer Merkmale (Fahrzeugalter, Laufleistung/Jahr, Power-Effizienz)
- 🧹 **Datenbereinigung:** Umgang mit Ausreißern, Duplikaten, fehlenden Werten
- 📊 **Explorative Datenanalyse:** Statistiken, Visualisierungen, Korrelationen
- 🤖 **Modelltraining und -bewertung:** R², RMSE, MAE, Cross-Validation
- 🕹️ **Interaktives Preisvorhersage-Tool:** Für beliebige Fahrzeugkonfigurationen
- 📝 **Ergebnisse und Diskussion:** Modellvergleich, Feature-Wichtigkeit, Limitationen, ethische Aspekte
- 🔁 **Reproduzierbarkeit:** Paketversionen, Random Seed, Systeminfos

---

## 📁 Projektstruktur

- `Preisvorhersage_Gebrauchtwagen.ipynb` – Haupt-Notebook mit allen Analyseschritten
- `Daten/` – Ordner mit allen verwendeten CSV-Datensätzen (je Automarke)
- `README.md` – Diese Datei

---

## ⚙️ Installation & Nutzung

1. **Python 3.10+** und **Jupyter Notebook** erforderlich.
2. Benötigte Pakete werden im Notebook automatisch installiert:
   ```
   pip install numpy==1.26.4 pandas==2.2.2 matplotlib==3.8.4 seaborn==0.13.2 scikit-learn==1.5.0 xgboost==2.0.3 ipywidgets==8.1.2 psutil==5.9.8 notebook==7.2.0 nbformat==5.10.4
   ```
3. Fahrzeugdaten als CSV in den Ordner `Daten/` legen (siehe Abschnitt Datenquellen).
4. Notebook in Jupyter öffnen und **alle Zellen nacheinander ausführen**.

---

## 📦 Datenquellen

- Die Fahrzeugdaten stammen aus öffentlich verfügbaren Datensätzen ([Kaggle: Used Cars Dataset](https://www.kaggle.com/datasets/adityadesai13/used-car-dataset-ford-and-mercedes)).
- Die Daten sind ausschließlich für Forschungs- und Bildungszwecke bestimmt.

---

## 🏆 Ergebnisse

- **Bestes Modell:** XGBoost (R² ≈ 0.95)
- **Wichtigste Einflussfaktoren:** Fahrzeugalter, Laufleistung, Motorgröße, Marke/Modell
- **95% der Vorhersagen** liegen innerhalb von ±4.200 £ des tatsächlichen Preises

---

## 🔁 Reproduzierbarkeit

- Globaler Random Seed (42)
- Paketversionen und Systeminfos werden im Notebook ausgegeben
- Alle Datenvorverarbeitungsschritte sind dokumentiert

---

## ⚖️ Lizenz & Ethik

- Nur für wissenschaftliche und nicht-kommerzielle Zwecke
- Keine personenbezogenen Daten enthalten
- Siehe Abschnitt "Limitationen und ethische Betrachtungen" im Notebook

---

**Fragen oder Feedback:** Bitte den Autor
