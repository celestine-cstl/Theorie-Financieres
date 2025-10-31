# Marchés Financiers - Labs 1 à 5
**Analyse de titres, construction de portefeuilles, optimisation moyenne–variance (Markowitz) et CAPM à partir de données Yahoo! Finance et FRED.**


![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge\&logo=python\&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge\&logo=pandas\&logoColor=white)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge\&logo=microsoft-excel\&logoColor=white)
![PowerPoint](https://img.shields.io/badge/PowerPoint-B7472A?style=for-the-badge\&logo=microsoft-powerpoint\&logoColor=white)

> Python/Pandas pour récupérer et préparer les données (CSV), Excel pour réaliser les calculs, les graphiques et l’optimisation avec le Solveur, et PowerPoint pour présenter les résultats de façon claire et synthétique.

<br>


## 🛠️ Compétences mobilisées 
- **Data finance** : collecte et préparation de séries Adj Close (mensuel), cohérence des périodes et des unités.
- **Statistiques de marché** : calcul de rendements, volatilité, annualisation, lecture du couple risque/rendement
- **Gestion de portefeuille** : diversification, lecture des corrélations, construction d’un portefeuille équipondéré
- **Optimisation** : usage du Solveur pour MVP, frontières efficientes, intégration de l’actif sans risque, identification du portefeuille tangent
- **Évaluation d’actifs (CAPM)** : rendements excédentaires, estimation bêta/alpha par régression, interprétation économique
- **Communication financière** : synthèses claires et visuelles en PowerPoint, focalisées sur décisions et insights

<br>

## 📑 Contenu par Lab

**Lab 1 - JPMorgan & régulateurs (SEC/FINRA/IOSCO)**
- **JPMorgan :**  Profil et secteur d’activité, revue des **statistiques clés**, analyse des principaux détenteurs, lecture des avis d’analystes et examen du bilan.
- **Régulateurs :** Présentation des missions de la **SEC**, de la **FINRA** et de l’**IOSCO**, avec un focus sur la protection des investisseurs et sur leur rôle dans la transparence et la confiance des marchés.

<br>

**Lab 2 - Meta Platforms, Inc. (META)**
- **Profil de l'entreprise**, calcul du rendement attendu sur 12 mois à partir des objectifs d'analystes , et évaluation d'une stratégie de détention sur 5 ans (valorisation et rendement total).
- **Analyse de Performance** : rendement moyen mensuel et l'écart-type (volatilité).
- **Rendement Réel :** Mise en perspective avec le taux nominal moyen des certificats de dépôt (CD) à un an et les anticipations d'inflation (MICH) pour calculer le taux de rendement réel attendu

<br>

**Lab 3 - Portefeuille 12 Actions Françaises : Construction, Rendement & Risque**
- **Construction du Portefeuille :** Sélection et pondération de 12 actions françaises pour constituer un portefeuille diversifié.
- **Mesures de Performance :** Calcul des rendements individuels des 12 actions, puis détermination du rendement moyen du portefeuille sur une période donnée.
- **Évaluation du Risque :** Calcul de la variance et de l'écart-type du portefeuille (volatilité), en tenant compte des corrélations entre les actions pour mesurer l'effet de la diversification.

<br>

**Lab 4 - Portefeuille 12 Actions Françaises : Modèle de Markowitz**
- **Portefeuille Équipondéré** : Calcul des rendements mensuels et détermination de la performance historique (rentabilité et écart-type annualisés) du portefeuille initial équipondéré.
- **Frontière Efficiente** : Utilisation de l'optimisation pour déterminer le Portefeuille de Volatilité Minimale et tracer la Frontière Efficiente des portefeuilles risqués, avec et sans ventes à découvert.
- **Portefeuille Tangent** : Intégration d'un actif sans risque pour tracer la Droite du Marché des Capitaux (CML) et identifier le Portefeuille Tangent (qui maximise le Ratio de Sharpe)

<br>

**Lab 5 - Modèle d'Évaluation des Actifs Financiers (MEDAF)**
- **Rendement & Risque :** Calcul des rendements mensuels (arithmétiques et géométriques) et annualisés des deux actifs.
- **Estimation du Bêta :** Réalisation d'une régression linéaire (MEDAF/CAPM) pour estimer le Bêta (risque systématique) de l'action Disney.
- **Analyse de l'Alpha :** Calcul de l'Alpha de Disney et interprétation de la performance ajustée au risque (surperformance ou sous-performance) de l'action par rapport au marché

