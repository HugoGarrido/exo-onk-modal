## Exo Ornikar : Intégration d'une modal

### ⏱ Durée

45 minutes d'exercice + 15 minutes de discussion

### 🎯 Objectif

L'objectif de cet exercice est d'intégrer une modal pour une librairie de composants, puis d'en discuter.<br/>
Ce composant devra être suffisament flexible et responsive pour respecter la spec designs et reprendre le maximum d'éléments de la liste de features dessous.<br/>
<br/>
Tu seras autonome, mais n'hésite pas à poser des questions au besoin pendant toute la durée de l'exercice !
Aussi n'hésite pas à chercher au besoin ce dont tu as besoin sur internet (dans l'idéal, garde tes onglets de recherches ouverts 👀)

### ✨ Features

Voici la liste des features à ajouter à la modal. Il n'y a pas de minimum attendu, le but est d'avoir quelque chose à montrer à la fin de l'exercice et d'en discuter.

#### Principales

- Intégration mobile
- Header et footer optionnels
- Stickyness des header et du footer en mobile
- Gestion du scroll et overflow dans la modal
- Affichage et disparition de la modal

#### Bonus

- Intégration desktop
- Disparition de la modal au "click en dehors"
- Disparition de la modal au clavier sur la touche Echap
- Animation de l'entrée/sortie de la modal

_NB: Sauf composant déjà fait, on peut ajouter toutes librairies qu'on jugera utile._

### 👩‍🎨 Design

[Lien vers le design](https://www.figma.com/file/S9j3lzxmLImOp0R8RHX0pt/02---Kitt---Components?node-id=413%3A3)

_NB: Il faut se faire un compte Invision pour pouvoir inspecter le projet_

### 🏯 Structure du Projet

```
exo-modal
├── .storybook
└── src
    ├── composants
    │ └── Modal                   - ✍️ Composant à implémenter
    │   ├── index.js
    │   ├── stories.js
    │ └── ModalLaucher            - 🔘 Composant de test qui va toggler la Modal
    │   ├── index.js
    │   ├── stories.js
    ├── App.tsx
    └── index.tsx
```

### 🤖 Commande

`yarn storybook`: start Storybook

### 📱 Breakpoints

`small : min-width: 480px;`<br/>
`medium : min-width: 768px;`<br/>
`large : min-width: 1024px;`<br/>
`wide : min-width: 1280px;`<br/>
