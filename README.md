# Rainfall_prediction_Senegal
Prévision de la pluviométrie et recommandations agricoles avec Prophet.
# Introduction
Ce notebook présente une modélisation des précipitations avec Prophet, suivie de recommandations agricoles et d’irrigation. 
Il s’inscrit dans le cadre du projet Hack2Hire.

# Prévision des précipitations et recommandations agricoles

## Objectif
Prévoir les précipitations avec Prophet et générer des recommandations agricoles et d’irrigation dynamiques.

## Contexte
Données météorologiques du Sénégal, saison des pluies 2025. Ce projet vise à soutenir les décisions agricoles.

 ## Méthodologie
- Nettoyage des données
- Modélisation avec Prophet
- Génération de prévisions
- Recommandations d’irrigation
- Évaluation du modèle

 Résultats
**MAE**: **6.35** mm  
**RMSE**: **9.06** mm

 ## Comparaison avec Random Forest
| Modèle          | MAE (mm) | RMSE (mm) |
|----------------|----------|-----------|
| Prophet        | 6.35     | 9.06      |
| Random Forest  | 6.73     | 9.96      |

## Recommandations d’irrigation
- < 5 mm : irrigation nécessaire
- 5–25 mm : irrigation complémentaire
- > 25 mm : suspendre l’irrigation



## 📁 Fichiers2
- `Prédiction_pluviométie.ipynb` : Notebook complet
- `previsions.csv` : Prévisions Prophet
- `recommandations_irrigation.csv` : Conseils d’irrigation

##  Auteur
Fatou DIALLO  Ingénieure statisticienne économiste.  
 Basée à Dakar,   
 Passionnée par la data et l'IA.
