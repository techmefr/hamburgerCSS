# Menu Hamburger CSS

Un menu hamburger responsive implémenté uniquement avec HTML et CSS, sans JavaScript.

## 📋 Description

Ce projet démontre comment créer un menu hamburger entièrement fonctionnel sans utiliser de JavaScript. Il utilise les sélecteurs CSS avancés et la technique du checkbox caché pour obtenir un comportement interactif.

Le menu s'affiche comme une barre de navigation traditionnelle sur les écrans larges et se transforme en menu hamburger sur les appareils mobiles.


## ✨ Caractéristiques

- **Aucun JavaScript nécessaire** - Fonctionne uniquement avec HTML et CSS
- **Responsive** - S'adapte aux différentes tailles d'écran
- **Toggle interactif** - Utilise un checkbox caché pour créer l'interaction
- **Design personnalisable** - Facile à adapter à différents styles
- **Léger** - Minimal et performant

## 🛠️ Technologies utilisées

- HTML5
- CSS3
- SVG pour le logo

## 💡 Comment ça marche

Le menu hamburger fonctionne grâce à:

1. Un `input` de type checkbox caché
2. Une étiquette `label` stylisée comme une icône de menu hamburger
3. Des sélecteurs CSS avancés pour afficher/masquer le menu lorsque la checkbox est cochée

```css
#menu-toggle:checked + .burger-menu ~ .menu-hidden {
    display: flex;
}
```

## 📱 Responsive design

- **Grand écran (>767px)**: Affiche une barre de navigation horizontale normale
- **Petit écran (≤767px)**: Affiche un menu hamburger qui, lorsqu'il est cliqué, révèle un menu vertical

## 🎨 Personnalisation

Pour modifier le style du menu:

- **Couleur de fond**: Modifiez `background-color: gold;` dans les styles pour `.menu-hidden` et `header`
- **Police et taille**: Ajustez les propriétés `font-size` et `font-weight` 
- **Espacement**: Modifiez les valeurs de `margin` et `padding`
- **Logo**: Remplacez le fichier SVG dans le dossier `src/images/`

## 📥 Installation

1. Clonez ce dépôt


2. Ouvrez `index.html` dans votre navigateur


## 🚀 Exemples d'utilisation

Ce menu peut être facilement intégré dans:
- Sites web personnels
- Blogs
- Landing pages
- Applications web responsives
- Projets d'apprentissage de CSS

## 📝 Licence

[MIT](https://choosealicense.com/licenses/mit/)


---

Créé par [Gaëtan Compigni](https://github.com/techmefr)
