# Diar Salem – Guide d'ajout des photos

## 📂 Structure des fichiers

```
Diar Salem/
├── index.html          ← Le site web (fichier principal)
├── images/             ← Dossier pour vos photos
│   ├── hero.jpg                  ← Photo principale (héro)
│   ├── about.jpg                 ← Photo section À propos
│   │
│   ├── cinematic-exterior.jpg    ← Vue extérieure cinématique
│   ├── cinematic-pool.jpg        ← Vue piscine cinématique
│   ├── cinematic-interior.jpg    ← Vue intérieur cinématique
│   ├── cinematic-terrace.jpg     ← Vue terrasse cinématique
│   ├── cinematic-night.jpg       ← Vue panoramique / nuit
│   │
│   ├── villa-a.jpg               ← Photo villa type A
│   ├── villa-b.jpg               ← Photo villa type B
│   │
│   ├── feature-pool.jpg          ← Photo piscine (détail)
│   ├── feature-kitchen.jpg       ← Photo cuisine équipée
│   ├── feature-garage.jpg        ← Photo garage
│   ├── feature-ac.jpg            ← Photo climatisation
│   ├── feature-garden.jpg        ← Photo jardin
│   ├── feature-terrace.jpg       ← Photo terrasse
│   ├── feature-wifi.jpg          ← Photo Wi-Fi / tech
│   └── feature-security.jpg      ← Photo sécurité
└── README.md           ← Ce fichier
```

## 🖼️ Comment ajouter vos photos

Les emplacements pour les images sont déjà préparés dans `index.html` sous forme de commentaires HTML.

Pour chaque image, trouvez le commentaire correspondant dans le HTML et remplacez-le par une balise `<img>`.

**Exemple :** Pour la galerie extérieure, cherchez :
```html
<!-- <img src="images/cinematic-exterior.jpg" alt="Villa Exterior"> -->
```
Et remplacez par :
```html
<img src="images/cinematic-exterior.jpg" alt="Villa Exterior">
```

## 📱 Tailles recommandées

| Type de photo | Taille recommandée | Format |
|---|---|---|
| Hero (arrière-plan) | 1920 × 1080 px | JPG |
| Cinematic shots | 1200 × 900 px | JPG |
| Villa cards | 800 × 600 px | JPG |
| Feature cards | 600 × 400 px | JPG |

> Conseil : compressez vos images avec [TinyPNG](https://tinypng.com/) pour un chargement rapide.

## 📞 Mise à jour des contacts

Dans `index.html`, remplacez les valeurs suivantes par les vraies informations :

| Placeholder | Remplacer par |
|---|---|
| `216XXXXXXXX` | Numéro WhatsApp réel (ex: `21698123456`) |
| `contact@diarsalem.com` | Adresse email réelle |
| `diarsalem` | Nom de la page Facebook Messenger |

## 🗺️ Mise à jour de la carte

Pour pointer vers l'emplacement exact des villas :
1. Allez sur [Google Maps](https://www.google.com/maps)
2. Cherchez l'adresse exacte
3. Cliquez **Partager** → **Intégrer une carte**
4. Copiez l'URL du `src` de l'iframe
5. Remplacez l'URL dans la section `<!-- LOCATION SECTION -->` du fichier HTML
