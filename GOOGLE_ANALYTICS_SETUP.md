# 📊 GUIDE GOOGLE ANALYTICS - Pâtisserie Fares

## Configuration Google Analytics 4 (GA4)

### Étape 1 : Créer un compte Google Analytics
1. Allez sur [Google Analytics](https://analytics.google.com)
2. Cliquez sur "Commencer à mesurer"
3. Créez un nouveau compte avec :
   - **Nom du compte** : Pâtisserie Fares
   - **Nom de la propriété** : Pâtisserie Fares Website

### Étape 2 : Obtenir votre ID Google Analytics
1. Une fois créé, vous recevrez un **ID de mesure** au format `G-XXXXXXXXXX`
2. Copiez cet ID

### Étape 3 : Intégrer dans votre site
1. Ouvrez le fichier `index.html`
2. Trouvez la ligne : `gtag('config', 'G-XXXXXXXXXX');`
3. Remplacez `G-XXXXXXXXXX` par votre ID réel
4. Répétez cette opération pour tous les fichiers HTML :
   - `index.html`
   - `menu.html`
   - `galerie.html`
   - `blog.html`
   - `reservation.html`

### Exemple :
```html
<script async src="https://www.googletagmanager.com/gtag/js?id=G-ABC123XYZ45"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'G-ABC123XYZ45');
</script>
```

## 📈 Métriques à Suivre

### Événements Importants
- **Page Views** : Nombre de visites sur chaque page
- **Click Events** : Clics sur "Réserver", "Commander", "Appeler"
- **Form Submissions** : Envois de formulaires de contact et réservation
- **Time on Page** : Temps passé sur chaque page

### Rapports Utiles
1. **Audience** : Démographie et localisation des visiteurs
2. **Acquisition** : D'où viennent vos visiteurs (Google, Facebook, etc.)
3. **Comportement** : Pages les plus consultées
4. **Conversions** : Réservations et demandes de contact

## 🔧 Dépannage

### Si les données ne s'affichent pas :
1. Vérifiez que l'ID GA4 est correct
2. Attendez 24-48h pour que les données commencent à apparaître
3. Utilisez l'outil [Google Tag Assistant](https://tagassistant.google.com) pour déboguer

### Si vous voyez "No data"
- C'est normal les 24 premières heures
- Assurez-vous que le script est présent dans le `<head>` du HTML
- Vérifiez la console du navigateur (F12 → Console) pour les erreurs

## 📱 Événements Personnalisés Recommandés

Vous pouvez ajouter ces événements pour un suivi plus détaillé :

```javascript
// Événement de clic sur réservation
document.querySelectorAll('a[href="reservation.html"]').forEach(link => {
  link.addEventListener('click', () => {
    gtag('event', 'reservation_click', {
      'event_category': 'engagement',
      'event_label': 'reservation_button'
    });
  });
});

// Événement d'envoi de formulaire
document.querySelector('.contact-form').addEventListener('submit', () => {
  gtag('event', 'form_submission', {
    'event_category': 'engagement',
    'event_label': 'contact_form'
  });
});
```

## 💡 Bonnes Pratiques

1. **Privacy** : Respectez le RGPD (ajoutez un consentement aux cookies)
2. **Anonymisation** : Anonymisez les adresses IP
3. **Exclusions** : Excluez votre propre traffic
4. **Révision régulière** : Consultez vos rapports GA4 chaque mois

---

**Questions ?** Consultez la [documentation officielle Google Analytics](https://support.google.com/analytics)
