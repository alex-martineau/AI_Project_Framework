# AI Project Framework

Un framework générique pour structurer des projets d’IA et de data science.  
Ce dépôt inclut une organisation type pour gérer les données, les notebooks, les modèles et la documentation.

## 🎯 Objectifs
- Fournir une base réutilisable pour tout projet de machine learning
- Faciliter la collaboration (code, notebooks, rapports)
- Mettre en place de bonnes pratiques (tests, modularité, séparation des données et du code)

## 📂 Structure
- `data/` : données brutes, traitées et externes
- `notebooks/` : notebooks d’exploration et de modélisation
- `src/` : code Python modulaire (prétraitement, features, modèles, visualisation)
- `scripts/` : pipeline principal d’exécution
- `tests/` : tests unitaires
- `reports/` : rapports et figures générés
- `docs/` : documentation du projet

## ⚙️ Installation
```bash
git clone https://github.com/alex-martineau/AI_Project_Framework.git
cd AI_Project_Framework
pip install -r requirements.txt
