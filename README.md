# 🎃 Site Web Halloween 2025

Un site web complet et interactif pour planifier une soirée d'Halloween avec une ambiance sombre et stylée.

## 🌟 Fonctionnalités

### ✨ Design & Interface
- **Thème Halloween sombre** avec couleurs orange, violet et rouge sang
- **Animations fluides** et effets visuels immersifs
- **Design responsive** adapté à tous les écrans
- **Polices Halloween** (Creepster, Creepy) pour une ambiance authentique

### 👻 Sections du Site
1. **En-tête** - Titre principal avec la date de la soirée
2. **Liste des invités** - 10 invités avec cartes interactives
3. **Budget & Repas** - Calculs automatiques du budget par personne
4. **Programme détaillé** - Timeline animée de la soirée
5. **Footer** - Message stylé de fin

### 🧮 Calculs Automatiques
- **Budget total** : 148€ (4 pizzas × 27€ + 40€ courses)
- **Budget par personne** : 14,80€ (calculé automatiquement)
- **Affichage dynamique** des montants avec animations

### 🎭 Programme de la Soirée
- **17h30** → Déguisement & Préparation 🎭
- **18h00** → Chasse aux bonbons 🍬
- **19h30** → Retour & Apéro 🍹
- **20h15** → Jeux & Détente 👻
- **21h00** → Repas 🍕
- **22h00** → Dessert & Jeux 🎲
- **23h30** → Film d'horreur 🎥

## 🚀 Installation & Utilisation

### Prérequis
- Navigateur web moderne (Chrome, Firefox, Safari, Edge)
- Aucune installation requise !

### Lancement
1. Clonez le dépôt :
```bash
git clone https://github.com/GaelDmps/halloween.git
```

2. Ouvrez le fichier `index.html` dans votre navigateur

3. Profitez de votre soirée Halloween ! 🎃

## 📁 Structure du Projet

```
halloween/
├── index.html          # Structure HTML principale
├── style.css           # Styles CSS avec thème Halloween
├── script.js           # Logique JavaScript et animations
└── README.md           # Documentation du projet
```

## 🎨 Technologies Utilisées

- **HTML5** - Structure sémantique
- **CSS3** - Animations, gradients, responsive design
- **JavaScript ES6+** - Calculs automatiques et interactions
- **Google Fonts** - Polices Halloween (Creepster, Creepy)

## 🌈 Couleurs du Thème

- **Orange principal** : `#ff6b00`
- **Violet accent** : `#7e3ff2`
- **Rouge sang** : `#d72638`
- **Fond sombre** : `#0a0a0a` à `#1a1a1a`

## ✨ Effets Visuels

- **Particules flottantes** en arrière-plan
- **Animations de gradient** sur l'en-tête
- **Effets de lueur** sur les éléments interactifs
- **Timeline animée** avec apparition progressive
- **Cartes d'invités** avec effets de survol
- **Compteurs animés** pour les montants

## 📱 Responsive Design

Le site s'adapte parfaitement à tous les écrans :
- **Desktop** - Affichage complet avec timeline centrée
- **Tablet** - Layout adapté avec grille flexible
- **Mobile** - Timeline verticale et cartes empilées

## 🎯 Personnalisation

### Modifier les invités
Éditez la section `.guests-grid` dans `index.html` :
```html
<div class="guest-card">Nouveau Nom</div>
```

### Ajuster le budget
Modifiez les valeurs dans `script.js` :
```javascript
const budgetData = {
    pizzas: { quantity: 4, pricePerUnit: 27 },
    courses: 40,
    totalGuests: 10
};
```

### Changer le programme
Éditez la section `.timeline` dans `index.html` :
```html
<div class="timeline-item">
    <div class="timeline-time">Nouvelle Heure</div>
    <div class="timeline-content">
        <span class="timeline-icon">🎃</span>
        <span class="timeline-text">Nouvelle Activité</span>
    </div>
</div>
```

## 🤝 Contribution

Les contributions sont les bienvenues ! N'hésitez pas à :
- Signaler des bugs
- Proposer de nouvelles fonctionnalités
- Améliorer le design
- Optimiser les performances

## 📄 Licence

Ce projet est sous licence MIT. Voir le fichier `LICENSE` pour plus de détails.

## 👨‍💻 Auteur

**Gaël** - [@GaelDmps](https://github.com/GaelDmps)

---

*Prépare-toi à trembler… mais avec style 💀*
