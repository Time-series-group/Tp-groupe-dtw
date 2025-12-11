# Cahier de Suivi Individuel
## Projet DTW - Analyse des Passagers Aériens (1949-1960)

### 👤 Informations Personnelles
- **Nom** : ESSUTHI MABNGUE Ange Armel
- **ID** : 24F2456
- **Rôle** : Analyste Data Science
### Chronologie du projet
- **Période** : Du 9 au 11 Décembre 2025
- **Durée** : 3 jours de travail intensif
- **Date de rendu** : 11 Décembre 2025

### Dernière mise à jour
11 Décembre 2025

- **Dépôt** : https://github.com/Time-series-group/Tp-groupe-dtw

---

## Chronologie du Travail

### **Jour 1 : Initialisation**
- Configuration environnement Python
- Chargement données `air_passengers.csv`
- Visualisation série temporelle complète
- Décomposition statistique (tendance, saisonnalité, bruit)

### **Jour 2 : Préparation DTW**
- Extraction 12 séries annuelles (1949-1960)
- Normalisation min-max des données
- Tentative avec `fastdtw` (problème technique)
- Implémentation manuelle de l'algorithme DTW

### **Jour 3 : Analyse et Visualisation**
- Calcul matrice distances DTW (12×12)
- Identification similarités : 1956-1957 (0.266)
- Identification différences : 1951-1958 (1.565)
- Génération visualisations d'alignement
- Création synthèse finale

---

##  Contributions Techniques

###  **Code Développé**
1. **Pipeline analyse complète** : Chargement → Nettoyage → Analyse → Visualisation
2. **Fonction DTW manuelle** : Implémentation algorithme de programmation dynamique
3. **Visualisation alignement** : 4 graphiques pour comprendre le warping temporel
4. **Analyse automatique** : Calcul indicateurs et statistiques

###  **Visualisations Créées**
- 01_serie_temporelle_complete.png
- 02_decomposition_additive.png  
- 03_series_annuelles_normalisees.png
- 04_matrice_dtw.png
- 05_dtw_alignment_*.png (3 paires)
- 06_synthese_finale_dtw.png

###  **Résultats Obtenus**
- **Matrice DTW complète** : Distances entre toutes les paires d'années
- **Métriques** : Distance moyenne = 0.982 ± 0.312
- **Clustering naturel** : 1949-1952 (variable), 1953-1954 (transition), 1955-1960 (stable)
- **Évolution** : Similarité croissante après 1955

---

##  Compétences Appliquées

###  **Techniques**
- Analyse séries temporelles (tendance, saisonnalité)
- Implémentation algorithmes (DTW, normalisation)
- DataViz avec matplotlib (graphiques complexes)
- Manipulation données avec pandas/numpy

###  **Méthodologiques**
- Workflow projet data science complet
- Résolution problèmes techniques (debugging)
- Documentation code et résultats
- Gestion versions avec Git

###  **Personnelles**
- Autonomie dans la recherche solutions
- Rigueur analyse quantitative
- Créativité visualisations
- Persévérance face aux défis techniques

---

##  Défis et Solutions

### **Défi 1 : Problème fastdtw**
- **Problème** : Erreur "Input vector should be 1-D"
- **Solution** : Implémentation manuelle DTW
- **Résultat** : Contrôle total, pas de dépendance externe

### **Défi 2 : Visualisation claire**
- **Problème** : Comment montrer l'alignement DTW ?
- **Solution** : 4 subplots (séries, matrice, warping, aligné)
- **Résultat** : Visualisation pédagogique et complète

### **Défi 3 : Interprétation résultats**
- **Problème** : Expliquer matrice de distances
- **Solution** : Indicateurs + heatmap + analyse temporelle
- **Résultat** : Insights compréhensibles

---

##  Apprentissages

### **Techniques**
1. DTW mesure la similarité de **forme**, pas juste de valeur
2. Normalisation essentielle pour comparer séries
3. Visualisation multiple angles nécessaire pour DTW

### **Méthodologiques**
1. Documentation étape par étape cruciale
2. Sauvegarde systématique des visualisations
3. Validation visuelle + quantitative

### **Personnels**
1. Patience avec problèmes techniques
2. Organisation travail en phases claires
3. Communication résultats via visualisations

---

##  Réalisations

###  **Projet Complet A→Z**
- Données brutes → Insights actionnables
- 8 visualisations professionnelles
- Documentation technique complète

###  **Solution Technique Robustes**
- Implémentation DTW manuelle fonctionnelle
- Pipeline reproductible
- Code bien documenté

###  **Valeur Ajoutée**
- **Pédagogique** : Compréhension visuelle DTW
- **Technique** : Référence implémentation DTW
- **Pratique** : Workflow analyse séries temporelles

---

** Date de réalisation** : [Date]  
** Statut** : PROJET COMPLÉTÉ  
** Fichiers produits** : Notebook + 8 images + données + documentation  

*Projet réalisé individuellement. avec rigueur.*
