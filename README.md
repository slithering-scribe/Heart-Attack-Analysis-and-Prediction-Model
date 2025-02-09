# Heart Attack Analysis and Prediction Model  
# Herzinfarkt-Analyse und Vorhersagemodell

---

## About Me / Über mich

**English:**  
Hi, I’m [@slithering-scribe](https://github.com/slithering-scribe)  
I’m interested in data science, predictive modeling, and enhancing healthcare through machine learning.  
I’m currently learning advanced techniques in health data analysis and model optimization.  
I’m looking to collaborate on projects related to health analytics, predictive modeling, and innovative healthcare solutions.  
**How to reach me:** [tamara.kachalla@outlook.com](mailto:tamara.kachalla@outlook.com)  
**Pronouns:** He/Him  
**Fun Fact:** The human heart beats around 100,000 times a day!

**Deutsch:**  
Hallo, ich bin [@slithering-scribe](https://github.com/slithering-scribe)  
Meine Interessen liegen in Data Science, prädiktivem Modellieren und der Verbesserung des Gesundheitswesens durch Machine Learning.  
Derzeit vertiefe ich mein Wissen in fortgeschrittenen Techniken der Gesundheitsdatenanalyse und Modelloptimierung.  
Ich suche nach Kooperationen in Projekten rund um Gesundheitsanalytik, prädiktive Modellierung und innovative Lösungen für Herausforderungen im Gesundheitswesen.  
**Kontakt:** [tamara.kachalla@outlook.com](mailto:tamara.kachalla@outlook.com)  
**Pronomen:** He/Him  
**Fun Fact:** Das menschliche Herz schlägt etwa 100.000 Mal pro Tag!

---

## Project Overview / Projektübersicht

**English:**  
Welcome to the Heart Attack Analysis and Prediction Model project! This project leverages advanced machine learning techniques to analyze and predict the likelihood of heart attacks. By identifying critical predictors and patterns, it aims to improve early detection and preventive care, aligning with EU healthcare innovation standards and data protection regulations (GDPR/DSGVO).

**Deutsch:**  
Willkommen beim Projekt „Herzinfarkt-Analyse und Vorhersagemodell“! Dieses Projekt nutzt fortschrittliche Machine-Learning-Methoden, um die Wahrscheinlichkeit von Herzinfarkten zu analysieren und vorherzusagen. Durch die Identifikation kritischer Einflussfaktoren und Muster soll die Früherkennung verbessert und präventive Maßnahmen unterstützt werden – stets unter Einhaltung der EU-Innovationsstandards im Gesundheitswesen sowie der Datenschutzbestimmungen (GDPR/DSGVO).

---

## Key Features / Hauptfunktionen

- **Data Analysis / Datenanalyse:**  
  Conduct comprehensive exploratory data analysis (EDA) to uncover risk factors and patterns.  
  Durchführung einer umfassenden explorativen Datenanalyse (EDA), um Risikofaktoren und Muster zu identifizieren.

- **Feature Engineering / Merkmal-Engineering:**  
  Develop new features to capture additional information and improve model accuracy.  
  Entwicklung neuer Merkmale, um zusätzliche Informationen zu erfassen und die Modellgenauigkeit zu verbessern.

- **Model Building / Modellaufbau:**  
  Implement machine learning models such as Logistic Regression, Random Forest, Support Vector Machine (SVM), and XGBoost.  
  Implementierung von Machine-Learning-Modellen wie Logistischer Regression, Random Forest, Support Vector Machine (SVM) und XGBoost.

- **Model Evaluation / Modellevaluierung:**  
  Evaluate models using metrics such as Accuracy, Precision, Recall, F1 Score, and ROC-AUC to select the best-performing model.  
  Bewertung der Modelle anhand von Metriken wie Genauigkeit, Präzision, Recall, F1-Score und ROC-AUC zur Auswahl des leistungsstärksten Modells.

- **Visualization / Visualisierung:**  
  Create clear visualizations to effectively interpret risk factors and model results.  
  Erstellung aussagekräftiger Visualisierungen zur effektiven Interpretation von Risikofaktoren und Modellergebnissen.

---

## Project Structure / Projektstruktur

```
heart-attack-analysis/
├── data/                 # Dataset and preprocessing scripts / Datensätze und Vorverarbeitungsskripte
├── notebooks/            # Jupyter notebooks for analysis and modeling / Jupyter Notebooks für Analyse und Modellierung
├── models/               # Trained models and related scripts / Gespeicherte Modelle und zugehörige Skripte
├── reports/              # Detailed reports on findings and model performance / Detaillierte Berichte zu Erkenntnissen und Modellleistung
├── visualizations/       # Visual assets and charts / Visualisierungen und Diagramme
├── requirements.txt      # Required Python packages / Erforderliche Python-Pakete
└── README.md             # Project documentation / Projektdokumentation
```

---

## How to Use / Anwendung

1. **Clone the Repository / Repository klonen:**

   ```bash
   git clone https://github.com/yourusername/heart-attack-analysis.git
   cd heart-attack-analysis
   ```

2. **Install Dependencies / Abhängigkeiten installieren:**

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Notebooks / Notebooks starten:**

   Open the notebooks in Jupyter and follow the step-by-step instructions for data analysis, model building, and evaluation.  
   Öffnen Sie die Jupyter Notebooks und folgen Sie den Schritt-für-Schritt-Anweisungen zur Datenanalyse, zum Modellaufbau und zur Evaluation.

---

## Contributions / Mitwirken

**English:**  
Contributions are welcome! If you have suggestions, improvements, or bug reports, please open an issue or submit a pull request. Let’s work together to make healthcare more predictive and proactive.

**Deutsch:**  
Beiträge sind willkommen! Wenn Sie Vorschläge, Verbesserungen oder Fehlerberichte haben, eröffnen Sie bitte ein Issue oder senden Sie einen Pull Request. Lassen Sie uns gemeinsam daran arbeiten, das Gesundheitswesen prädiktiver und proaktiver zu gestalten.

---

## License / Lizenz

This project is licensed under the MIT License.  
Dieses Projekt ist unter der MIT-Lizenz lizenziert.

---

## Final Note / Abschließende Hinweise

Here’s to predicting heart health with data science! 🚀❤️  
Auf eine datengestützte Zukunft in der Herzgesundheit! 🚀❤️

---

## Model Performance and Conclusion / Modellevaluation und Schlussfolgerung

### **Neural Network Model Performance / Leistung des neuronalen Netzes**

- **Accuracy / Genauigkeit:** 0.803

### **Summary of Model Performances / Zusammenfassung der Modellevaluation**

**Logistic Regression / Logistische Regression:**
- **Accuracy / Genauigkeit:** 0.754  
- **Best Parameters / Beste Parameter:** `{'C': 100, 'max_iter': 100, 'solver': 'newton-cg'}`  
- **Confusion Matrix / Konfusionsmatrix:**
  ```
  [[19  9]
   [ 6 27]]
  ```

**Random Forest:**
- **Accuracy / Genauigkeit:** 0.770  
- **Best Parameters / Beste Parameter:** `{'bootstrap': False, 'max_depth': 20, 'min_samples_leaf': 2, 'min_samples_split': 5, 'n_estimators': 200}`  
- **Confusion Matrix / Konfusionsmatrix:**
  ```
  [[19  9]
   [ 5 28]]
  ```

**Random Forest with Top Features / Random Forest mit Top-Merkmalen:**
- **Accuracy / Genauigkeit:** 0.738  
- **Confusion Matrix / Konfusionsmatrix:**
  ```
  [[21  7]
   [ 9 24]]
  ```

**Gradient Boosting:**
- **Accuracy / Genauigkeit:** 0.803  
- **Best Parameters / Beste Parameter:** `{'learning_rate': 0.01, 'max_depth': 4, 'min_samples_leaf': 1, 'min_samples_split': 2, 'n_estimators': 100}`  
- **Confusion Matrix / Konfusionsmatrix:**
  ```
  [[21  7]
   [ 5 28]]
  ```

**Voting Classifier:**
- **Accuracy / Genauigkeit:** 0.754  
- **Confusion Matrix / Konfusionsmatrix:**
  ```
  [[21  7]
   [ 8 25]]
  ```

**Support Vector Machine (SVM) / Support Vector Machine (SVM):**
- **Accuracy / Genauigkeit:** 0.754  
- **Confusion Matrix / Konfusionsmatrix:**
  ```
  [[21  7]
   [ 8 25]]
  ```

**Neural Network / Neuronales Netz:**
- **Accuracy / Genauigkeit:** 0.803

### **Conclusion / Schlussfolgerung:**

Among the models evaluated, both the **Gradient Boosting** model and the **Neural Network** achieved the highest accuracy of **0.803**. This suggests that these models are particularly effective for predicting heart attacks based on the current dataset. The performance of the **Voting Classifier** and **SVM** was comparable to **Logistic Regression**, while the **Random Forest** models also performed well, albeit slightly lower. Further fine-tuning and exploration of ensemble methods may lead to additional improvements in predictive performance.
