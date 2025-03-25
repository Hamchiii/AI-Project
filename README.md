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

### Lab 3 – Multi-Agent Search

**Objectifs :**
- Développer des agents pour prendre des décisions dans un environnement multi‑agent.
- Implémenter et comparer plusieurs algorithmes adversariaux.
- Tester les agents sur des scénarios classiques (smallClassic, etc.) en évaluant leur capacité à maximiser le score et à éviter les fantômes.

**Fichiers clés :**
- `multiAgents.py` : Contient l’implémentation des agents (Reflex, Minimax, Alpha‑Beta, Expectimax).
- `multiagentTestClasses.py` : Fournit le framework de test et d’évaluation des agents.
- `AI_lab3_…pdf` : Énoncé détaillé des consignes et critères d’évaluation du TP3.

**Exemples d’exécution :**
```bash
python pacman.py -p ReflexAgent -l smallClassic
python pacman.py -p MinimaxAgent -l smallClassic -a depth=2
python pacman.py -p AlphaBetaAgent -l smallClassic -a depth=2
python pacman.py -p ExpectimaxAgent -l smallClassic -a depth=2

### Lab 3 – Multi-Agent Search
