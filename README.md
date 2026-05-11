# 🌿 Business Bridge — Site Officiel

> **L'écosystème agricole africain de demain.**  
> Formation · Organisation · Production · Commerce · Exportation

---

## 🎯 Présentation

Site institutionnel premium de **Business Bridge**, une structure entrepreneuriale intégrée basée à Niamey, Niger, opérant à l'intersection de l'agriculture, de la formation et de la technologie.

Le site présente les trois composantes de l'écosystème :
- **EPPRIDAD** – École polytechnique privée pour le développement agricole durable
- **FERME.** – Hub agricole moderne de 8 hectares
- **KASSANMOU** – Marketplace digitale producteurs africains → marchés mondiaux

---

## 🛠️ Technologies

| Technologie | Usage |
|-------------|-------|
| HTML5 sémantique | Structure & SEO |
| Tailwind CSS (CDN) | Styles utilitaires |
| CSS3 custom | Variables, animations, design system |
| JavaScript vanilla | Interactions, scroll, compteurs |
| Google Fonts | Cormorant Garamond + Syne + DM Sans |

---

## 📁 Structure du projet

```
business-bridge/
├── index.html          # Page principale (single-page)
├── assets/
│   ├── hero-bg.jpg     # Image de fond hero (à ajouter)
│   ├── eppridad.jpg    # Image composante EPPRIDAD (à ajouter)
│   ├── ferme.jpg       # Image composante FERME (à ajouter)
│   ├── kassanmou.jpg   # Image composante KASSANMOU (à ajouter)
│   └── banituri.jpg    # Image client Banituri (à ajouter)
└── README.md
```

---

## 🎨 Design System

### Palette de couleurs

| Nom | Valeur | Usage |
|-----|--------|-------|
| Vert principal | `#1a5d1a` | Couleur primaire, boutons, accents |
| Vert foncé | `#0f3d0f` | Fonds sombres, navbar |
| Vert clair | `#2a7a2a` | Gradients, hover |
| Doré | `#d4af37` | Accents premium, séparateurs |
| Doré clair | `#e8c84a` | Highlights, hover |
| Blanc cassé | `#f9f7f2` | Fond principal |

### Typographies

- **Cormorant Garamond** — Titres display, citations (serif élégant)
- **Syne** — Labels, navigation, badges (sans-serif institutionnel)
- **DM Sans** — Corps de texte, descriptions (lisibilité optimale)

---

## 📐 Sections du site

1. **Hero** — Titre fort + CTA + barre de statistiques
2. **Qui sommes-nous** — Vision, mission, positionnement
3. **Nos Composantes** — EPPRIDAD, FERME., KASSANMOU
4. **Réalisations & Clients** — Banituri + système duplicable
5. **Notre Impact** — Chiffres animés + piliers
6. **Vision Africaine** — Roadmap Niger → Afrique → Monde
7. **Contact** — Coordonnées + formulaire
8. **Footer** — Navigation + réseaux sociaux + copyright

---

## 🚀 Déploiement GitHub Pages

```bash
# 1. Créer un repository GitHub
git init
git add .
git commit -m "feat: lancement site officiel Business Bridge"
git remote add origin https://github.com/VOTRE-ORG/business-bridge.git
git push -u origin main

# 2. Activer GitHub Pages
# Settings → Pages → Source: main / root
```

---

## 📸 Images à ajouter

Créer un dossier `assets/` et y ajouter :

| Fichier | Dimensions recommandées | Description |
|---------|------------------------|-------------|
| `hero-bg.jpg` | 1920×1080px | Afrique moderne + agriculture + tech |
| `eppridad.jpg` | 800×500px | Vue de l'école ou salle de formation |
| `ferme.jpg` | 800×500px | Vue de la ferme intégrée |
| `kassanmou.jpg` | 800×500px | Interface digitale ou marché |
| `banituri.jpg` | 800×500px | Logo ou interface Banituri |

---

## ➕ Ajouter un client (système duplicable)

Dans la section `#realisations`, dupliquer ce bloc :

```html
<!-- CLIENT X : Nom -->
<article class="client-card fade-up delay-100">
  <div class="h-44 flex items-center justify-center" style="background: ...;">
    <!-- Logo ou image -->
  </div>
  <div class="p-6">
    <h3 class="...">Nom du Client</h3>
    <p class="...">Description courte du projet réalisé.</p>
    <div class="flex flex-wrap gap-2 mb-4">
      <span class="...">Tag 1</span>
      <span class="...">Tag 2</span>
    </div>
    <a href="URL_DU_SITE" class="btn-outline ...">Voir le site →</a>
  </div>
</article>
```

---

## ✅ Fonctionnalités

- [x] Design responsive (mobile, tablette, desktop)
- [x] Animations d'entrée au scroll (Intersection Observer)
- [x] Compteurs animés (section Impact)
- [x] Navbar fixe avec effet glassmorphism au scroll
- [x] Menu mobile overlay
- [x] SEO de base (meta tags, Open Graph)
- [x] Code commenté et maintenable
- [x] Système client duplicable
- [x] Scrollbar personnalisée

---

## 📞 Contact

**Business Bridge**  
Niamey, Niger – Afrique de l'Ouest  
Email : contact@businessbridge.com

---

*© 2026 Business Bridge. Tous droits réservés.*  
*Construire l'Afrique agricole de demain.*
