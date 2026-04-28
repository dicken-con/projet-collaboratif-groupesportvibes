# 🏆 Sport Vibe

> *Site web dédié à l'univers du sport — conçu avec passion, développé en équipe.*

---

## 👥 Équipe

| Nom | Rôle | GitHub | participation| 
|---|---|---|---|
| N'GOMA MABIALA RICKEN JAIBESS | Chef de Projet & QA | @dicken-con |validation qualite et index.html et readme.md|
| OUSMANE FALL| Développeur Back-End | @fallousmanenoreyni-debug | style.css et dossier image et apropos.html |
|SANGOULE GADJI | Développeur Front-End 1 | @samsoudinegadji-rgb |football.html et basketbal.html| 
| MARIEME DIOP | Développeur Front-End 2 | @mariame | natation.html et tennis.html |
| DJILY NDIAYE | Développeur Front-End 3| @Djilyndiaye |fitness.html et panier.html |

---

## Branches

| Branche | Rôle |
|---|---|
| `main` | Branche de production — contient le code final validé |
| `dev` | Branche de développement — tout le travail se fait ici |

> ⚠️ La branche `main` est vide pendant le développement. Elle ne reçoit du contenu qu'à la fin du projet via une fusion avec `dev`.

---
## 🔀Création du dépôt (Repository) par le QA
**.Cliquez sur le bouton "+" (en haut à droite) puis New repository.**

**.Repository name : Choisissez un nom court et clair.**

**.Public/Private : Choisissez la visibilité.**

**.Cochez Add a README file (utile pour initialiser le projet).**

**.Cliquez sur Create repository.**


## 🔀Ajout des collaborateurs
**.Allez dans l'onglet Settings (Paramètres) de votre dépôt.**

**.Allez dans l'onglet Settings (Paramètres) de votre dépôt et definir dev comme branch par defaut.**

**.Cliquez sur Collaborators dans le menu de gauche (section Access).**

**.Cliquez sur le bouton vert Add people.**

**.Saisissez le nom d'utilisateur ou l'e-mail de la personne.**

**.Cliquez sur Add [username] to this repository.il aura les droits d'écriture (Push) sur le projet toujours avec un pull request.**



## 🔀 Workflow Git

###  fork le repo 
decocher le bouton coupier seulement....

### 1. Cloner le repo pour tout les collaborateur
# ouvre le cmd
```bash
cd desktop
git clone https://github.com/ton username/projet-collaboratif-groupesportvibes.git
cd projet-collaboratif-groupesportvibes
```

### 2. Créer sa branche personnelle depuis `dev`
```bash
git branch -a ( * dev
  remotes/origin/HEAD -> origin/main
  remotes/origin/dev
  remotes/origin/main)
git branch 
git config --global user.name
git config --global user.email
git checkout -b feature/votre-nom
```

### 3. Envoyer son travail en un seul push
```bash
New-Item(ou touch ou ""> ) nom.html ou nom.css

seulement pour le dossier image --->  mkdir images -->git add images/ -->git commit -m "Ajout dossier images"--> git push origin feature/ousmane

code nom.html ou nom.css ( taper le code )
ouvrir le treminal dans vscode
cd C:\Users\bmd\OneDrive\Bureau\projet-collaboratif-groupesportvibes
git add nom.html ou nom.css
git commit -m "Description claire du fichier ajouté"
git push origin feature/votre-nom

```

### 4. Ouvrerture la fenetre
cliquer le bouton 
entre ton username github 
entre ton mot de passe 
---
# ✅ Après
### 4. Ouvrir une Pull Request
**. Cliquer sur le bandeau jaune qui apparaît automatiquement copare and pull request**
**. Remplir la Pull Request**
- **Titre** : nom du fichier ajouté ex: `Ajout index.html`
- **Description** : courte explication ex: `Page d'accueil créée et complète`
- Vérifier que c'est bien :base: dev ← compare: feature/votre-nom 
**. Cliquer "Create pull request"**

> ✅ La Pull Request est envoyée, Ricken reçoit une notification 🔔

### Côté Ricken (QA / Chef de projet)

**. Recevoir la notification**
- Par email 📧
- Sur GitHub 🔔 en haut à droite

**. Aller dans l'onglet Pull Requests**

**. Choisir une action**

| Action | Signification |
|---|---|
| ✅ **Merge pull request** | Travail validé, intégré dans `dev` |
| 💬 **Add a comment** | Demande de modification avant validation |
| ❌ **Close pull request** | Travail refusé |

---

### Résumé visuel
---

## ✅ Règles importantes

- ⚠️ **Ne jamais travailler  sur  main toujours sur dev**
- ✅ Chaque fichier doit être envoyé **en deux branch et en deux push** (pour avoir au moin de commi)
- ✅ Chaque collaborateur travaille sur **sa propre branche** `feature/votre-nom`
- ✅ Toute contribution passe par une **Pull Request vers `dev`**
- ✅ Seul **Ricken** valide et merge les Pull Requests
- ✅ La branche `main` ne reçoit du contenu qu'à la **fin du projet**
- ⚠️ **au minimum 2 commits pas collaborateur **
---

## 📁 Structure du projet

```
projet-collaboratif-groupesportvibes/

├── images/          ← Dossier contenant toutes les images du site
├── index.html
├── apropos.html
├── football.html
├── basketball.html
├── natation.html
├── tennis.html
├── fitness.html
├── panier.html
├── style.css
└── README.md
```

---

## 🚀 Phases du projet

### 🔵 Phase 1 — Préparation
- [ ✔ ] Définir les pages du site (Accueil, À propos, Contact, etc.)
- [ ✔ ] Choisir les couleurs et polices du site
- [ ✔ ] Réaliser la maquette (papier)
- [ ✔ ] Créer la structure des dossiers du projet

### 🟡 Phase 2 — Structure HTML
- [ ✔ ] Créer les fichiers `.html`
- [ ✔ ] Mettre en place le Header (logo + navigation)
- [ ✔ ] Développer la section Hero (bannière principale)
- [ ✔ ] Développer la section Services / Présentation
- [ ✔ ] Créer le Footer (section avec un script)

### 🟠 Phase 3 — Design CSS
- [ ✔ ] Mise en page générale (flexbox / grid)
- [ ✔ ] Style du Header et de la navigation
- [ ✔ ] Style des autres sections

### 🟢 Phase 4 — Finalisation
- [ ✔ ] Tester sur différents navigateurs
- [ ✔ ] Optimiser les images
- [ ✔ ] Vérifier les liens et le contenu
- [ ✔ ] Déployer le site (GitHub Pages)

---

## 🔁 Fusion finale dev → main

Quand tout le contenu de `dev` est validé et complet :

1. Ricken ouvre une **Pull Request** : `dev → main`
2. Il vérifie le contenu final
3. Il merge → **tout le contenu de `dev` arrive dans `main`** ✅
4. Le site est déployé sur **GitHub Pages** 🌐

---
## 📝 Mot du QA & Chef de Projet au PROFFESSEUR

Ce projet a été organisé et supervisé par **Ricken**, en tant que 
QA et Chef de Projet.

Chaque membre de l'équipe a reçu une partie du travail clairement 
définie selon son rôle. L'avancement de chaque collaborateur a été 
suivi, contrôlé et vérifié lors de nos sessions de rencontre en équipe.

Chaque contribution a été soumise via une **Pull Request** et validée 
personnellement avant d'être intégrée dans le projet, garantissant 
ainsi la qualité et la cohérence du travail fourni.

> *Projet développé avec rigueur et esprit d'équipe — Sport Vibe *
