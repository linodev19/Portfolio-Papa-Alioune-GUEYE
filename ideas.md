# Portfolio Cinéaste - Stratégie de Design

## Approches Stylistiques Considérées

### 1. **Cinéma Noir Moderne** (Sélectionné)
**Probabilité:** 0.08

Esthétique inspirée du cinéma noir des années 50 revisitée avec une sensibilité contemporaine. Contraste dramatique noir-rouge, typographie cinématographique, animations fluides et cinématiques.

---

## Approche Choisie : **Cinéma Noir Moderne**

### Design Movement
**Film Noir + Modernisme Numérique**
Fusion du style cinématographique classique (contraste extrême, dramatisme) avec l'esthétique web contemporaine (fluidité, micro-interactions, typographie audacieuse).

### Core Principles
1. **Dramatisme Cinématographique** - Chaque section raconte une histoire visuelle, avec des contrastes saisissants et des transitions fluides
2. **Minimalisme Stratégique** - Espace blanc généreux pour mettre en avant le contenu vidéo et les projets
3. **Mouvement Intentionnel** - Animations subtiles mais percutantes qui reflètent le dynamisme du cinéma
4. **Hiérarchie Visuelle Forte** - Typographie imposante et contraste couleur pour guider l'œil

### Color Philosophy
- **Noir (#0a0a0a)** : Fond principal, élégance, profondeur, neutralité
- **Rouge Vif (#e63946 ou #ff0000)** : Accent énergique, passion cinématographique, appels à l'action
- **Blanc/Gris Clair (#f5f5f5, #e0e0e0)** : Texte principal, contraste maximal
- **Gris Charcoal (#1a1a1a)** : Sections secondaires, profondeur

**Intent:** Le noir crée une toile de fond cinématographique immersive, le rouge incarne l'énergie créative et l'urgence du cinéma.

### Layout Paradigm
- **Hero Section Asymétrique** : Vidéo showreel en full-width avec overlay texte positionné bas-gauche
- **Grille Décalée** : Carrousels YouTube en grille 2-3 colonnes avec décalage vertical pour dynamisme
- **Sections Alternées** : Contenu texte/image alternant gauche-droite pour rythme naturel
- **Espaces Respiratoires** : Sections larges avec padding généreux, pas de centrage rigide

### Signature Elements
1. **Ligne Rouge Verticale** : Élément graphique récurrent séparant sections, symbolisant le "cut" cinématographique
2. **Badges de Catégories** : Petits éléments rouges avec texte blanc pour les types de projets (Institutionnel, Série, Spot, etc.)
3. **Animations de Transition** : Fade-in/slide-in au scroll, effet "film strip" sur les carrousels

### Interaction Philosophy
- **Hover Effects Subtils** : Les vidéos s'agrandissent légèrement, les textes se colorent en rouge
- **Scroll Triggers** : Animations au scroll pour créer une sensation de cinéma interactif
- **Carrousels Fluides** : Navigation intuitive avec boutons discrets, autoplay optionnel
- **Feedback Immédiat** : Chaque interaction produit une réponse visuelle claire

### Animation Guidelines
- **Durée** : 300-500ms pour les transitions principales, 150-200ms pour les micro-interactions
- **Easing** : `cubic-bezier(0.23, 1, 0.32, 1)` pour les entrées (snappy), `cubic-bezier(0.77, 0, 0.175, 1)` pour les mouvements
- **Scroll Animations** : Fade-in + slide-up au scroll, stagger de 50-80ms entre éléments
- **Autoplay Vidéos** : Pause au survol, lecture fluide sans saccades
- **Respect Motion** : `@media (prefers-reduced-motion: no-preference)` pour les animations non-essentielles

### Typography System
- **Display Font** : Playfair Display (serif, bold) pour les titres principaux - élégance cinématographique
- **Heading Font** : Montserrat (sans-serif, 600-700) pour les sous-titres - modernité
- **Body Font** : Inter (sans-serif, 400-500) pour le texte courant - lisibilité
- **Hierarchy** : H1 60px, H2 40px, H3 28px, Body 16px, Small 14px

### Brand Essence
**One-liner:** Portfolio cinématographique pour un créateur de contenus audiovisuels professionnels - où passion, technique et innovation se rencontrent.

**Personality:** Cinématique, Professionnel, Dynamique

### Brand Voice
- **Headlines** : Percutants, évocateurs, cinématographiques
  - ✅ "Réalisations qui captivent"
  - ✅ "Du concept à l'écran"
  - ❌ "Bienvenue sur mon site"
  
- **CTAs** : Directs, actifs, énergiques
  - ✅ "Découvrir le showreel"
  - ✅ "Explorer les projets"
  - ❌ "Cliquez ici"

- **Microcopy** : Professionnel mais accessible, évite le jargon excessif

### Wordmark & Logo
**Concept** : Symbole graphique minimaliste représentant un "frame" ou "clap" de cinéma
- Forme géométrique : Carré/rectangle avec ligne rouge diagonale (rappelle le clap de cinéma)
- Pas de texte dans le logo (logo seul sur fond noir)
- Couleur : Rouge vif sur fond transparent
- Utilisation : Header, favicon, éléments de branding

### Signature Brand Color
**Rouge Cinématographique : #e63946**
Couleur unmistakable, énergique, rappelle l'urgence et la passion du cinéma. Utilisée pour :
- Accents principaux (boutons, lignes, badges)
- Hover states
- Appels à l'action
- Éléments de séparation

---

## Sections du Site

### 1. Landing Page (Hero)
- Vidéo showreel en full-width background
- Overlay noir semi-transparent (0.4-0.5 opacity)
- Texte overlay : Nom, titre professionnel, CTA
- Navigation fixe en haut

### 2. À Propos / Compétences
- Section avec présentation courte
- Grille de compétences : Réalisation, Vidéographie, Montage, Direction, etc.
- Icônes + texte, badges rouges

### 3. Réalisations / Portfolio
- Carrousels YouTube par catégorie :
  - Institutionnels
  - Séries/Films
  - Spots Publicitaires
  - Vidéos Promotionnelles
  - Contenus Créatifs
- Grille décalée, 2-3 colonnes
- Hover effect : Agrandissement + overlay info

### 4. Showreel Section
- Vidéo principale en mise en avant
- Description et stats (durée, année, etc.)

### 5. Contact / Footer
- Formulaire simple ou liens de contact
- Réseaux sociaux
- Copyright

---

## Décisions Techniques

- **Framework** : HTML/CSS pur (vanilla, pas de framework JS lourd)
- **Vidéos** : Intégration YouTube via iframes
- **Animations** : CSS transitions + animations, JavaScript minimal
- **Responsive** : Mobile-first, breakpoints à 768px et 1024px
- **Performance** : Lazy loading pour les vidéos, optimisation des images

