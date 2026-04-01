# Projet RO - Optimisation de Tournées

## Objectif

Résoudre un problème de tournée de véhicules (TSP/VRP) pour minimiser les coûts de livraison.

Contraintes additionnelles:
1. Restrictions d'arêtes : certaines routes peuvent être coûteuses ou interdites
2. Dépendances de visite : une livraison doit précéder une collecte

## Structure du Projet

```
RO-code_source/
├── README.md
├── requirement.txt
├── .gitignore
│
├── livrables/
│   └── G5-livrable.ipynb
│
├── code/
│   └── code.ipynb
│
├── data/
│   └── dataset.csv
│
└── docs/
    └── notes.md
```

## Installation

```bash
pip install -r requirement.txt
jupyter notebook
```
