# 🍔 Challenge Menu Hamburger

> 📌 **Projet pédagogique** réalisé dans le cadre de la préparation au **Titre Professionnel Développeur Web & Web Mobile (TP DWWM)**.  
> Objectif : concevoir un **menu hamburger responsive 100% CSS/SCSS** (sans JavaScript) avec animations.

---

## 🎯 Objectifs pédagogiques
- Mettre en œuvre un **toggle de navigation** accessible via la technique *checkbox + label* (dit “checkbox hack”).  
- Animer l’icône hamburger avec des **@keyframes** (transformation “burger → cornet de frites” / retour).  
- Gérer l’**ouverture/fermeture** du panneau de navigation par **animations CSS**.  
- Structurer et factoriser les styles avec **SCSS** (variables, partials, imports).  
- Rendre l’interface **responsive** (breakpoints à 600px et 1024px).

---

## ✨ Fonctionnalités
- **Icône interactive** composée de 8 `span` stylisés/animés (pain, tomate, fromage, steak, salade…).  
- **Ouverture/Fermeture** de la *side‑nav* par changement d’état de la checkbox (`:checked`) → animations `ouvrir-navigation` / `fermer-navigation` + fondu d’opacité.  
- **Layout responsive** :  
  - `≥ 600px` : ajustements de la taille de l’icône et de la typo.  
  - `≥ 1024px` : agrandissement du toggle, grille de sections 2×2 dans `<main>`.  
- **Sans JS** : navigation et animations entièrement pilotées par CSS.
  
> Bonus UI fun : l’icône “hamburger” **se transforme en cornet + frites** lors de l’ouverture, puis **redevient un burger** à la fermeture (animations `transformation-cornet`, `rotation-frite1/2`, `retour-frite1/2`, `transformation-burger`).

---

## 🗂 Arborescence
```
/
├─ index.html
├─ css/
│  ├─ main.css
│  └─ main.css.map
└─ scss/
   ├─ _reset.scss
   ├─ _variables.scss
   ├─ _base.scss
   ├─ _toggle.scss
   ├─ _nav.scss
   ├─ _section.scss
   └─ main.scss
```

---

## 🛠 Stack & outils
- **HTML5** sémantique (header, nav, main, section, footer).  
- **CSS3 / SCSS** (partials, variables, media queries, animations, `clip-path`).  



## 📱 Responsive & comportements
- **Header** fixé en haut (`position: fixed; height: 15vh`).  
- **Nav** latérale fixe (`left: 0; top: 15vh; bottom: 0; width: 40%`) masquée/affichée par animation de `max-height` + opacité.  
- **Main** en colonne (mobile) → **grid 2×2** à `≥ 1024px`.  
- **Typo / tailles** adaptées dès `≥ 600px`.

---


## 👩‍💻 Auteur
**Elodie Gateau**  
- LinkedIn : https://www.linkedin.com/in/elodiegateau/  
- GitHub : https://github.com/Elodie-Gateau

---

## 📄 Licence
Projet d’apprentissage — usage **pédagogique** dans le cadre du **Titre Professionnel DWWM**.
