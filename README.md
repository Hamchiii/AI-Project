# Projet IA – Lab 3 et Lab 4

Ce projet se compose de deux parties distinctes :

1. **Lab 3 – Multi-Agent Search**  
   Implémentation d’agents adversariaux pour le jeu Pac‑Man, comprenant :
   - ReflexAgent (agent réactif basé sur une fonction d’évaluation heuristique)
   - MinimaxAgent (recherche exhaustive par minimax)
   - AlphaBetaAgent (minimax avec élagage alpha‑beta)
   - ExpectimaxAgent (modélisation probabiliste des fantômes)

2. **Lab 4 – Reinforcement Learning**  
   Implémentation d’algorithmes d’apprentissage par renforcement pour optimiser la politique de Pac‑Man, comprenant :
   - ValueIterationAgent (planification par itération sur les valeurs d’états)
   - PacmanQAgent (Q‑Learning tabulaire)
   - ApproximateQAgent (Q‑Learning avec extraction de caractéristiques)
   - PacmanDeepQAgent (Deep Q‑Learning utilisant un réseau de neurones)

---

## Détails des laboratoires

### Lab 3 – Multi-Agent Search

**Objectifs :**
- Développer des agents pour prendre des décisions dans un environnement multi‑agent.
- Implémenter et comparer plusieurs algorithmes adversariaux.
- Tester les agents sur des scénarios classiques en évaluant leur capacité à maximiser le score et à éviter les fantômes.

**Fichiers clés :**
- `multiAgents.py` : Contient l’implémentation des agents (Reflex, Minimax, Alpha‑Beta, Expectimax).
- `multiagentTestClasses.py` : Fournit le framework de test et d’évaluation des agents.
- `AI_lab3_…pdf` : Énoncé détaillé des consignes et critères d’évaluation du TP3.

---

### Lab 4 – Reinforcement Learning

**Objectifs :**
- Utiliser des méthodes de planification et d’apprentissage par renforcement pour apprendre une politique optimale.
- Implémenter la Value Iteration pour calculer une politique par itération sur les valeurs d’états.
- Mettre en place plusieurs agents de Q‑Learning (tabulaire, approximatif et profond) pour comparer leurs performances.

**Fichiers clés :**
- `valueIterationAgents.py` : Implémentation de l’algorithme de Value Iteration.
- `deepQLearningAgents.py` : Implémentation d’un agent Deep Q‑Learning.
- `AI_lab4_…pdf` : Énoncé détaillé des consignes et des méthodes attendues pour le TP4.

---

## Structure du rendu

Le dossier final compressé doit contenir :
- **Scripts Python** : Tous les fichiers sources complétés (TP3 et TP4).
- **Documents d’énoncé** : Les fichiers PDF `AI_lab3_…pdf` et `AI_lab4_…pdf`.
- **README.md** : Ce document, décrivant les objectifs, la méthodologie, les instructions d’exécution et les résultats.
- **Éventuellement** : Des graphiques ou captures d’écran illustrant les performances des agents.

---

## Critères d’évaluation

- **Exactitude fonctionnelle** : Correctitude de l’implémentation des algorithmes et comportement optimal des agents.
- **Qualité du code** : Lisibilité, modularité et respect des consignes.
- **Performance empirique** : Scores obtenus, taux de victoire et temps de calcul.
- **Documentation** : Clarté du README et commentaires dans le code.

---

## Références

- Pacman AI Projects, UC Berkeley (http://ai.berkeley.edu)
- Documentation interne du projet
