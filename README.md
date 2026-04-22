# TP1 SMA - Ingénierie des Prompts pour les Systèmes Multi-Agents

## Description

Ce dépôt contient le Travail Pratique 1 (TP1) du cours de Systèmes Multi-Agents (SMA), intitulé "Ingénierie des Prompts pour les Systèmes Multi-Agents". Ce projet explore l'application de l'ingénierie des prompts dans le contexte des systèmes multi-agents, en utilisant des technologies d'IA telles que LangChain, OpenAI et d'autres bibliothèques pour analyser et expérimenter avec des prompts efficaces.

## Contenu du Projet

- `main.py` : Script principal en Python pour l'exécution des tâches principales.
- `pyproject.toml` : Fichier de configuration du projet Python, incluant les dépendances.
- `TP1 SMA- Prompt Engineering For Multi Agent Systems (1).ipynb` : Notebook Jupyter contenant les analyses, expérimentations et démonstrations interactives.

## Installation

1. **Clonez le dépôt** :
   ```bash
   git clone https://github.com/votre-utilisateur/nom-du-repo.git
   cd nom-du-repo
   ```

2. **Installez les dépendances** :
   Assurez-vous d'avoir Python 3.11 ou supérieur installé. Utilisez pip pour installer les dépendances :
   ```bash
   pip install .
   ```
   Ou directement depuis pyproject.toml :
   ```bash
   pip install -e .
   ```

   Les dépendances principales incluent :
   - LangChain pour la gestion des chaînes de prompts
   - OpenAI pour l'accès aux modèles d'IA
   - Pandas et NumPy pour l'analyse de données
   - Matplotlib pour la visualisation
   - Et d'autres bibliothèques comme scikit-learn, tiktoken, etc.

## Utilisation

- **Exécution du script principal** :
  ```bash
  python main.py
  ```

- **Exploration du notebook** :
  Lancez Jupyter Notebook et ouvrez le fichier `.ipynb` :
  ```bash
  jupyter notebook "TP1 SMA- Prompt Engineering For Multi Agent Systems (1).ipynb"
  ```
  Suivez les cellules pour reproduire les expérimentations.

## Prérequis

- Python >= 3.11
- Jupyter Notebook ou JupyterLab
- Clé API OpenAI (si nécessaire pour certains tests)
- Environnement virtuel recommandé (venv ou conda)

## Structure du Projet

```
.
├── main.py                 # Script d'exécution principal
├── pyproject.toml          # Configuration et dépendances
├── README.md               # Ce fichier
└── TP1 SMA- Prompt Engineering For Multi Agent Systems (1).ipynb  # Notebook d'analyse
```

## Auteur

[Votre Nom] - Étudiant en Systèmes Multi-Agents  
Contact : [votre.email@example.com]

## Licence

Ce projet est distribué sous la licence MIT. Voir le fichier `LICENSE` pour plus de détails (si applicable).

## Remarques

Ce TP fait partie du cursus académique et est destiné à des fins éducatives. Assurez-vous de respecter les politiques d'utilisation des API externes (comme OpenAI) lors de vos expérimentations.
