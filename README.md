![Python](https://img.shields.io/badge/Python-3.10-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-orange)
# Analysez-les-ventes-d-une-librairie-avec-Python
Analysez les ventes d'une librairie avec  Python
⸻

📊 Analyse du comportement d’achat des clients

🧾 Description du projet

Ce projet vise à analyser le comportement d’achat des clients à partir de données transactionnelles afin d’identifier les facteurs influençant leurs habitudes de consommation.

À travers une approche statistique rigoureuse, nous cherchons à comprendre comment les caractéristiques des clients (âge, sexe) influencent :

* Le montant total des achats
* La fréquence d’achat
* Le panier moyen
* Le type de produits achetés

⸻

🔎 Contexte

Dans un contexte où la data joue un rôle clé dans la prise de décision, les entreprises ont besoin de mieux comprendre leurs clients afin d’optimiser leurs stratégies marketing et commerciales.

Les données utilisées dans ce projet proviennent d’un dataset contenant :

* Des informations clients (âge, sexe)
* Des données transactionnelles (prix, sessions)
* Des catégories de produits achetés

L’enjeu est de transformer ces données en insights exploitables.

⸻

🎯 Objectifs

L’objectif principal est d’identifier les relations entre les variables clients et leur comportement d’achat.

Questions clés :

* Le sexe influence-t-il la catégorie de produits achetée ?
* L’âge influence-t-il le montant total des achats ?
* L’âge a-t-il un impact sur la fréquence d’achat ?
* Le panier moyen varie-t-il selon l’âge ?
* Les différentes catégories attirent-elles des profils d’âge différents ?

⸻

🧪 Méthodologie

Nous avons appliqué plusieurs tests statistiques adaptés au type de variables :

1️⃣ Test du Chi²

* Analyse : Sexe ↔ Catégorie
* Objectif : Tester l’indépendance entre deux variables catégorielles

⸻

2️⃣ Corrélation (Pearson & Spearman)

* Analyse :
    * Âge ↔ Montant total
    * Âge ↔ Fréquence
    * Âge ↔ Panier moyen
* Objectif : Mesurer la relation entre variables quantitatives

⸻

3️⃣ ANOVA

* Analyse : Âge ↔ Catégorie
* Objectif : Comparer les moyennes d’âge entre plusieurs groupes

⸻

📊 Résultats principaux

🔹 Sexe vs Catégorie (Chi²)

* p-value très faible → relation statistiquement significative
* Cramer’s V très faible → relation très faible

👉 Conclusion :
Le sexe n’est pas un facteur déterminant dans le choix des produits.

⸻

🔹 Âge vs Montant total

* Corrélation négative faible

👉 Conclusion :
Les clients plus âgés dépensent légèrement moins au total.

⸻

🔹 Âge vs Fréquence

* Corrélation positive faible

👉 Conclusion :
Les clients plus âgés achètent légèrement plus souvent.

⸻

🔹 Âge vs Panier moyen

* Corrélation négative modérée à forte

👉 Conclusion :
Les jeunes dépensent plus par transaction.

⸻

🔹 Âge vs Catégorie (ANOVA)

* p-value = 0 → différence significative

👉 Conclusion :
Certaines catégories attirent des groupes d’âge spécifiques.

⸻

🧠 Insights clés

* L’âge est le facteur le plus influent dans le comportement d’achat
* Le sexe a un impact négligeable
* Les jeunes ont tendance à dépenser plus par achat
* Les clients plus âgés achètent plus souvent mais dépensent moins par panier

⸻

⚙️ Technologies utilisées

* Python
* Pandas
* NumPy
* Matplotlib / Seaborn
* SciPy (tests statistiques)

⸻

📈 Visualisations

Le projet inclut plusieurs visualisations :

* Graphiques en barres (répartition par sexe et catégorie)
* Scatter plots (relations entre variables quantitatives)
* Boxplots (comparaison des distributions)

⸻

📌 Conclusion

Ce projet démontre l’importance de combiner analyse exploratoire et tests statistiques pour tirer des conclusions fiables à partir des données.

L’utilisation de tests adaptés (Chi², corrélation, ANOVA) permet de :

* Valider les hypothèses
* Éviter les biais d’interprétation
* Produire des insights exploitables

⸻

🚀 Améliorations possibles

* Segmentation clients (clustering)
* Modèles prédictifs (machine learning)
* Analyse temporelle (évolution des achats)
* Ajout de variables comportementales

⸻

👤 Auteur

Projet réalisé dans le cadre d’une analyse de données clients.
