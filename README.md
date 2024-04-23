# Breast-Cancer-Survival-Prediction-with-Machine-Learning.Mohsen.Sabziyan
**Breast Cancer Prediction**

**Projektname:** Breast Cancer Prediction

**Beschreibung:** Dieses Projekt zielt darauf ab, Brustkrebs mithilfe von maschinellem Lernen vorherzusagen. Es verwendet Daten aus einer realen Brustkrebsdatenbank, darunter Alter, Geschlecht, Proteinwerte, Tumor-Stadium und mehr, um Modelle zu trainieren und Vorhersagen zu treffen, ob eine Person an Brustkrebs erkrankt ist oder nicht. Das Projekt umfasst die Implementierung verschiedener Modelle für die Brustkrebsvorhersage.

**Below is the information of all columns in the dataset:**

- Patient_ID: ID des Patienten
- Age: Alter des Patienten
- Gender: Geschlecht des Patienten
- Protein1, Protein2, Protein3, Protein4: Expressionsebenen
- Tumor_Stage: Brustkrebsstadium des Patienten
- Histology: Infiltrierendes duktales Karzinom, Infiltrierendes lobuläres Karzinom, Schleimiges Karzinom
- ER status: Positiv/Negativ
- PR status: Positiv/Negativ
- HER2 status: Positiv/Negativ
- Surgery_type: Lumpektomie, Einfache Mastektomie, Modifizierte radikale Mastektomie, Andere
- DateofSurgery: Datum der Operation
- DateofLast_Visit: Datum des letzten Besuchs des Patienten
- Patient_Status: Lebendig/Verstorben

**Inhalt:**
- `Real Breast Cancer Data.csv`: Die Rohdatendatei, die Informationen über Brustkrebsfälle enthält.
- `breast_cancer_prediction.py`: Ein Python-Skript, das verschiedene Machine-Learning-Modelle trainiert und testet, um Brustkrebs vorherzusagen.
- `README.md`: Diese README-Datei, die eine Anleitung zur Verwendung des Projekts enthält.

Models
The script utilizes the following models:

- Support Vector Machine (SVM)
- Random Forest
- Gradient Boosting
- K-nearest Neighbors (KNN)
- Naive Bayes
- Decision Tree
- Logistic Regression

Das Skript trainiert verschiedene Modelle für die Brustkrebsvorhersage und bewertet ihre Leistung anhand eines Teils der Daten. Es gibt auch eine README-Datei, die die Verwendung des Projekts erklärt.

**Hinweise:**
- Dieses Projekt dient nur zu Demonstrationszwecken und kann für Bildungszwecke oder als Ausgangspunkt für die Entwicklung eigener Brustkrebsvorhersagemodelle verwendet werden.
