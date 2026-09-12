# 🎂 Pâtisserie Fares - Guide Complet

## 📋 Table des Matières
1. [Vue d'ensemble](#vue-densemble)
2. [Structure du site](#structure-du-site)
3. [Pages disponibles](#pages-disponibles)
4. [Installation et déploiement](#installation-et-déploiement)
5. [Personnalisation](#personnalisation)
6. [Maintenance](#maintenance)

---

## 🎯 Vue d'Ensemble

**Pâtisserie Fares** est un site web professionnel pour une pâtisserie artisanale avec :
- ✨ Design moderne et élégant (thème rose & or)
- 📱 Responsive (mobile, tablette, desktop)
- 🔍 Optimisé pour le SEO
- 📊 Intégration Google Analytics
- 📋 Système de réservation en ligne
- 📝 Blog avec articles
- 🎨 Galerie complète avec filtrage
- 📞 Formulaire de contact

---

## 📁 Structure du Site

```
patisserie-site/
├── index.html              # Page d'accueil
├── menu.html               # Catalogue des produits
├── galerie.html            # Galerie complète avec filtrage
├── blog.html               # Articles et conseils
├── reservation.html        # Formulaire de réservation
├── styles.css              # Styles globaux
├── script.js               # Fonctionnalités JavaScript
├── README.md               # Documentation
├── GOOGLE_ANALYTICS_SETUP.md # Guide Google Analytics
└── IMPROVEMENTS.md         # Améliorations apportées
```

---

## 📄 Pages Disponibles

### 1. **Index.html** - Accueil
- Section héro avec call-to-action
- Présentation de l'entreprise
- Mini galerie avec 6 créations
- Services proposés
- Horaires d'ouverture
- Témoignages clients
- Formulaire de contact

**Accès direct** : `https://votresite.com/`

### 2. **Menu.html** - Catalogue
- 6 catégories de produits
- Prix détaillés
- Descriptions complètes
- Estimation des prix
- Conditions de réservation

**Accès direct** : `https://votresite.com/menu.html`

### 3. **Galerie.html** - Galerie Complète
- 12 créations pâtissières
- Filtrage par catégorie :
  - Tous
  - Mariages
  - Anniversaires
  - Créations Spéciales
  - Plateaux
- Prix et descriptions
- Boutons "Commander"

**Accès direct** : `https://votresite.com/galerie.html`

### 4. **Blog.html** - Articles
- 6 articles de conseils
- Images associées
- Dates de publication
- Auteur (Chef Fares)
- Design attractif
- Potentiel SEO élevé

**Accès direct** : `https://votresite.com/blog.html`

### 5. **Reservation.html** - Réservation en Ligne
- Formulaire complet en 4 sections
- Calcul automatique du prix
- Options personnalisées
- Validation en temps réel
- Message de confirmation

**Accès direct** : `https://votresite.com/reservation.html`

---

## 🚀 Installation et Déploiement

### Option 1 : GitHub Pages (RECOMMANDÉ - GRATUIT)

#### Étape 1 : Activer GitHub Pages
1. Allez sur votre repo : https://github.com/sadisaid422-design/patisserie-site
2. Cliquez sur **Settings**
3. Sélectionnez **Pages** dans le menu de gauche
4. Sous "Source", choisissez **main** branch
5. Cliquez sur **Save**

#### Étape 2 : Accéder au site
✅ Votre site est en ligne à :
```
https://sadisaid422-design.github.io/patisserie-site/
```

### Option 2 : Netlify (GRATUIT + Domaine personnalisé)

1. Allez sur [netlify.com](https://netlify.com)
2. Connectez votre compte GitHub
3. Sélectionnez le repo `patisserie-site`
4. Laissez les paramètres par défaut
5. Cliquez sur **Deploy**

### Option 3 : Domaine Personnalisé

Pour utiliser `patisseriefare.ma` ou un domaine personnalisé :
1. Achetez un domaine (Namecheap, GoDaddy, etc.)
2. Configurez les DNS vers GitHub Pages ou Netlify
3. Suivez les instructions du registraire

---

## 🎨 Personnalisation

### Modifier les Couleurs

Ouvrez `styles.css` et modifiez :
```css
:root {
    --primary-color: #FF1493;      /* Rose - Modifier ici */
    --secondary-color: #FFD700;    /* Or - Modifier ici */
    --accent-color: #FF69B4;       /* Rose clair - Modifier ici */
}
```

### Modifier le Contenu

**Titre du site** : Trouvez et modifiez "Pâtisserie Fares" dans chaque fichier HTML

**Téléphone** : Cherchez "0559461051" et remplacez par votre numéro

**Adresse** : Remplacez "JX6Q+2PV, Maatkas" par votre adresse

**Horaires** : Modifiez "8h00 - 17h00" selon vos horaires réels

### Remplacer les Images

Actuellement, le site utilise des images placeholder (via.placeholder.com).

**Pour utiliser vos vraies images :**
1. Téléchargez vos photos dans le repo
2. Remplacez les URLs :
   ```html
   <!-- Avant -->
   <img src="https://via.placeholder.com/300x300/FF1493/FFB6C1?text=Gâteau+Rose" alt="Gâteau rose">
   
   <!-- Après -->
   <img src="images/gateau-rose.jpg" alt="Gâteau rose">
   ```

---

## 📊 Intégration Google Analytics

### Configuration Initiale
1. Créez un compte Google Analytics 4 : https://analytics.google.com
2. Obtenez votre ID (format : G-XXXXXXXXXX)
3. Remplacez `G-XXXXXXXXXX` dans chaque fichier HTML par votre ID réel
4. Consultez `GOOGLE_ANALYTICS_SETUP.md` pour plus de détails

### Suivre les Réservations
Les événements suivants sont automatiquement suivis :
- Clics sur "Réserver"
- Envois de formulaires
- Temps passé sur chaque page
- Source du traffic

---

## 🔧 Maintenance

### Mises à Jour Régulières
- **Galerie** : Ajoutez de nouvelles photos chaque mois
- **Blog** : Publiez 2-3 articles par mois
- **Menu** : Mettez à jour les prix si nécessaire
- **Témoignages** : Ajoutez les avis récents

### Optimisation SEO
1. Utilisez des descriptions détaillées pour chaque photo
2. Ajoutez des meta descriptions
3. Incluez des mots-clés pertinents
4. Publiez régulièrement sur le blog

### Sécurité
- Gardez vos dépendances à jour
- Ne stockez jamais de données sensibles dans le code
- Utilisez HTTPS (automatique avec GitHub Pages)

---

## 📱 Fonctionnalités Avancées

### Formulaire de Réservation
- Calcul automatique du prix
- Validation des champs
- Estimation en temps réel
- Support de 4 options additionnelles

### Filtrage Galerie
- Filtrage en temps réel
- Animations fluides
- Responsive design
- 5 catégories disponibles

### Navigation Mobile
- Menu hamburger responsive
- Navigation fluide
- Compatible tous navigateurs

---

## 📞 Support et Aide

### Problèmes Courants

**Le site ne s'affiche pas correctement sur mobile :**
- Vérifiez que vous avez le tag `viewport` dans le `<head>`
- Testez dans Chrome DevTools (F12 → Responsive)

**Les images ne s'affichent pas :**
- Vérifiez les chemins des fichiers
- Assurez-vous que les fichiers sont uploadés dans le repo

**Le formulaire de contact ne fonctionne pas :**
- C'est normal, vous devez configurer un service backend (Formspree, Netlify Forms, etc.)

### Ressources Utiles
- [Documentation HTML](https://developer.mozilla.org/fr/docs/Web/HTML)
- [CSS Reference](https://developer.mozilla.org/fr/docs/Web/CSS)
- [JavaScript Guide](https://developer.mozilla.org/fr/docs/Web/JavaScript)
- [Google Analytics Docs](https://support.google.com/analytics)

---

## ✅ Checklist de Lancement

- [ ] Configuration Google Analytics
- [ ] Remplacer toutes les images placeholder
- [ ] Vérifier tous les liens
- [ ] Tester sur mobile et desktop
- [ ] Ajouter votre domaine personnalisé
- [ ] Configurer le formulaire de contact (Formspree/Netlify)
- [ ] Ajouter vos réseaux sociaux
- [ ] Vérifier le SEO
- [ ] Lancer le site !

---

**Créé avec ❤️ pour Pâtisserie Fares**
Dernière mise à jour : 12 Septembre 2024
