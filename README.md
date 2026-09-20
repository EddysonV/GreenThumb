<div align="center">

# 🌿 GreenThumb

### Système intelligent de recommandation de plantes pour l’e-commerce

**Le bon végétal, pour chaque client.**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-FF6F00?style=for-the-badge)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)

</div>

---

## Présentation

GreenThumb est mon projet principal réalisé dans le cadre du **Bootcamp Data Analytics du Wagon**, d’avril à juin 2026.

Le projet propose un système de recommandation capable de suggérer des plantes adaptées au profil de chaque client : préférences, environnement, luminosité, niveau d’entretien, budget et historique d’achat.

> Ce dépôt présente une **proposition de pilote Data & Machine Learning**. Il ne s’agit pas d’un produit actuellement déployé en entreprise.

## Problème métier

Face à un catalogue e-commerce, choisir une plante adaptée peut être complexe. Une recommandation pertinente doit tenir compte à la fois :

- des besoins et préférences du client ;
- des caractéristiques des végétaux ;
- des comportements et achats précédents ;
- du contexte réel : espace, luminosité, entretien et budget.

## Solution proposée

GreenThumb repose sur une architecture légère et responsable :

1. **Préparation et structuration des données**
2. **Moteur hybride de recommandation**
3. **API FastAPI** pour servir les résultats
4. **Expérimentation A/B** pour mesurer l’impact
5. **Monitoring** des performances et de la qualité

Chaque recommandation est accompagnée d’éléments explicatifs pour aider le client à comprendre le choix proposé.

## Architecture

```text
Données clients + Catalogue + Interactions
                  │
                  ▼
       Nettoyage et préparation
                  │
                  ▼
   Moteur hybride de recommandation
                  │
                  ▼
             API FastAPI
                  │
                  ▼
       Site ou application e-commerce
```

## Technologies

- **Python** et **Pandas** pour la préparation et l’analyse
- **SQL** et **BigQuery** pour l’exploitation des données
- **Machine Learning** pour le moteur de recommandation
- **FastAPI** pour l’exposition du modèle
- **Power BI** pour le suivi des indicateurs
- **Git** pour le versionnement

## Objectifs du pilote

| Indicateur | Cible |
|---|---:|
| Conversion | +5 % |
| Panier moyen | +8 % |
| Latence de recommandation | < 250 ms |
| Blocage RGPD | 0 |

## Approche responsable

Le projet intègre dès sa conception :

- la qualité et la traçabilité des données ;
- le respect du RGPD ;
- l’analyse des biais ;
- l’explicabilité des recommandations ;
- le monitoring du modèle et des performances.

## Données étudiées

Le cas d’usage repose sur un jeu de données e-commerce comprenant notamment :

- plus de **951 000 commandes** ;
- **4 075 clients** ;
- **25 produits** ;
- plus de **485 000 avis et notes**.

---

<div align="center">

Projet Data & Machine Learning réalisé par **Eddyson Volcimé**  
Bootcamp Data Analytics — Le Wagon · 2026

</div>
