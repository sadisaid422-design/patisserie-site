# 🎂 Pâtisserie Fares - Site Web

Bienvenue sur le repository du site web de **Pâtisserie Fares**, votre destination pour des créations pâtissières artisanales d'exception !

## 📋 Table des matières

- [À propos](#à-propos)
- [Fonctionnalités](#fonctionnalités)
- [Installation locale](#installation-locale)
- [Déploiement](#déploiement)
- [Structure du projet](#structure-du-projet)
- [Contact](#contact)

## 🎯 À propos

**Pâtisserie Fares** est une pâtisserie artisanale spécialisée dans la création de gâteaux personnalisés et de desserts raffinés. Chaque création est élaborée avec les meilleurs ingrédients et décorée avec passion pour sublimer vos moments spéciaux.

### 📞 Informations de contact
- **Téléphone** : 0559461051
- **Adresse** : JX6Q+2PV, Maatkas
- **Horaires** : 8h00 - 17h00 (tous les jours)

## ✨ Fonctionnalités

✅ **Navigation intuitive** - Menu fluide et responsive
✅ **Galerie de créations** - Showcase de nos meilleures pâtisseries
✅ **Services détaillés** - Mariage, anniversaires, événements, desserts individuels
✅ **Formulaire de contact** - Prise de commande en ligne
✅ **Témoignages clients** - Avis et retours de nos clients
✅ **Design responsive** - Adapté à tous les appareils (mobile, tablette, desktop)
✅ **Animations fluides** - Effets visuels élégants
✅ **Mobile-first** - Optimisé pour les appareils mobiles

## 🚀 Installation locale

### Prérequis
- Un navigateur web moderne (Chrome, Firefox, Safari, Edge)
- Un serveur local (optionnel mais recommandé)

### Étapes

1. **Cloner le repository**
```bash
git clone https://github.com/sadisaid422-design/patisserie-site.git
cd patisserie-site
```

2. **Ouvrir le site localement**

**Méthode 1 : Avec Python (le plus simple)**
```bash
# Python 3
python -m http.server 8000

# Puis ouvrir : http://localhost:8000
```

**Méthode 2 : Avec Node.js**
```bash
npx http-server
```

**Méthode 3 : Double-clic**
- Ouvrez simplement `index.html` dans votre navigateur

## 📦 Déploiement

### Option 1 : GitHub Pages (Gratuit) ⭐ Recommandé

1. Allez dans les **Settings** de votre repository
2. Scroll jusqu'à **Pages**
3. Sélectionnez `main` comme branche source
4. Cliquez sur **Save**
5. Votre site sera disponible à : `https://sadisaid422-design.github.io/patisserie-site`

**C'est gratuit et automatique !**

### Option 2 : Netlify (Gratuit + Domaine custom)

1. Visitez [netlify.com](https://netlify.com)
2. Cliquez sur **"New site from Git"**
3. Connectez votre compte GitHub
4. Sélectionnez ce repository
5. Cliquez **Deploy**

### Option 3 : Vercel (Gratuit + Performance)

1. Visitez [vercel.com](https://vercel.com)
2. Cliquez sur **Import Project**
3. Importez ce repository GitHub
4. Cliquez **Deploy**

### Option 4 : Hébergement traditionnel (payant)

1. Téléchargez les fichiers
2. Uploadez via FTP chez votre hébergeur
3. Configurez votre domaine

## 📁 Structure du projet

```
patisserie-site/
├── index.html          # Page principale
├── styles.css          # Styles et design
├── script.js           # Fonctionnalités JavaScript
├── menu.html           # Page du menu (à créer)
├── galerie.html        # Page galerie complète (à créer)
├── contact.html        # Page de contact (à créer)
├── README.md           # Ce fichier
└── .gitignore          # Fichiers à ignorer
```

## 🎨 Personnalisation

### Modifier les informations de contact

Ouvrez `index.html` et cherchez la section **Contact** :

```html
<p>0559461051</p>
<p>JX6Q+2PV, Maatkas</p>
```

### Changer les couleurs

Ouvrez `styles.css` et modifiez les variables CSS :

```css
:root {
    --primary-color: #FF1493;      /* Rose vif */
    --secondary-color: #FFD700;    /* Or */
    --accent-color: #FF69B4;       /* Rose pastel */
}
```

### Ajouter vos photos

Remplacez les images placeholder par vos propres photos :
1. Créez un dossier `images/` à la racine
2. Ajoutez vos photos
3. Modifiez les `src` des images dans `index.html`

## 📝 Pages à ajouter

### Pages recommandées :
- [ ] `menu.html` - Catalogue complet avec prix
- [ ] `galerie.html` - Galerie complète avec descriptions
- [ ] `a-propos.html` - Historique et philosophie
- [ ] `blog.html` - Articles et conseils
- [ ] `commande.html` - Formulaire de commande avancé

## 🔧 Technologies utilisées

- **HTML5** - Structure sémantique
- **CSS3** - Design responsive et animations
- **JavaScript Vanilla** - Interactivité sans dépendances
- **Font Awesome** - Icônes
- **Google Fonts** - Typographie (optionnel)

## 📱 Responsive Design

Le site est optimisé pour :
- 📱 Mobiles (320px+)
- 📱 Tablettes (768px+)
- 💻 Ordinateurs (1200px+)

## 🎓 Conseils SEO

Pour améliorer votre visibilité Google :

1. Modifiez le `<title>` et les `<meta>` dans `index.html`
2. Ajouter des descriptions d'images avec `alt=""`
3. Créer un `sitemap.xml`
4. Soumettre à Google Search Console
5. Ajouter des mots-clés pertinents

## 🐛 Problèmes courants

### Le site ne s'affiche pas correctement
- Assurez-vous d'ouvrir via un serveur local (pas en double-cliquant)
- Vérifiez la console du navigateur (F12) pour les erreurs

### Les images ne s'affichent pas
- Vérifiez que le chemin des images est correct
- Utilisez des chemins relatifs : `images/photo.jpg`

### Le formulaire ne fonctionne pas
- Actuellement, le formulaire affiche juste un message de succès
- Pour l'envoyer par email, utilisez un service comme Formspree ou Netlify Forms

## 📞 Support et Contact

Pour toute question ou modification :
- 📧 Email : contact@patisseriefares.com
- ☎️ Tél : 0559461051
- 📍 Adresse : JX6Q+2PV, Maatkas

## 📄 Licence

Ce projet est sous licence MIT. Libre de modifier et d'utiliser.

## 🙏 Remerciements

Merci d'avoir choisi cette solution web pour votre pâtisserie !

---

**Dernière mise à jour** : 12 Septembre 2026

**Créé avec ❤️ pour Pâtisserie Fares**