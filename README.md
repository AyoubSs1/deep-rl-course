# 🤖 Deep Reinforcement Learning — Interactive Course

> **Cours interactif** sur les trois grandes familles du Deep Reinforcement Learning :  
> DQN · Policy Gradient · Actor-Critic  
> Construit comme une **single-page application** entièrement autonome.

---

## 🌐 Voir le cours en ligne

**→ [Ouvrir index.html](./index.html)** *(double-clic, aucun serveur requis)*

Ou via GitHub Pages : `https://<username>.github.io/<repo>/`

---

## 📚 Structure du cours (5 onglets)

| Onglet | Contenu |
|---|---|
| **Vue d'ensemble** | Le problème MDP commun, présentation des 3 approches |
| **01 · DQN** | Value-based, Replay Buffer, Target Network — démo interactive |
| **02 · Policy** | Policy Gradient, REINFORCE, distribution gaussienne — démo |
| **03 · Actor-Critic** | Architecture hybride, calcul de l'avantage — démo temps réel |
| **Comparaison** | Tableau comparatif + arbre de décision |

Chaque famille suit la même structure :  
**Comment ça marche** (étapes cliquables) → **Démo interactive** → **Quand l'utiliser** → **Algorithmes associés**

---

## 🛠️ Technique

- **Un seul fichier** : `index.html` — HTML + CSS + JavaScript intégrés
- **Aucune dépendance** : pas de framework, pas de npm, pas de build
- **Police externe** : Google Fonts (fallback automatique hors-ligne)
- **Compatibilité** : tous navigateurs modernes (Chrome, Firefox, Safari, Edge)

---

## 🚀 Déployer sur GitHub Pages

```bash
# 1. Créer le dépôt et pousser
git init
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/<username>/<repo>.git
git push -u origin main

# 2. Activer GitHub Pages
# Settings → Pages → Source : main / (root) → Save
```

Le site sera disponible à `https://<username>.github.io/<repo>/` en ~1 minute.

---

## 📖 Références

- Mnih et al. (2015) — *Human-level control through deep reinforcement learning* (DQN)
- Williams (1992) — *Simple statistical gradient-following algorithms* (REINFORCE)
- Mnih et al. (2016) — *Asynchronous methods for deep RL* (A3C/A2C)
- Sutton & Barto — *Reinforcement Learning: An Introduction* (2e éd.)

---

*Réalisé dans le cadre du cours Deep Reinforcement Learning.*
