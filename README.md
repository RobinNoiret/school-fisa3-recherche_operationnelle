# Projet RO - Optimisation de Tournées

## Objectif

Résoudre un **problème de tournée de véhicules** (TSP/VRP) pour minimiser les coûts de livraison.

**Contraintes additionnelles**:
1. Restrictions d'arêtes : certaines routes peuvent être coûteuses ou interdites
2. Dépendances de visite : une livraison doit précéder une collecte

## Structure du Projet

```
/
├── README.md
├── requirement.txt
│
├── livrables/
│   ├── 01_modélisation.ipynb
│   ├── 02_algorithmes.ipynb
│   └── 03_expériences.ipynb
│
├── docs/
│
└── data/
    └── results/
```

## Installation

```bash
pip install -r requirement.txt
jupyter notebook
```
