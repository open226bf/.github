# Guide de Contribution — OPEN226

Merci de votre intérêt pour OPEN226 ! Ce guide vous accompagne dans vos premiers pas.

---

## 🌱 Types de Contributions

Tout le monde peut contribuer, avec ou sans compétences en programmation :

- **Code** — nouvelles fonctionnalités, corrections de bugs, tests
- **Documentation** — rédaction, traduction, tutoriels
- **Design** — interfaces, visuels, supports de communication
- **Communauté** — ateliers, mentorat, organisation d'événements
- **Idées** — propositions de projets, retours d'expérience

---

## 🚀 Démarrer

### Prérequis

- Un compte [GitHub](https://github.com) (gratuit)
- [Git](https://git-scm.com) installé sur votre machine
- Un éditeur de code (VS Code recommandé)

### Première contribution

```bash
# 1. Forkez le dépôt via l'interface GitHub (bouton "Fork" en haut à droite)

# 2. Clonez votre fork
git clone https://github.com/VOTRE-NOM/nom-du-projet.git
cd nom-du-projet

# 3. Créez une branche descriptive
git checkout -b feat/ma-fonctionnalite
# ou
git checkout -b fix/correction-bug
# ou
git checkout -b docs/amelioration-doc

# 4. Faites vos modifications, puis committez
git add .
git commit -m "feat: description claire de ma modification"

# 5. Poussez et créez une Pull Request
git push origin feat/ma-fonctionnalite
```

> 💡 **Astuce :** Cherchez les issues marquées `good first issue` — elles sont faites pour les nouveaux contributeurs !

---

## 📝 Conventions

### Messages de commit

Nous utilisons le format [Conventional Commits](https://www.conventionalcommits.org/fr) :

| Préfixe | Usage |
|---------|-------|
| `feat:` | Nouvelle fonctionnalité |
| `fix:` | Correction de bug |
| `docs:` | Documentation |
| `style:` | Formatage du code |
| `test:` | Ajout de tests |
| `chore:` | Maintenance |

**Exemples :**
```
feat: ajouter la fonctionnalité de connexion utilisateur
fix: corriger le bug d'affichage sur mobile
docs: mettre à jour le guide d'installation
```

### Pull Requests

Une bonne PR doit :
- Avoir un titre clair et une description détaillée
- Résoudre une seule problématique à la fois
- Passer tous les tests existants
- Respecter les conventions de code

---

## 🏷️ Labels des Issues

| Label | Description |
|-------|-------------|
| `good first issue` | Idéal pour les débutants |
| `help wanted` | Besoin d'aide supplémentaire |
| `💡 idée-projet` | Proposition de nouveau projet |
| `bug` | Quelque chose ne fonctionne pas |
| `documentation` | Amélioration de la doc |
| `question` | Besoin de clarification |

---

## ❓ Des questions ?

- Ouvrez une [Discussion](https://github.com/open226bf/open226-community/discussions)
- Envoyez un email : **issadicko78@gmail.com**

Lisez aussi notre [Code de Conduite](CODE_OF_CONDUCT.md) avant de contribuer.
