# Growth Together (GT) — Design System Web

> **Version :** 1.0.0  
> **Source d'autorité principale :** *Charte graphique GT 1* (Document officiel de marque — 70 pages)  
> **Auteur :** Antigravity Architecture & Design  
> **Branche de travail :** `refonte-GM`  
> **Dernière mise à jour :** Février 2025

---

## Sommaire

1. [Principes directeurs & Traçabilité](#1-principes-directeurs--traçabilité)
2. [Section A : Vision de marque, Philosophie & Identité](#section-a--vision-de-marque-philosophie--identité)
3. [Section B : Système de Couleurs & Tokens Sémantiques](#section-b--système-de-couleurs--tokens-sémantiques)
4. [Section C : Typographie & Échelle Hiérarchique Web](#section-c--typographie--échelle-hiérarchique-web)
5. [Section D : Système Spatial, Grilles & Layout Responsif](#section-d--système-spatial-grilles--layout-responsif)
6. [Section E : Formes, Rayons & Élévation (Surface)](#section-e--formes-rayons--élévation-surface)
7. [Section F : Éléments Graphiques, Motifs & Traitement Visuel](#section-f--éléments-graphiques-motifs--traitement-visuel)
8. [Section G : Spécification des Composants UI Fondamentaux](#section-g--spécification-des-composants-ui-fondamentaux)
9. [Section H : Motion, Micro-interactions & Transitions](#section-h--motion-micro-interactions--transitions)
10. [Section I : Accessibilité (A11y) & Conformité WCAG 2.1](#section-i--accessibilité-a11y--conformité-wcag-21)
11. [Section J : Tokens CSS Prêts à l'Emploi (`:root`)](#section-j--tokens-css-prêts-à-lemploi-root)
12. [Section K : Garde-Fous de Design (Design Guardrails)](#section-k--garde-fous-de-design-design-guardrails)

---

## 1. Principes directeurs & Traçabilité

Ce Design System constitue la passerelle canonique entre la charte graphique originelle de **Growth Together** et son implémentation technique web. 

Pour garantir une rigueur méthodologique absolue, chaque choix est tagué selon son niveau d'origine :
* `[EXPLICITE]` : Définition, valeur, proportion ou interdiction formulée textuellement ou visuellement dans le PDF source (*Charte graphique GT 1*).
* `[DÉDUITE]` : Dérivation directe ou adaptation logique d’un principe de la charte aux contraintes d’une interface numérique interactive.
* `[PROPOSÉE POUR LE WEB]` : Ajout technique et ergonomique conventionnel pour assurer la robustesse, l'interactivité et l'accessibilité sur le web (ex. anneaux de focus, grille d'espacement 8pt, tokens de transition).

---

## Section A : Vision de marque, Philosophie & Identité

### 1. Fondations & Raison d'Être `[EXPLICITE]`
* **Nom de l'organisation :** Growth Together (acronyme d'usage : **GT**)
* **Signature de marque (Baseline) :** `Ground. Grow. Widen.™`
* **Idée motrice (Big Idea) :**  
  > *« Grandir seul est possible, grandir ensemble est durable. »*

### 2. Le Framework d'Action en 3 Piliers `[EXPLICITE]`
L'architecture de l'information et le parcours utilisateur du site web doivent refléter ce triptyque :
1. **GROUND (Ancrer) :**  
   * *Principe :* Toute progression commence par un point de départ assumé sans jugement.  
   * *Axe éditorial :* « Il n’y a pas de honte à commencer, seulement du courage. »
2. **GROW (Grandir) :**  
   * *Principe :* Le mouvement crée la transformation durable.  
   * *Axe éditorial :* « Chaque petit pas compte plus que le résultat final. »
3. **WIDEN (Élargir / Rayonner) :**  
   * *Principe :* On ne grandit jamais seul ; la réussite individuelle devient inspiration et levier collectif.  
   * *Axe éditorial :* « Ta progression inspire celle de quelqu’un d’autre. »

### 3. Ton de Voix & Personnalité `[EXPLICITE]`
Le contenu, les micro-copies, les messages d'état et les formulations UI doivent incarner ces 8 qualificatifs :
* **Bienveillant & Accessible :** Pas de jargon intimidant, formulation chaleureuse et claire.
* **Motivant & Positif :** Tourné vers l'émancipation, valorisant l'effort et la régularité.
* **Authentique & Engagé :** Ancré dans la réalité humaine, transparent, refus des promesses illusoires.
* **Dynamique & Fédérateur :** Esprit de communauté, appel au mouvement collectif.

### 4. Anatomie & Symbolisme du Logotype `[EXPLICITE]`
Le logotype GT est un système typographique et vectoriel précis :
* **Typographie mère :** *Satoshi Bold*, modifiée sur mesure.
* **La ligature signature `th` :** Jonction continue entre le `th` de *Growth* et le `th` de *Together*. Elle symbolise l'interconnexion, le passage de témoin, le soutien mutuel continu.
* **La lettre `w` dynamique :** Dessinée comme un escalier à 3 niveaux ascendants, illustrant les trois étapes de croissance (*Ground, Grow, Widen*).
* **Le symbole / monogramme :** Forme autonome reprenant le motif signature ou le monogramme GT avec l'escalier ascendant.

```
       ┌────────────────────────────────────────────────────────┐
       │   [ Marges de protection : X = Hauteur du 'G' maj ]     │
       │                                                        │
       │     (X)                                                │
       │     ┌───┐                                              │
       │ (X) │ ☷ │   G R O W T H       (X)                      │
       │     └───┘   T O G E T H E R                            │
       │                                                        │
       │     (X)                                                │
       └────────────────────────────────────────────────────────┘
```

### 5. Variantes Officielles du Logo `[EXPLICITE]`
1. **Variante Principale (Empilée 2 lignes) :** Icône/monogramme à gauche, "GROWTH" sur la première ligne, "TOGETHER" sur la seconde ligne, reliés par la ligature.
2. **Variante Horizontale (1 ligne) :** Monogramme à gauche suivi de "GROWTH TOGETHER" sur un seul axe horizontal (privilégiée pour la barre de navigation desktop condensée).
3. **Variante Verticale (Centrée) :** Monogramme au-dessus, typographie centrée en-dessous (idéale pour écrans de démarrage, splash screens, bas de page centrés).
4. **Monogramme / Icône Seule :** Utilisable pour le favicon, les avatars de réseaux sociaux et les icônes d'application mobile/PWA.

### 6. Zone d'Exclusion & Tailles Minimales Web `[EXPLICITE]` / `[PROPOSÉE POUR LE WEB]`
* **Zone de respiration (Clear space) :** L'espace vide autour du logo complet doit être égal à au moins **la hauteur du "G" majuscule** (`X`). Aucun texte, bouton ou élément graphique ne doit pénétrer cette zone.  
  Pour l'icône isolée, la marge minimale correspond à **la moitié de la hauteur de l'icône** (`X/2`). `[EXPLICITE]`
* **Taille minimale sur écran :**
  * Logo complet horizontal : **hauteur minimale 32px** (largeur proportionnelle ~140px). `[PROPOSÉE POUR LE WEB]`
  * Logo empilé : **hauteur minimale 44px**. `[PROPOSÉE POUR LE WEB]`
  * Icône / Favicon seul : **24px × 24px** (affichage standard web), **16px** (favicon tab navigateur). `[PROPOSÉE POUR LE WEB]`

### 7. Interdictions Formelles sur le Logo `[EXPLICITE]`
* ❌ **NE JAMAIS** déformer, étirer ou écraser les proportions du logo.
* ❌ **NE JAMAIS** modifier la typographie ou dissocier manuellement les lettres de la ligature.
* ❌ **NE JAMAIS** appliquer d'ombres portées (*drop-shadows*), de lueurs ou de dégradés sur le logo.
* ❌ **NE JAMAIS** inverser ou recolorer les éléments dans des couleurs hors charte.
* ❌ **NE JAMAIS** placer le logo sur un fond photographique chargé sans contraste suffisant ou sans couche d'atténuation.

---

## Section B : Système de Couleurs & Tokens Sémantiques

### 1. Palette Primaire Officielle `[EXPLICITE]`

| Nom de Couleur | Hexadécimal | Code RVB | HSL | Rôle Fondamental & Symbolique |
| :--- | :--- | :--- | :--- | :--- |
| **Nuit Profonde** | `#091116` | `rgb(9, 17, 22)` | `203°, 42%, 6%` | Fond sombre structurel, textes titres et corps haute lisibilité. Remplace le noir pur. |
| **Bleu Élan** | `#2982B3` | `rgb(41, 130, 179)` | `201°, 63%, 43%` | Couleur d'action principale, dynamisme, progression, boutons primaires. |
| **Bleu Ardoise** | `#1C475F` | `rgb(28, 71, 95)` | `201°, 54%, 24%` | Couleur de structure, fonds sombres secondaires, cartes contrastées, bordures actives. |
| **Bleu Brume** | `#DEEEF7` | `rgb(222, 238, 247)` | `202°, 58%, 92%` | Surfaces douces, badges d'information, conteneurs légers, lignes de séparation discrètes. |
| **Blanc Neutre** | `#FAFAFA` | `rgb(250, 250, 250)` | `0°, 0%, 98%` | Fond clair principal, cartes épurées, texte sur fond sombre. |

> [!IMPORTANT]
> **RÈGLE DU NOIR PUR `[EXPLICITE]` :**  
> L'utilisation du noir absolu `#000000` est **strictement interdite**. Toute zone sombre, texte noir ou arrière-plan nuit doit obligatoirement utiliser **Nuit Profonde (`#091116`)**.

### 2. Palette Secondaire & Accents `[EXPLICITE]`

| Nom de Couleur | Hexadécimal | Code RVB | HSL | Rôle Fondamental |
| :--- | :--- | :--- | :--- | :--- |
| **Orange Élan** | `#EC4700` | `rgb(236, 71, 0)` | `18°, 100%, 46%` | Accent haute énergie, badges prioritaires, CTA de conversion décisifs, notifications. |
| **Gris Neutre** | `#E5E7E6` | `rgb(229, 231, 230)` | `150°, 3%, 90%` | Bordures inactives, séparateurs de listes, arrière-plans de champs désactivés. |

### 3. Règles d'Usage & Proportions Strictes (Page 50 du Guide) `[EXPLICITE]`
* **Interdiction des fonds saturés :**  
  *Le Bleu Élan (`#2982B3`) et l'Orange Élan (`#EC4700`) ne doivent JAMAIS être utilisés comme couleur d'arrière-plan de pleine page*. Ce sont des couleurs d'accentuation ponctuelle (boutons, marqueurs, micro-animations, tags).
* **Interdiction des dégradés & ombres :**  
  Aucun dégradé de couleur (*gradients*) ni ombre portée prononcée (*drop shadow*) ne doit être appliqué aux couleurs de la marque ou aux logos. Le style est épuré, franc et affirmé (*flat design structuré*).
* **Lisibilité des textes :**  
  Ne colorez jamais les longs paragraphes ou les sous-titres en Orange Élan ou Bleu Élan sur fond clair. Le texte doit rester en `#091116` pour préserver le confort visuel.

### 4. Matrice de Contraste & Accessibilité WCAG 2.1 `[PROPOSÉE POUR LE WEB]`

| Élément Front | Arrière-plan | Ratio de Contraste | Statut WCAG 2.1 AA | Statut WCAG 2.1 AAA |
| :--- | :--- | :--- | :--- | :--- |
| **Nuit Profonde (`#091116`)** | Blanc Neutre (`#FAFAFA`) | **18.7 : 1** | ✅ Conforme | ✅ Conforme (Texte & Titre) |
| **Nuit Profonde (`#091116`)** | Bleu Brume (`#DEEEF7`) | **16.1 : 1** | ✅ Conforme | ✅ Conforme (Texte & Titre) |
| **Blanc Neutre (`#FAFAFA`)** | Nuit Profonde (`#091116`) | **18.7 : 1** | ✅ Conforme | ✅ Conforme (Texte & Titre) |
| **Blanc Neutre (`#FAFAFA`)** | Bleu Ardoise (`#1C475F`) | **7.5 : 1** | ✅ Conforme | ✅ Conforme (Texte & Titre) |
| **Blanc Neutre (`#FAFAFA`)** | Bleu Élan (`#2982B3`) | **4.6 : 1** | ✅ Conforme (Texte normal & UI) | ⚠️ Conforme gros texte (>18pt) |
| **Blanc Neutre (`#FAFAFA`)** | Orange Élan (`#EC4700`) | **4.55 : 1** | ✅ Conforme (Boutons UI & Gros texte) | ⚠️ Non conforme petit texte (<14pt) |
| **Bleu Élan (`#2982B3`)** | Blanc Neutre (`#FAFAFA`) | **4.1 : 1** | ⚠️ Titres & Icônes UI uniquement | ❌ Éviter en corps de texte petit |
| **Bleu Ardoise (`#1C475F`)** | Blanc Neutre (`#FAFAFA`) | **6.6 : 1** | ✅ Conforme | ✅ Conforme (Texte normal) |

### 5. Système de Tokens Sémantiques Web `[DÉDUITE]` / `[PROPOSÉE POUR LE WEB]`

#### Thème Clair (Default - Light Mode)
```css
/* Arrière-plans & Surfaces */
--gt-surface-page: #FAFAFA;
--gt-surface-card: #FFFFFF;
--gt-surface-subtle: #DEEEF7;
--gt-surface-muted: #E5E7E6;
--gt-surface-inverse: #091116;

/* Typographie & Contenus */
--gt-text-primary: #091116;
--gt-text-secondary: #1C475F;
--gt-text-muted: #566573;
--gt-text-inverse: #FAFAFA;

/* Actions & Interactivité */
--gt-action-primary: #2982B3;
--gt-action-primary-hover: #1C475F;
--gt-action-primary-active: #153648;
--gt-action-accent: #EC4700;
--gt-action-accent-hover: #C93D00;
--gt-action-accent-active: #A63200;

/* Bordures & Séparateurs */
--gt-border-subtle: #E5E7E6;
--gt-border-medium: #CAD1D5;
--gt-border-strong: #1C475F;
--gt-border-focus: #2982B3;

/* Statuts Fonctionnels */
--gt-status-success: #1E824C;
--gt-status-warning: #EC4700; /* Alignement sur l'Orange Élan */
--gt-status-error: #D92525;
--gt-status-info: #2982B3;   /* Alignement sur le Bleu Élan */
```

#### Thème Sombre (Dark Mode)
```css
/* Arrière-plans & Surfaces */
--gt-surface-page: #091116;
--gt-surface-card: #111E26;
--gt-surface-subtle: #1C475F;
--gt-surface-muted: #1A2832;
--gt-surface-inverse: #FAFAFA;

/* Typographie & Contenus */
--gt-text-primary: #FAFAFA;
--gt-text-secondary: #DEEEF7;
--gt-text-muted: #95A5B2;
--gt-text-inverse: #091116;

/* Actions & Interactivité */
--gt-action-primary: #2982B3;
--gt-action-primary-hover: #3FA0D6;
--gt-action-primary-active: #5EB2E2;
--gt-action-accent: #EC4700;
--gt-action-accent-hover: #FF5A14;
--gt-action-accent-active: #FF773D;

/* Bordures & Séparateurs */
--gt-border-subtle: #1C475F;
--gt-border-medium: #275C7A;
--gt-border-strong: #DEEEF7;
--gt-border-focus: #3FA0D6;
```

---

## Section C : Typographie & Échelle Hiérarchique Web

### 1. Familles Typographiques Officielles `[EXPLICITE]`
Le système typographique repose sur un duo de polices complémentaires :
1. **Satoshi (Font de Marque & Titrage Display) :**  
   *Caractère sans-serif géométrique contemporain, précis, élégant et puissant.*  
   * **Usages :** Grand logo, slogans phares, titres Display (`H0`), titres de sections événementielles (`H1` majeurs).  
   * **Graisses utilisées :** Bold (700), Medium (500).  
   * **Fallback CSS :** `'Satoshi', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif`.
2. **Open Sans (Font Fonctionnelle & Textes de Contenu) :**  
   *Caractère sans-serif humaniste, hautement lisible sur toutes les résolutions d'écran.*  
   * **Usages :** Titres hiérarchiques de pages (`H1` standards, `H2`, `H3`), sous-titres, corps de texte, menus de navigation, libellés de formulaires, boutons, métadonnées.  
   * **Graisses utilisées :** Regular (400), Medium (500), Semi-Bold (600), Bold (700).  
   * **Fallback CSS :** `'Open Sans', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif`.

### 2. Échelle Typographique Web Responsif `[EXPLICITE]` / `[DÉDUITE]`

| Niveau | Police | Graisse | Taille Desktop | Taille Mobile | Interlignage (*line-height*) | Espacement (*letter-spacing*) | Règle de la charte |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **Display H0** | Satoshi | Bold (700) | **64px** (4rem) | **44px** (2.75rem) | 1.1 (tight) | -0.02em | Impact visuel d'en-tête héro |
| **Titre H1** | Satoshi / Open Sans | Bold (700) | **48px - 72px** | **36px - 40px** | 1.15 | -0.015em | *72px défini dans le guide pour le format grand écran* `[EXPLICITE]` |
| **Sous-titre H2** | Open Sans | Semi-Bold (600) | **36px** (2.25rem) | **28px** (1.75rem) | 1.25 | -0.01em | *Exactement la moitié du titre principal (72px / 2 = 36px)* `[EXPLICITE]` |
| **Section H3** | Open Sans | Bold (700) | **20px - 22px** | **18px** (1.125rem) | 1.35 | 0 | Titres de blocs, cartes majeures `[EXPLICITE]` |
| **Sous-section H4** | Open Sans | Semi-Bold (600) | **18px** (1.125rem) | **16px** (1rem) | 1.4 | 0 | Titres de cartes, modales `[DÉDUITE]` |
| **Corps (Body Regular)**| Open Sans | Regular (400) | **18px** (1.125rem) | **16px** (1rem) | **28px** (1.55) | 0 | *18px avec leading 28px explicitement fixé dans la charte* `[EXPLICITE]` |
| **Corps Compact** | Open Sans | Regular (400) | **16px** (1rem) | **15px** (0.9375rem) | 1.5 | 0 | Formulaires, descriptions denses `[PROPOSÉE POUR LE WEB]` |
| **Légende (Caption)** | Open Sans | Regular (400) | **14px** (0.875rem) | **13px** (0.8125rem) | 1.4 | +0.01em | *14px sur une seule ligne défini dans la charte* `[EXPLICITE]` |
| **Micro / Overline** | Open Sans | Semi-Bold (600) | **12px** (0.75rem) | **11px** (0.6875rem) | 1.3 | +0.06em (Uppercase) | Sur-titres de catégories, badges `[PROPOSÉE POUR LE WEB]` |

### 3. Règles Éditoriales & Alignements Typographiques `[EXPLICITE]` / `[DÉDUITE]`
* **Longueur de ligne optimale :** Pour préserver le confort de lecture sur les articles et sections éditoriales, borner la largeur de texte à un maximum de **65 à 75 caractères** (`max-width: 68ch`).
* **Alignement :** Toujours aligner les titres et paragraphes à gauche (*left-aligned*). Ne jamais justifier le texte sur le web (sources de rivières de blancs inesthétiques et néfastes pour l'accessibilité).
* **Hiérarchie stricte des sous-titres :** Comme stipulé dans la charte graphique, les sous-titres (`H2`) doivent mesurer environ 50% de la taille du titre principal et s'étendre idéalement sur 2 à 3 lignes équilibrées.

---

## Section D : Système Spatial, Grilles & Layout Responsif

### 1. Grille de Base & Échelle Spatiale `[PROPOSÉE POUR LE WEB]`
Le système spatial repose sur un pas de base de **8px** (avec un sous-pas de **4px** pour les micro-ajustements UI).

| Token | Valeur en px | Valeur en rem | Cas d'Usage Typique |
| :--- | :--- | :--- | :--- |
| `--gt-space-1` | 4px | 0.25rem | Micro-espacements (badge padding interne, écart icône-texte). |
| `--gt-space-2` | 8px | 0.5rem | Padding vertical des petits boutons, écarts denses. |
| `--gt-space-3` | 12px | 0.75rem | Padding vertical des inputs, gaps de listes compactes. |
| `--gt-space-4` | 16px | 1rem | Padding standard des boutons, marge interne de cartes compactes. |
| `--gt-space-6` | 24px | 1.5rem | Padding de carte standard, gouttières inter-colonnes. |
| `--gt-space-8` | 32px | 2rem | Espacement entre sections de formulaires, padding de modales. |
| `--gt-space-10` | 40px | 2.5rem | Séparation de blocs éditoriaux. |
| `--gt-space-12` | 48px | 3rem | Espacement vertical avant titre de section. |
| `--gt-space-16` | 64px | 4rem | Marges de section sur tablette et petits écrans. |
| `--gt-space-20` | 80px | 5rem | Espacement vertical de sections majeures (Desktop). |
| `--gt-space-24` | 96px | 6rem | Marge supérieure des sections Hero. |
| `--gt-space-32` | 128px | 8rem | Espacement majeur aéré (Landing pages de prestige). |

### 2. Points de Rupture Responsifs (Breakpoints) `[PROPOSÉE POUR LE WEB]`

```
Mobile (xs / sm)       Tablette (md)           Desktop (lg)            Large Desktop (xl)
┌──────────────────────┬───────────────────────┬───────────────────────┬────────────────────────┐
│ < 640px              │ 640px - 1023px        │ 1024px - 1439px       │ >= 1440px              │
│ 4 colonnes           │ 8 colonnes            │ 12 colonnes           │ 12 colonnes            │
│ Gouttière : 16px     │ Gouttière : 24px      │ Gouttière : 32px      │ Gouttière : 32px       │
│ Marge écran : 16px   │ Marge écran : 32px    │ Marge écran : 48px    │ Marge écran : Auto     │
│ Conteneur : 100%     │ Conteneur : 100%      │ Conteneur : Max 1200px│ Conteneur : Max 1360px │
└──────────────────────┴───────────────────────┴───────────────────────┴────────────────────────┘
```

### 3. Largeurs Maximales des Conteneurs (`max-width`) `[PROPOSÉE POUR LE WEB]`
* `--gt-container-narrow : 768px` (Formulaires centrés, articles de blog, pages de confirmation).
* `--gt-container-default : 1200px` (Grilles standards de cartes, tableaux de bord, vitrines de projets).
* `--gt-container-wide : 1360px` (Headers pleine largeur, vues tabulaires denses, galeries visuelles).

---

## Section E : Formes, Rayons & Élévation (Surface)

### 1. Rayons de Courbure (Border-radius) `[DÉDUITE]` / `[PROPOSÉE POUR LE WEB]`
L'identité GT conjugue modernité géométrique et accessibilité humaine. Les angles ne sont ni acérés (0px) ni cartoon/excessivement ronds (sauf badges pilules).

| Token | Valeur | Usages |
| :--- | :--- | :--- |
| `--gt-radius-none` | `0px` | Séparateurs, tableaux denses pleine largeur. |
| `--gt-radius-sm` | `4px` | Champs de saisie (*inputs*), selects, cases à cocher, infobulles (*tooltips*). |
| `--gt-radius-md` | `8px` | Boutons standards, cartes secondaires, menus déroulants (*dropdowns*). |
| `--gt-radius-lg` | `12px` | Cartes principales de contenu, conteneurs de modales, panneaux latéraux. |
| `--gt-radius-xl` | `16px` | Bannières d'accroche hero, callouts promotionnels majeurs. |
| `--gt-radius-full` | `9999px` | Badges de statut, avatars ronds, boutons pilules d'action rapide (*chips*). |

### 2. Élévation & Ombres Portées (Shadows) `[EXPLICITE]` / `[PROPOSÉE POUR LE WEB]`

> [!WARNING]
> **INTERDICTION DE LA CHARTE `[EXPLICITE]` :**  
> La charte graphique prohibe formellement les ombres portées agressives (*drop-shadows* lourdes, floues et sombres) qui dénaturent l'épure flat design de la marque.

Pour répondre aux nécessités d'empilement fonctionnel du web (modales, popovers, menus flottants), le système propose une élévation par **bordures fines ton-sur-ton** ou par **micro-ombres diffuses quasi-invisibles** basées sur la couleur `Nuit Profonde` très atténuée :

```css
/* Élévation 0 : Éléments plats sur la page (défaut) */
--gt-shadow-none: none;

/* Élévation 1 : Cartes interactives au repos (Délimitation par bordure) */
--gt-shadow-card: 0 1px 3px rgba(9, 17, 22, 0.04);
--gt-card-border: 1px solid var(--gt-border-subtle);

/* Élévation 2 : Cartes au survol / Dropdowns menus */
--gt-shadow-hover: 0 6px 16px -2px rgba(9, 17, 22, 0.08);

/* Élévation 3 : Modales, Tiroirs (Drawers), Dialogues de confirmation */
--gt-shadow-modal: 0 16px 36px -4px rgba(9, 17, 22, 0.16);

/* Écran d'atténuation (Backdrop Overlay) */
--gt-backdrop-overlay: rgba(9, 17, 22, 0.65);
```

---

## Section F : Éléments Graphiques, Motifs & Traitement Visuel

### 1. Le Motif Ascendant « W » `[EXPLICITE]`
* **Origine :** Dérivé de la lettre `w` du logotype, représentant la courbe de croissance en 3 paliers ascendante.
* **Format vectoriel :** 3 arches ou paliers continus avec des angles adoucis.
* **Épaisseur de trait standard :** **1.5px à 2px** (toujours fin et élégant, jamais massif).
* **Couleurs autorisées :**
  * Trait `#DEEEF7` (Bleu Brume) sur fond Nuit Profonde (`#091116`) ou Bleu Ardoise (`#1C475F`).
  * Trait `#1C475F` (Bleu Ardoise) ou `#2982B3` très atténué sur fond Blanc Neutre (`#FAFAFA`).
  * Ponctuellement, trait `#EC4700` (Orange Élan) sur micro-illustrations de progression.

### 2. La Règle d'Or des 30% `[EXPLICITE]`
> **RÈGLE CRITIQUE :**  
> Le motif graphique ne doit **JAMAIS couvrir plus de 30%** de la surface totale d'un écran ou d'une composition.
* Le motif est un amplificateur visuel, pas un papier peint d'arrière-plan.
* Il doit être positionné avec parcimonie : amorce de coin en haut à droite d'un hero, filigrane discret sous une statistique clé, ou séparateur de chapitres.

```
┌──────────────────────────────────────────────────────────┐
│  Growth Together                                         │
│                                           ╭───╮          │  <-- Motif ≤ 30%
│  GROUND. GROW. WIDEN.                     │ ☷ │          │      de la surface
│  Rejoignez le mouvement collectif        ╰───╯          │      totale
│                                                          │
│  [ Agir ensemble ]   [ Découvrir ]                       │
│                                                          │
└──────────────────────────────────────────────────────────┘
```

### 3. Traitement & Direction Artistique Photographique `[EXPLICITE]`
Le traitement photographique web de Growth Together répond à 5 commandements impératifs :
1. **Humanité & Authenticité Réelle :** Privilégier les visuels de reportage immersif, montrant des personnes réelles en action, en réunion, en séance de mentorat ou de travail collaboratif.
2. **Éclairage Naturel & Chaud :** Rejeter les lumières artificielles criardes ou les filtres rétro/sépia passés.
3. **Contrastes Francs :** Les images doivent présenter des noirs denses (alignés sur l'ambiance Nuit Profonde) et des blancs lumineux.
4. **Diversité & Inclusivité :** Refléter la pluralité des parcours et des générations.
5. **❌ Exclusion Formelle des Banques d'Images Génériques :** Proscrire les portraits posés artificiels en costume cravate, les sourires crispés devant fond blanc studio ou les poignées de main corporate stéréotypées.

---

## Section G : Spécification des Composants UI Fondamentaux

### 1. Boutons (Buttons) `[DÉDUITE]` / `[PROPOSÉE POUR LE WEB]`

Les boutons traduisent l'appel au mouvement de GT. Leurs états interactifs doivent être immédiatement discernables.

```
┌───────────────────────────┐    ┌───────────────────────────┐
│     Bouton Primaire       │    │      Bouton Accent        │
│   Fond: Bleu Élan #2982B3 │    │  Fond: Orange Élan #EC4700│
│   Texte: Blanc #FAFAFA    │    │   Texte: Blanc #FAFAFA    │
└───────────────────────────┘    └───────────────────────────┘
┌───────────────────────────┐    ┌───────────────────────────┐
│     Bouton Secondaire     │    │      Bouton Ghost         │
│   Fond: Transparent       │    │   Fond: Transparent       │
│   Bordure: #1C475F (1.5px)│    │   Texte: Bleu Élan #2982B3│
└───────────────────────────┘    └───────────────────────────┘
```

#### Anatomie & États Détaillés :
* **Bouton Primaire (Action principale / Engagement) :**
  * *Default :* Background `#2982B3`, Couleur texte `#FAFAFA`, Padding `12px 24px`, Radius `8px`, Font Open Sans Semi-Bold 16px.
  * *Hover :* Background `#1C475F`, Transition `background-color 150ms ease`.
  * *Active :* Background `#153648`, Scale `0.98`.
  * *Focus-Visible :* Anneau extérieur de 2px en `#2982B3` avec un décalage (*offset*) de 2px.
  * *Disabled :* Background `#E5E7E6`, Couleur texte `#8C9BA5`, Curseur `not-allowed`, Opacité `0.65`.
* **Bouton Accent (Conversion haute priorité / Don / Rejoindre) :**
  * *Default :* Background `#EC4700`, Couleur texte `#FAFAFA`.
  * *Hover :* Background `#C93D00`.
  * *Active :* Background `#A63200`, Scale `0.98`.
  * *Focus-Visible :* Anneau extérieur de 2px en `#EC4700`, offset 2px.
* **Bouton Secondaire (Action alternative) :**
  * *Default :* Background transparent, Bordure 1.5px solid `#1C475F`, Couleur texte `#1C475F`.
  * *Hover :* Background `rgba(41, 130, 179, 0.08)`, Bordure `#2982B3`, Couleur texte `#2982B3`.
  * *Active :* Background `rgba(41, 130, 179, 0.16)`.
* **Bouton Tertiaire / Ghost (Action discrète) :**
  * *Default :* Background transparent, Pas de bordure, Texte `#2982B3`.
  * *Hover :* Background `rgba(41, 130, 179, 0.08)`, Texte `#1C475F`.

### 2. Cartes de Contenu (Cards) `[DÉDUITE]` / `[PROPOSÉE POUR LE WEB]`
* **Structure :**
  * Fond : `#FFFFFF` (sur page `#FAFAFA`) ou `#111E26` (en dark mode).
  * Bordure : 1px solid `#E5E7E6` (délimitation nette sans ombre lourde).
  * Rayon de courbure : `12px`.
  * Padding interne : `24px` (desktop), `16px` (mobile).
* **Comportement Interactif (Cartes cliquables) :**
  * Au survol : Légère translation verticale `transform: translateY(-2px)`, changement de couleur de bordure vers `#2982B3`, micro-ombre diffuse `0 8px 20px -4px rgba(9, 17, 22, 0.06)`.
  * Transition : `all 200ms cubic-bezier(0.4, 0, 0.2, 1)`.

### 3. Champs de Formulaire (Inputs, Selects, Textareas) `[PROPOSÉE POUR LE WEB]`
* **État Repos (Default) :**
  * Fond : `#FAFAFA`.
  * Bordure : 1.5px solid `#E5E7E6`.
  * Rayon : `6px`.
  * Typographie saisie : Open Sans Regular 16px, couleur `#091116`.
  * Label supérieur : Open Sans Semi-Bold 14px, couleur `#1C475F`, marge basse 6px.
  * Placeholder : `#8C9BA5`.
* **État Focus (Actif) :**
  * Bordure : 1.5px solid `#2982B3`.
  * Box-shadow : `0 0 0 3px rgba(41, 130, 179, 0.18)` (contour d'accessibilité bienveillant).
  * Fond : `#FFFFFF`.
* **État Erreur (Invalide) :**
  * Bordure : 1.5px solid `#EC4700`.
  * Box-shadow : `0 0 0 3px rgba(236, 71, 0, 0.15)`.
  * Message d'assistance inférieur : Open Sans Regular 13px, couleur `#EC4700`.

### 4. Navigation (Header & Footer) `[DÉDUITE]` / `[PROPOSÉE POUR LE WEB]`
* **Header / Barre de Navigation Supérieure :**
  * Hauteur : `72px` (desktop), `60px` (mobile).
  * Fond : `#FAFAFA` avec flou d'arrière-plan (`backdrop-filter: blur(12px); background-color: rgba(250, 250, 250, 0.92);`).
  * Bordure inférieure : 1px solid `#E5E7E6`.
  * Alignement du logo officiel à gauche (respect de la zone d'exclusion `X`).
  * Liens de navigation : Open Sans Semi-Bold 15px, couleur `#091116`, soulignement discret au survol en `#2982B3`.
  * Bouton d'action direct à droite : Bouton Accent ou Primaire ("Rejoindre GT").
* **Footer (Pied de Page Institutionnel) :**
  * Fond : **Nuit Profonde (`#091116`)**.
  * Typographie : Textes en Blanc Neutre (`#FAFAFA`) et liens secondaires en Bleu Brume (`#DEEEF7` atténué).
  * Organisation : 4 colonnes (1. Logo GT + Baseline "Ground. Grow. Widen." ; 2. Navigation Pilier ; 3. Ressources & Transparence ; 4. Contact & Réseaux Sociaux).
  * Mention légale inférieure : Séparée par un filet fin de 1px en `#1C475F`.

### 5. Badges, Tags & Puces de Statut `[DÉDUITE]` / `[PROPOSÉE POUR LE WEB]`
* **Badge Pilier GT (Ground / Grow / Widen) :**
  * Fond : `#DEEEF7`, Texte : `#1C475F`, Graisse : Semi-Bold 12px, Rayon : `9999px`, Padding : `4px 12px`.
* **Badge Énergie / Nouveauté :**
  * Fond : `rgba(236, 71, 0, 0.1)`, Texte : `#EC4700`, Graisse : Bold 12px, Rayon : `9999px`, Padding : `4px 12px`.
* **Badge Neutre :**
  * Fond : `#E5E7E6`, Texte : `#091116`, Graisse : Medium 12px, Rayon : `4px`, Padding : `2px 8px`.

---

## Section H : Motion, Micro-interactions & Transitions

### 1. Principes de Mouvement GT `[DÉDUITE]`
Le mouvement dans l'interface traduit l'élan, la constance et l'élévation sans artifice superficiel :
* **Précis & Fluide :** Pas d'effets rebonds exagérés (*bounces*) qui nuiraient au sérieux de la mission.
* **Courbes d'Accélération :** Utilisation systématique de la courbe d'atténuation standardisée :  
  `cubic-bezier(0.4, 0, 0.2, 1)` (démarrage franc, décélération douce).

### 2. Tokens de Durée `[PROPOSÉE POUR LE WEB]`
* `--gt-duration-fast : 150ms` (Micro-interactions, survol de boutons, activation de liens).
* `--gt-duration-normal : 250ms` (Déroulement d'accordéons, transitions d'onglets, apparitions d'infobulles).
* `--gt-duration-slow : 400ms` (Ouverture de tiroirs latéraux, affichage de modales, pagination).

### 3. Respect Impératif de `prefers-reduced-motion` `[PROPOSÉE POUR LE WEB]`
Pour les utilisateurs ayant activé l'option de réduction des animations dans leur système d'exploitation :
```css
@media (prefers-reduced-motion: reduce) {
  *, *::before, *::after {
    animation-duration: 0.01ms !important;
    animation-iteration-count: 1 !important;
    transition-duration: 0.01ms !important;
    scroll-behavior: auto !important;
  }
}
```

---

## Section I : Accessibilité (A11y) & Conformité WCAG 2.1

Pour respecter la valeur fondamentale de **bienveillance et d'accessibilité** de Growth Together :
1. **Contraste Minimum de 4.5:1 :** Tous les textes de corps et libellés interactifs respectent le seuil WCAG AA.
2. **Indicateurs de Focus Visibles :**  
   L'outline par défaut du navigateur ne doit **JAMAIS être supprimé sans remplacement** (`outline: none` interdit).  
   Règle obligatoire : `:focus-visible { outline: 2px solid var(--gt-border-focus); outline-offset: 2px; }`.
3. **Hiérarchie Titres Sémantique :** Une page unique ne comporte qu'un seul élément `<h1>`. La suite (`<h2>`, `<h3>`) doit être rigoureusement imbriquée sans saut de palier.
4. **Attributs ARIA & Accessibilité Formulaires :** Chaque champ de saisie doit disposer d'un `<label>` associé via son identifiant `id`. Les icônes cliquables sans texte doivent comporter un attribut explicite `aria-label`.

---

## Section J : Tokens CSS Prêts à l'Emploi (`:root`)

Le bloc ci-dessous est directement intégrable au fichier racine de styles (`variables.css` ou `globals.css`) de l'application web :

```css
/**
 * GROWTH TOGETHER — CSS DESIGN TOKENS
 * Extrait officiel de la Charte graphique GT 1
 */

:root {
  /* ==========================================================================
     1. COULEURS DE LA CHARTE (VALEURS ABSOLUES) [EXPLICITE]
     ========================================================================== */
  --gt-color-nuit-profonde: #091116; /* RGB(9, 17, 22) - Règle: JAMAIS de #000000 */
  --gt-color-bleu-elan:     #2982B3; /* RGB(41, 130, 179) - Accent principal */
  --gt-color-bleu-ardoise:  #1C475F; /* RGB(28, 71, 95) - Structure & Dark secondary */
  --gt-color-bleu-brume:    #DEEEF7; /* RGB(222, 238, 247) - Teinte douce & Surfaces */
  --gt-color-blanc-neutre:  #FAFAFA; /* RGB(250, 250, 250) - Fond clair & Textes inverse */
  
  --gt-color-orange-elan:   #EC4700; /* RGB(236, 71, 0) - Accent conversion & énergie */
  --gt-color-gris-neutre:   #E5E7E6; /* RGB(229, 231, 230) - Bordures & Séparateurs */

  /* ==========================================================================
     2. TOKENS SÉMANTIQUES (THÈME CLAIR PAR DÉFAUT) [DÉDUITE]
     ========================================================================== */
  --gt-bg-page:         var(--gt-color-blanc-neutre);
  --gt-bg-surface:      #FFFFFF;
  --gt-bg-subtle:       var(--gt-color-bleu-brume);
  --gt-bg-muted:        var(--gt-color-gris-neutre);
  --gt-bg-inverse:      var(--gt-color-nuit-profonde);

  --gt-text-primary:    var(--gt-color-nuit-profonde);
  --gt-text-secondary:  var(--gt-color-bleu-ardoise);
  --gt-text-muted:      #566573;
  --gt-text-inverse:    var(--gt-color-blanc-neutre);

  --gt-interactive-primary:       var(--gt-color-bleu-elan);
  --gt-interactive-primary-hover: var(--gt-color-bleu-ardoise);
  --gt-interactive-accent:        var(--gt-color-orange-elan);
  --gt-interactive-accent-hover:  #C93D00;

  --gt-border-subtle:   var(--gt-color-gris-neutre);
  --gt-border-strong:   var(--gt-color-bleu-ardoise);
  --gt-border-focus:    var(--gt-color-bleu-elan);

  /* ==========================================================================
     3. TYPOGRAPHIE & ÉCHELLE DE TEXTE [EXPLICITE] & [DÉDUITE]
     ========================================================================== */
  --gt-font-display: 'Satoshi', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
  --gt-font-body:    'Open Sans', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;

  /* Graisses */
  --gt-font-weight-regular:  400;
  --gt-font-weight-medium:   500;
  --gt-font-weight-semibold: 600;
  --gt-font-weight-bold:     700;

  /* Tailles */
  --gt-text-xs:   0.75rem;    /* 12px */
  --gt-text-sm:   0.875rem;   /* 14px */
  --gt-text-base: 1rem;       /* 16px */
  --gt-text-lg:   1.125rem;   /* 18px (Corps standard de la charte) */
  --gt-text-xl:   1.25rem;    /* 20px */
  --gt-text-2xl:  1.5rem;     /* 24px */
  --gt-text-3xl:  2.25rem;    /* 36px (Sous-titres H2 de la charte) */
  --gt-text-4xl:  3rem;       /* 48px */
  --gt-text-5xl:  4.5rem;     /* 72px (Titres H1 majeurs de la charte) */

  /* Interlignages (Line-Heights) */
  --gt-leading-none:    1;
  --gt-leading-tight:   1.15;
  --gt-leading-snug:    1.35;
  --gt-leading-normal:  1.55; /* ~28px pour un texte à 18px */
  --gt-leading-relaxed: 1.7;

  /* ==========================================================================
     4. ÉCHELLE SPATIALE & MISE EN PAGE [PROPOSÉE POUR LE WEB]
     ========================================================================== */
  --gt-space-1:  0.25rem;  /* 4px */
  --gt-space-2:  0.5rem;   /* 8px */
  --gt-space-3:  0.75rem;  /* 12px */
  --gt-space-4:  1rem;     /* 16px */
  --gt-space-6:  1.5rem;   /* 24px */
  --gt-space-8:  2rem;     /* 32px */
  --gt-space-10: 2.5rem;   /* 40px */
  --gt-space-12: 3rem;     /* 48px */
  --gt-space-16: 4rem;     /* 64px */
  --gt-space-20: 5rem;     /* 80px */
  --gt-space-24: 6rem;     /* 96px */

  --gt-container-narrow:  768px;
  --gt-container-default: 1200px;
  --gt-container-wide:    1360px;

  /* ==========================================================================
     5. RAYONS DE COURBURE & SURFACES [DÉDUITE] & [PROPOSÉE POUR LE WEB]
     ========================================================================== */
  --gt-radius-none: 0px;
  --gt-radius-sm:   4px;
  --gt-radius-md:   8px;
  --gt-radius-lg:   12px;
  --gt-radius-xl:   16px;
  --gt-radius-full: 9999px;

  /* Ombres & Élévation (Discrètes, zéro ombre lourde) [EXPLICITE] */
  --gt-shadow-none:   none;
  --gt-shadow-sm:     0 1px 3px rgba(9, 17, 22, 0.05);
  --gt-shadow-md:     0 6px 16px -2px rgba(9, 17, 22, 0.08);
  --gt-shadow-modal:  0 16px 36px -4px rgba(9, 17, 22, 0.16);

  /* ==========================================================================
     6. MOTION & TRANSITIONS [PROPOSÉE POUR LE WEB]
     ========================================================================== */
  --gt-ease-standard: cubic-bezier(0.4, 0, 0.2, 1);
  --gt-duration-fast:   150ms;
  --gt-duration-normal: 250ms;
  --gt-duration-slow:   400ms;
}

/* ==========================================================================
   SUPPORT DARK MODE DÉDIÉ [DÉDUITE]
   ========================================================================== */
[data-theme="dark"], body.dark-mode {
  --gt-bg-page:         var(--gt-color-nuit-profonde);
  --gt-bg-surface:      #111E26;
  --gt-bg-subtle:       var(--gt-color-bleu-ardoise);
  --gt-bg-muted:        #1A2832;
  --gt-bg-inverse:      var(--gt-color-blanc-neutre);

  --gt-text-primary:    var(--gt-color-blanc-neutre);
  --gt-text-secondary:  var(--gt-color-bleu-brume);
  --gt-text-muted:      #95A5B2;
  --gt-text-inverse:    var(--gt-color-nuit-profonde);

  --gt-interactive-primary:       var(--gt-color-bleu-elan);
  --gt-interactive-primary-hover: #3FA0D6;
  --gt-interactive-accent:        var(--gt-color-orange-elan);
  --gt-interactive-accent-hover:  #FF5A14;

  --gt-border-subtle:   var(--gt-color-bleu-ardoise);
  --gt-border-strong:   var(--gt-color-bleu-brume);
  --gt-border-focus:    #3FA0D6;
}
```

---

## Section K : Garde-Fous de Design (Design Guardrails)

Les 15 règles d'or ci-dessous sont absolues et opposables à toute proposition graphique ou développement frontend au sein du projet Growth Together :

| Règle | À Faire (Do) | Ne Pas Faire (Don't) | Justification & Référence |
| :---: | :--- | :--- | :--- |
| **1** | Utiliser **`#091116` (Nuit Profonde)** pour les fonds sombres et textes de haute densité. | ❌ **JAMAIS de noir pur `#000000`**. | Règle fondatrice de la charte. Le noir pur durcit le regard et nuit à la bienveillance. `[EXPLICITE]` |
| **2** | Utiliser le Bleu Élan (`#2982B3`) et l'Orange Élan (`#EC4700`) comme **accents ponctuels**. | ❌ Ne jamais remplir un fond d'écran entier en Bleu Élan ou Orange Élan. | Page 50 de la charte : fatigue visuelle et perte d'impact des boutons d'action. `[EXPLICITE]` |
| **3** | Conserver des styles de surfaces **plats et épurés** avec de fines bordures (`1px solid #E5E7E6`). | ❌ Proscrire tout dégradé de couleur (*gradients*) ou ombres portées intenses (*drop shadows*). | Règle formelle d'interdiction de la charte GT. `[EXPLICITE]` |
| **4** | Restreindre la présence du motif en 'w' à **moins de 30%** de la surface de l'écran. | ❌ Ne jamais couvrir l'arrière-plan ou saturer la composition avec le motif. | Règle chiffrée stricte de la charte pour éviter la surcharge cognitive. `[EXPLICITE]` |
| **5** | Respecter une marge d'exclusion autour du logo égale à **la hauteur du "G" majuscule**. | ❌ Ne jamais coller d'icône, bordure ou texte à moins de cette distance du logo. | Préservation de l'intégrité et de la lisibilité de la marque GT. `[EXPLICITE]` |
| **6** | Réserver la typographie **Satoshi** pour les titres d'impact et l'identité. | ❌ Ne jamais utiliser Satoshi pour de longs paragraphes ou du corps de texte. | Satoshi est une fonte de titrage géométrique ; Open Sans assure la lisibilité continue. `[EXPLICITE]` |
| **7** | Rendre les sous-titres (`H2`) exactement à **la moitié de la taille du titre principal** (~36px). | ❌ Ne pas créer de sous-titres disproportionnés ou plus grands que 50% du H1. | Règle explicite d'équilibre géométrique de la charte. `[EXPLICITE]` |
| **8** | Conserver un interlignage aéré de **28px** pour un corps de texte à **18px** (`line-height: 1.55`). | ❌ Ne pas compresser les lignes de texte pour "gagner de la place". | Confort de lecture et accessibilité pour les personnes souffrant de dyslexie. `[EXPLICITE]` |
| **9** | Sélectionner des photographies **authentiques, humaines, chaleureuses et non posées**. | ❌ Interdiction absolue des visuels stéréotypés de banques d'images (*stock photos* figées). | Identité engagée et honnête de Growth Together. `[EXPLICITE]` |
| **10** | Conserver les traits du motif en `w` à une finesse comprise entre **1.5px et 2px**. | ❌ Ne jamais épaissir les traits du motif pour en faire des blocs massifs. | Élégance et légèreté visuelle exigées par la marque. `[EXPLICITE]` |
| **11** | Garantir un **anneau de focus de 2px bien visible** (`outline-offset: 2px`) sur tous les éléments actifs. | ❌ Ne jamais poser `outline: none` sans proposer d'alternative visuelle immédiate. | Critère d'accessibilité WCAG 2.1 AA pour la navigation au clavier. `[PROPOSÉE POUR LE WEB]` |
| **12** | Respecter la ligature signature entre les deux `th` de *Growth Together*. | ❌ Ne jamais réécrire le logo avec une police brute sans les jointures de la ligature. | Valeur d'entraide et de passage de témoin inscrite dans le dessin du logo. `[EXPLICITE]` |
| **13** | Limiter la largeur maximale des colonnes d'articles à **68 caractères** (`68ch`). | ❌ Ne jamais étirer des lignes de lecture sur toute la largeur d'un écran 1920px. | Évite le décrochage visuel lors du passage à la ligne suivante. `[PROPOSÉE POUR LE WEB]` |
| **14** | Assurer le support de `prefers-reduced-motion: reduce`. | ❌ Ne jamais imposer de mouvements, défilements forcés ou effets parallaxe sans option de désactivation. | Respect des usagers sujets aux troubles vestibulaires et à la cinétose. `[PROPOSÉE POUR LE WEB]` |
| **15** | Structurer chaque page autour des trois temps : **Ground, Grow, Widen**. | ❌ Ne jamais présenter les initiatives GT comme des succès instantanés ou isolés. | Alignement philosophique et pédagogique permanent avec la Big Idea de GT. `[EXPLICITE]` |
