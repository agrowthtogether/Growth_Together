# Design System web - Growth Together

> Source d'autorité : `charte graphique GT 1.pdf` (70 pages analysées intégralement).
>
> Version : 1.0 - 26 septembre 2026
>
> Périmètre : traduction de l'identité Growth Together en règles de conception et d'implémentation web. Ce document ne remplace pas les fichiers maîtres du logo.

## Statut des règles

Chaque décision est qualifiée par l'un des statuts suivants :

- **[EXPLICITE]** : règle ou valeur écrite ou montrée sans ambiguïté dans la charte.
- **[DÉDUITE]** : règle observée de manière récurrente dans les compositions ou applications de la charte.
- **[PROPOSÉE POUR LE WEB]** : adaptation nécessaire à une interface responsive, interactive ou accessible, non spécifiée par la charte.

En cas de conflit, une règle **[EXPLICITE]** prime, sauf lorsqu'une adaptation d'accessibilité est signalée. Toute évolution de la marque doit être validée avant d'être intégrée ici.

---

## A. Brand Foundations

### Identité et personnalité

Growth Together exprime une progression individuelle rendue durable par le collectif. **[EXPLICITE]** Son territoire associe :

- l'accessibilité et la bienveillance, portées par des formes rondes et fluides ;
- le mouvement et la progression, incarnés par le symbole ascendant ;
- la rigueur et la crédibilité, exprimées par les grilles, les grands aplats sombres et la typographie sans serif ;
- l'énergie et l'engagement, apportés par le Bleu Élan et l'Orange Élan ;
- l'authenticité du groupe, montrée par des photographies de situations réelles.

Le ton de marque est **positif, bienveillant, accessible, motivant, authentique, engagé, dynamique et fédérateur**. **[EXPLICITE]**

Le positionnement est : « Accompagner chacun dans sa progression, à son rythme, jamais seul » et « Faire grandir les individus en cultivant l'énergie du collectif ». **[EXPLICITE]** L'idée d'impact est : « Grandir seul est possible ; grandir ensemble est durable ». **[EXPLICITE]**

### Signature conceptuelle

Le cadre « Ground. Grow. Widen.™ » structure le discours : **[EXPLICITE]**

1. **Ground** : assumer son point de départ.
2. **Grow** : progresser par le mouvement et les petits pas.
3. **Widen** : élargir sa progression par le collectif et inspirer les autres.

### Éléments immédiatement reconnaissables

- le symbole « w » continu, formé de trois élévations et évoquant un histogramme ascendant ; **[EXPLICITE]**
- le logotype minuscule, rond et retravaillé, avec les liaisons « th » ; **[EXPLICITE]**
- les contrastes Bleu Brume / Nuit Profonde, Bleu Brume / Bleu Ardoise et Bleu Élan / Bleu Brume ; **[EXPLICITE]**
- les grands espaces blancs ou sombres et les compositions asymétriques ; **[DÉDUITE]**
- le motif répétitif construit avec le symbole, plein ou en contour ; **[EXPLICITE]**
- l'orange comme impulsion ponctuelle, jamais comme masse dominante ; **[EXPLICITE]**
- les photographies authentiques de progression, d'échange et de communauté. **[EXPLICITE]**

### Direction artistique en 8 principes

1. **Faire sentir la progression** par la hiérarchie, le rythme vertical et le symbole ascendant. **[DÉDUITE]**
2. **Mettre le collectif au centre**, sans imagerie de performance solitaire ou compétitive. **[EXPLICITE]**
3. **Rester clair et généreux** : peu d'éléments, beaucoup d'espace respirant. **[DÉDUITE]**
4. **Construire sur la grille** : alignements francs, proportions constantes, rythme typographique stable. **[EXPLICITE]**
5. **Faire dominer les bleus** ; réserver l'orange aux signaux et accents. **[EXPLICITE]**
6. **Privilégier les formes arrondies et continues**, jamais agressives ou cassées sans fonction. **[DÉDUITE]**
7. **Montrer des moments vrais**, en mouvement et en relation, plutôt que des scènes de coaching figées. **[EXPLICITE]**
8. **Employer le motif avec retenue** : au plus 30 % de la composition. **[EXPLICITE]**

### À éviter

Les effets gratuits, les dégradés, les ombres décoratives lourdes, les compositions saturées, les couleurs hors palette, les photographies trop posées et l'esthétique de performance compétitive contredisent l'identité. **[EXPLICITE pour couleurs, logo et photographie ; DÉDUITE pour les effets d'interface]**

---

## B. Couleurs

### Palette de marque

| Couleur | Valeur | Rôle dans l'identité | Usage web recommandé | Statut |
|---|---|---|---|---|
| Nuit Profonde | `#091116` · RGB 9, 17, 22 | Fond sombre majeur, alternative de marque au noir | Sections immersives, footer, texte très sombre | **[EXPLICITE]** |
| Bleu Ardoise | `#1C475F` · RGB 28, 71, 95 | Bleu institutionnel, calme et crédible | Texte, fonds de section, logo sur fond clair | **[EXPLICITE]** |
| Bleu Élan | `#2982B3` · RGB 41, 130, 179 | Accent bleu dynamique, progression | CTA, liens, indicateurs actifs, grands aplats ponctuels | **[EXPLICITE]** |
| Bleu Brume | `#DEEEF7` · RGB 222, 238, 247 | Lumière, respiration, douceur | Fonds secondaires, surfaces informatives, logo clair sur fond sombre | **[EXPLICITE]** |
| Blanc Neutre | `#FAFAFA` · RGB 250, 250, 250 | Fond clair principal | Page, surfaces, texte sur fond sombre | **[EXPLICITE via RGB ; correction documentée]** |
| Orange Élan | `#EC4700` · RGB 236, 71, 0 | Énergie, motivation, signal secondaire | Accent bref, repère, numéro, petite icône ; jamais fond dominant | **[EXPLICITE]** |
| Gris Neutre | `#E5E7E6` · RGB 229, 231, 230 | Neutre d'accompagnement | Bordures, séparateurs, fonds désactivés | **[EXPLICITE]** |

La charte imprime `#2FAFAFA` pour le Blanc Neutre, valeur HEX invalide à 7 chiffres. Le RGB indiqué (250, 250, 250) et le rendu visuel établissent `#FAFAFA`. La correction est documentée ici et doit être employée dans le code. **[DÉDUITE]**

Aucune valeur CMYK n'est fournie dans la charte. **[EXPLICITE]**

### Tokens fonctionnels

| Token | Valeur | Emploi | Statut |
|---|---:|---|---|
| `brand-primary` | `#1C475F` | identité institutionnelle, texte et surfaces fortes | **[DÉDUITE]** |
| `brand-secondary` | `#2982B3` | action, progression et état actif | **[DÉDUITE]** |
| `brand-accent` | `#EC4700` | accent ponctuel uniquement | **[EXPLICITE]** |
| `background-primary` | `#FAFAFA` | fond principal clair | **[DÉDUITE]** |
| `background-secondary` | `#DEEEF7` | alternance douce de sections | **[DÉDUITE]** |
| `surface` | `#FAFAFA` | surfaces au-dessus d'un fond coloré | **[PROPOSÉE POUR LE WEB]** |
| `text-primary` | `#091116` | texte principal | **[DÉDUITE]** |
| `text-secondary` | `#1C475F` | texte secondaire | **[DÉDUITE]** |
| `border` | `#E5E7E6` | bordures et séparateurs | **[DÉDUITE]** |
| `success` | `#147A50` | confirmation sémantique, distincte des couleurs de marque | **[PROPOSÉE POUR LE WEB - accessibilité]** |
| `warning` | `#9A5B00` | alerte non bloquante | **[PROPOSÉE POUR LE WEB - accessibilité]** |
| `error` | `#B42318` | erreur et danger | **[PROPOSÉE POUR LE WEB - accessibilité]** |

Les trois couleurs fonctionnelles ne sont pas des couleurs de marque : les limiter aux messages système, champs et statuts qui exigent une convention universelle. **[PROPOSÉE POUR LE WEB]**

### Contrastes vérifiés

Ratios calculés selon WCAG 2.x :

| Premier plan / fond | Ratio | Usage permis |
|---|---:|---|
| Nuit Profonde / Blanc Neutre | 18,23:1 | tout texte, AAA |
| Nuit Profonde / Bleu Brume | 16,02:1 | tout texte, AAA |
| Bleu Ardoise / Blanc Neutre | 9,51:1 | tout texte, AAA |
| Bleu Ardoise / Bleu Brume | 8,36:1 | tout texte, AAA |
| Blanc Neutre / Bleu Ardoise | 9,51:1 | tout texte, AAA |
| Bleu Brume / Nuit Profonde | 16,02:1 | tout texte, AAA |
| Nuit Profonde / Orange Élan | 4,96:1 | texte normal AA ; préférer texte Nuit Profonde sur petit bouton orange |
| Nuit Profonde / Bleu Élan | 4,48:1 | grands textes AA ; échec marginal pour texte normal |
| Blanc Neutre / Bleu Élan | 4,07:1 | grand texte seulement ; ne pas utiliser pour petit texte |
| Bleu Élan / Bleu Brume | 3,58:1 | grand texte et éléments graphiques seulement |
| Blanc Neutre / Orange Élan | 3,68:1 | grand texte et éléments graphiques seulement |
| Bleu Élan / Orange Élan | 1,11:1 | interdit pour texte ou contrôle |

Pour un bouton Bleu Élan, utiliser Nuit Profonde pour le libellé si la taille est inférieure à 18 px gras / 24 px normal. **[PROPOSÉE POUR LE WEB - adaptation accessible]** Pour conserver l'apparence d'un bouton blanc sur Bleu Élan, réserver cette combinaison aux libellés gras d'au moins 18 px ou employer Bleu Ardoise comme fond. **[PROPOSÉE POUR LE WEB]**

### Répartition recommandée

- 60 à 75 % : Blanc Neutre et espaces respirants ; **[DÉDUITE]**
- 15 à 30 % : Nuit Profonde, Bleu Ardoise ou Bleu Brume ; **[DÉDUITE]**
- 5 à 15 % : Bleu Élan ; **[DÉDUITE]**
- moins de 5 % : Orange Élan. **[DÉDUITE à partir de l'interdiction de fond dominant]**

---

## C. Typographie

### Familles

- **Satoshi Bold** : police primaire et base du logo retravaillé. L'utiliser comme caractère de marque pour les displays très courts, chiffres clés ou signatures, sans jamais recomposer le logo en texte. **[EXPLICITE pour la police ; PROPOSÉE POUR LE WEB pour l'usage éditorial]**
- **Open Sans** : police secondaire, optimisée pour l'affichage et la lisibilité. Graisses montrées : Regular, Medium et Bold ; la charte emploie aussi Semi Bold dans le système de titres. Elle porte l'essentiel de l'interface et des contenus. **[EXPLICITE]**
- **Fallback web** : `Arial, Helvetica, sans-serif` si les fichiers de polices ne peuvent pas être servis. **[PROPOSÉE POUR LE WEB]**

Ne pas simuler une graisse absente. Charger au minimum Open Sans 400, 600, 700 et Satoshi 700 en WOFF2, avec `font-display: swap`. **[PROPOSÉE POUR LE WEB]**

### Principes typographiques

- hiérarchie nette et contraste d'échelle important ; **[EXPLICITE]**
- alignement sur une grille de ligne de base ; **[EXPLICITE]**
- titre de référence à 72 px, sous-titre à 36 px, corps à 18 px, légende à 14 px ; **[EXPLICITE]**
- un sous-titre peut occuper deux ou trois lignes et mesure environ la moitié du titre ; **[EXPLICITE]**
- titres compacts, en casse phrase ou capitales selon leur rôle ; longs textes jamais en capitales ; **[DÉDUITE]**
- la signature « Ground. Grow. Widen.™ » conserve sa ponctuation et sa casse. **[EXPLICITE]**

### Échelle typographique web

Les tailles fluides sont bornées entre les valeurs mobile et desktop indiquées. **[PROPOSÉE POUR LE WEB]**

| Style | Famille | Desktop | Mobile | Graisse | Interligne | Tracking | Transformation | Statut |
|---|---|---:|---:|---:|---:|---:|---|---|
| Display | Satoshi | 72 px | 48 px | 700 | 0,98 | -0,03em | aucune | **[EXPLICITE 72 ; PROPOSÉE mobile]** |
| H1 | Open Sans | 64 px | 40 px | 700 | 1,05 | -0,025em | aucune | **[PROPOSÉE POUR LE WEB]** |
| H2 | Open Sans | 48 px | 34 px | 700 | 1,10 | -0,02em | aucune | **[PROPOSÉE POUR LE WEB]** |
| H3 | Open Sans | 36 px | 28 px | 700 | 1,15 | -0,015em | aucune | **[EXPLICITE 36 ; PROPOSÉE mobile]** |
| H4 | Open Sans | 24 px | 22 px | 700 | 1,25 | -0,01em | aucune | **[PROPOSÉE POUR LE WEB]** |
| Body Large | Open Sans | 20 px | 18 px | 400 | 1,55 | 0 | aucune | **[PROPOSÉE POUR LE WEB]** |
| Body | Open Sans | 18 px | 16 px | 400 | 1,60 | 0 | aucune | **[EXPLICITE 18 ; PROPOSÉE mobile]** |
| Small | Open Sans | 16 px | 15 px | 400 | 1,50 | 0 | aucune | **[PROPOSÉE POUR LE WEB]** |
| Caption | Open Sans | 14 px | 14 px | 400 | 1,45 | 0,01em | aucune | **[EXPLICITE 14]** |
| Button | Open Sans | 16 px | 16 px | 700 | 1,20 | 0,01em | aucune | **[PROPOSÉE POUR LE WEB]** |
| Navigation | Open Sans | 15 px | 16 px | 600 | 1,20 | 0,01em | aucune | **[PROPOSÉE POUR LE WEB]** |
| Eyebrow | Open Sans | 14 px | 13 px | 700 | 1,20 | 0,10em | capitales | **[DÉDUITE]** |

Largeur maximale recommandée d'un paragraphe : 65 à 72 caractères. **[PROPOSÉE POUR LE WEB]** Un titre de hero devrait rester sur deux lignes, trois au maximum sur petit écran. **[DÉDUITE]**

---

## D. Logo

### Versions officielles

La charte présente trois compositions : logo horizontal, logo empilé et symbole associé au lettrage. **[EXPLICITE]** Elle montre aussi le symbole seul et les compositions logo + tagline / icône + tagline. **[EXPLICITE]**

Combinaisons autorisées : **[EXPLICITE]**

- Bleu Brume sur Nuit Profonde ;
- Bleu Brume sur Bleu Ardoise ;
- Bleu Brume sur Bleu Élan ;
- Bleu Élan sur Bleu Brume ;
- Bleu Ardoise sur Blanc Neutre ;
- noir sur blanc ;
- blanc sur noir.

Sur le web, préférer les versions Bleu Ardoise / Blanc Neutre et Bleu Brume / Nuit Profonde. Les versions noir et blanc servent uniquement lorsque la couleur est impossible. **[DÉDUITE]**

### Zone de sécurité

La zone minimale est une unité `X` tirée d'une portion du symbole et doit entourer toutes les versions. Aucun texte, image, motif ou autre logo ne peut l'envahir. **[EXPLICITE]**

Les fichiers fournis ne définissent pas la valeur numérique de `X`. Conserver l'espace intégré au fichier maître ; à défaut, réserver autour du logo un espace minimal égal à l'épaisseur d'un fût vertical du symbole. **[DÉDUITE]** Ne jamais recadrer un fichier logo au ras du tracé.

### Tailles minimales web

La charte ne donne pas de taille minimale chiffrée pour le logotype. **[EXPLICITE]** Valeurs opérationnelles : **[PROPOSÉE POUR LE WEB]**

- logo horizontal : largeur minimale 140 px ; cible desktop 168 à 200 px ;
- logo empilé : largeur minimale 96 px ;
- symbole seul : 32 px minimum dans l'interface, 24 px uniquement pour favicon ;
- logo + tagline : largeur minimale 220 px ; en dessous, supprimer la tagline et utiliser le logo officiel seul.

Toute taille reste subordonnée à une lecture nette du mot « together » à 100 % de zoom.

### Contextes web

- **Navigation desktop** : logo horizontal officiel, largeur 168-184 px, aligné à gauche ; zone `X` préservée. **[PROPOSÉE POUR LE WEB]**
- **Navigation mobile** : symbole seul ou version empilée, 36-44 px de haut ; prévoir un nom accessible dans le lien. **[PROPOSÉE POUR LE WEB]**
- **Footer** : logo horizontal ou logo + tagline si sa largeur atteint 220 px ; contraste fort. **[PROPOSÉE POUR LE WEB]**
- **Favicon** : symbole seul centré dans un carré, déclinaisons 16, 32, 48, 180 et 192 px ; priorité à Bleu Brume sur Nuit Profonde ou Bleu Ardoise sur Blanc Neutre. **[PROPOSÉE POUR LE WEB, cohérente avec les icônes sociales explicites]**
- **Réseaux sociaux** : symbole seul dans un disque Bleu Élan, Nuit Profonde ou Gris Neutre, selon les variantes montrées ; respecter les tailles de plateforme. La charte montre 176 × 176 et 128 × 128 px pour Facebook, 400 × 400 px pour LinkedIn, 110 × 110 px pour Instagram et 192 × 192 px pour WhatsApp. **[EXPLICITE]**

### Interdictions

Ne jamais : ajouter contour, ombre ou dégradé ; déformer, étirer ou élargir ; tourner ou renverser ; mélanger les couleurs ; remplir le tracé avec un motif ; poser le logo ou l'icône sur une image trop chargée ou insuffisamment contrastée. **[EXPLICITE]**

Le logo sur photographie n'est permis que sur une zone sobre, uniforme et fortement contrastée. Ajouter si nécessaire un aplat de marque, plutôt qu'une ombre ou un contour au logo. **[EXPLICITE + PROPOSÉE POUR LE WEB]**

---

## E. Grille et layout

### Principe de composition

Les planches de la charte utilisent une grille modulaire, de grands alignements horizontaux, des zones de respiration importantes, une hiérarchie gauche/droite asymétrique et des compositions en mosaïque pour les applications. **[DÉDUITE]** Le contenu web doit donc alterner des sections ouvertes, des divisions 5/7 ou 6/6 et quelques mosaïques photographiques ; il ne doit pas être centré systématiquement. **[PROPOSÉE POUR LE WEB]**

### Containers et grilles

| Contexte | Largeur | Colonnes | Gouttière | Marges latérales | Statut |
|---|---:|---:|---:|---:|---|
| Large desktop ≥ 1440 px | max 1280 px | 12 | 24 px | min 64 px | **[PROPOSÉE POUR LE WEB]** |
| Desktop 1024-1439 px | calc(100% - 96 px) | 12 | 24 px | 48 px | **[PROPOSÉE POUR LE WEB]** |
| Tablette 768-1023 px | calc(100% - 64 px) | 8 | 20 px | 32 px | **[PROPOSÉE POUR LE WEB]** |
| Mobile < 768 px | calc(100% - 40 px) | 4 | 16 px | 20 px | **[PROPOSÉE POUR LE WEB]** |
| Petit mobile < 360 px | calc(100% - 32 px) | 4 | 12 px | 16 px | **[PROPOSÉE POUR LE WEB]** |

Un contenu éditorial long reste dans une colonne de 720 px maximum. **[PROPOSÉE POUR LE WEB]** Les médias peuvent sortir de cette colonne jusqu'au container principal pour préserver l'impact visuel. **[DÉDUITE]**

### Système d'espacement

Base de 4 px avec une échelle courte : **[PROPOSÉE POUR LE WEB]**

| Token | Valeur | Usage type |
|---|---:|---|
| `space-1` | 4 px | micro-ajustement, icône/texte |
| `space-2` | 8 px | groupe très lié |
| `space-3` | 12 px | contrôle compact |
| `space-4` | 16 px | padding courant |
| `space-5` | 24 px | gouttière, groupe de contenu |
| `space-6` | 32 px | bloc ou card |
| `space-7` | 48 px | sous-section |
| `space-8` | 64 px | section mobile |
| `space-9` | 96 px | section desktop standard |
| `space-10` | 128 px | grande respiration / hero |

Espacement vertical de section : 96 à 128 px sur desktop, 64 à 80 px sur tablette, 48 à 64 px sur mobile. **[PROPOSÉE POUR LE WEB]** Alterner les densités pour éviter un empilement mécanique.

### Responsive

- passer les compositions texte/image de 5/7 ou 6/6 à une colonne sous 768 px ; **[PROPOSÉE POUR LE WEB]**
- conserver l'ordre narratif : eyebrow, titre, texte/action, média ; **[PROPOSÉE POUR LE WEB]**
- recadrer les photos par point focal, sans masquer les visages ou interactions ; **[DÉDUITE]**
- ne jamais réduire le motif au point où son trait se casse ; simplifier ou le masquer sur petits écrans ; **[PROPOSÉE POUR LE WEB]**
- maintenir au moins 20 px de marge latérale et 44 px pour les cibles tactiles. **[PROPOSÉE POUR LE WEB]**

---

## F. Formes et éléments graphiques

### Symbole ascendant

Le « w » combine une forme continue, des courbes de rayon identique, une épaisseur constante et des barres de tailles croissantes. Il symbolise les progrès successifs, non linéaires mais orientés vers le haut. **[EXPLICITE]**

Sur le web, il peut être utilisé comme : **[PROPOSÉE POUR LE WEB]**

- repère de section ou marqueur de progression ;
- élément de fond largement recadré à faible contraste ;
- séparateur graphique entre les trois temps Ground / Grow / Widen ;
- masque photographique uniquement si la lisibilité de l'image reste bonne.

Ne jamais redessiner, fragmenter, tourner ni animer la géométrie interne du symbole. **[EXPLICITE pour la transformation ; PROPOSÉE pour l'animation]**

### Motifs

Le motif est une répétition régulière du symbole, en plein ou en contour, dans les combinaisons Bleu Brume / Nuit Profonde et contour / Nuit Profonde ou Bleu Ardoise. Il peut aussi être placé en perspective sur une photographie. **[EXPLICITE]**

Règles :

- couverture maximale : **30 % de la composition** ; **[EXPLICITE]**
- fréquence recommandée : un motif fort au plus toutes les deux ou trois sections ; **[PROPOSÉE POUR LE WEB]**
- opacité sur photographie : 12 à 24 % selon le contraste ; **[PROPOSÉE POUR LE WEB]**
- motif de contour : trait minimal 1 px à l'écran standard, 1,5 px sur grand format ; **[PROPOSÉE POUR LE WEB]**
- ne pas placer derrière un paragraphe, un formulaire ou une action principale ; **[PROPOSÉE POUR LE WEB]**
- ne pas combiner motif, photo chargée et texte dans la même zone. **[DÉDUITE]**

### Lignes, cadres et découpes

Les planches emploient de fines lignes horizontales comme repères de structure et des blocs francs, sans ombre. **[DÉDUITE]** Utiliser des séparateurs 1 px Gris Neutre sur fond clair ou Bleu Ardoise atténué sur fond sombre. **[PROPOSÉE POUR LE WEB]** Les rayons doivent rappeler le logo sans rendre chaque bloc « pilule » : rayon moyen 12 px, grand rayon 20 px, pilule uniquement pour badges et boutons compacts. **[PROPOSÉE POUR LE WEB]**

---

## G. Photographie

### Style

La photographie doit incarner l'authenticité, le mouvement et la force du collectif. Elle montre des moments réels de progression, de connexion et de bienveillance, loin des clichés figés ou trop posés du coaching. **[EXPLICITE]**

Les exemples privilégient : **[DÉDUITE]**

- petits groupes diversifiés en âge, genre et origine ;
- discussions, ateliers, prises de parole, écoute et collaboration ;
- gestes naturels et interactions visibles ;
- lumière naturelle ou intérieure douce ;
- couleurs réalistes, légèrement chaudes, sans dominante artificielle ;
- cadrages mi-larges ou moyens, avec contexte lisible ;
- arrière-plans de travail, d'événement ou de communauté, présents mais non distrayants ;
- contraste modéré et retouche discrète.

### Règles de sélection

1. L'image doit raconter une interaction ou une progression, pas simplement montrer des personnes souriantes. **[DÉDUITE]**
2. Préférer une scène vécue à une banque d'images manifestement mise en scène. **[EXPLICITE]**
3. Représenter la diversité réelle de la communauté avec dignité, sans tokenisme. **[PROPOSÉE POUR LE WEB]**
4. Conserver les textures de peau naturelles et limiter la retouche au cadrage, à l'exposition et à l'harmonisation douce. **[DÉDUITE]**
5. Éviter les poses héroïques solitaires, les poignées de main génériques, les graphiques de réussite factices et les bureaux artificiellement parfaits. **[DÉDUITE]**
6. Prévoir une zone calme si un texte ou logo doit recouvrir la photo ; sinon, séparer texte et image. **[EXPLICITE pour le logo ; PROPOSÉE pour le texte]**
7. Fournir `alt` descriptif lorsqu'une photo est informative et `alt=""` lorsqu'elle est purement décorative. **[PROPOSÉE POUR LE WEB]**

### Formats et traitement

- hero : ratio 16:9 à 3:2, point focal explicite ; **[PROPOSÉE POUR LE WEB]**
- texte + image : 4:3 ou 3:2 ; **[PROPOSÉE POUR LE WEB]**
- portraits équipe : 4:5 cohérent, sans uniformiser artificiellement les arrière-plans ; **[PROPOSÉE POUR LE WEB]**
- mosaïque projet/événement : combiner 3:2, carré et détail, comme dans les projections de marque ; **[DÉDUITE]**
- ne pas appliquer de dégradé coloré de marque ; un voile uni Nuit Profonde peut être utilisé uniquement pour atteindre le contraste du texte. **[PROPOSÉE POUR LE WEB]**

---

## H. Illustrations et icônes

La charte ne définit pas une famille complète d'illustrations ou de pictogrammes d'interface. Elle définit le symbole de marque et montre des constructions géométriques sobres. **[EXPLICITE]**

Pour les icônes UI : **[PROPOSÉE POUR LE WEB]**

- utiliser une seule famille d'icônes outline, géométrique et arrondie ;
- trait 1,75 à 2 px à une taille de 24 px, extrémités et jonctions arrondies ;
- niveaux de détail faibles, sans remplissages mixtes ;
- couleur Nuit Profonde ou Bleu Ardoise ; Bleu Élan pour l'état actif ; couleurs sémantiques uniquement pour les statuts ;
- tailles standard 16, 20, 24 et 32 px ;
- toute icône seule déclenchant une action possède un nom accessible et une cible d'au moins 44 × 44 px.

Ne pas confondre les icônes fonctionnelles avec le symbole Growth Together et ne pas fabriquer de pseudo-logos à partir d'icônes tierces. **[PROPOSÉE POUR LE WEB]**

---

## I. Composants UI

### Boutons

Tous les boutons ont une hauteur minimale de 48 px, un rayon de 12 px, un padding horizontal de 24 px, un libellé Open Sans Bold 16 px et un focus externe de 3 px. **[PROPOSÉE POUR LE WEB]**

#### Primary

- fond Bleu Ardoise, texte Blanc Neutre, sans bordure ;
- hover : fond Nuit Profonde ;
- focus : anneau Bleu Élan de 3 px avec décalage de 2 px ;
- active : fond Nuit Profonde et translation verticale de 1 px ;
- usage : une action principale par zone logique.

**[PROPOSÉE POUR LE WEB]** Cette combinaison respecte la palette et offre 9,51:1 de contraste.

#### Secondary

- fond transparent, texte Bleu Ardoise, bordure Bleu Ardoise 2 px ;
- hover : fond Bleu Brume ;
- focus : même anneau que Primary ;
- active : fond Gris Neutre.

**[PROPOSÉE POUR LE WEB]**

#### Tertiary

- fond transparent, texte Bleu Ardoise, sans bordure ;
- indicateur possible : flèche outline ou soulignement de 2 px ;
- hover : soulignement ou fond Bleu Brume discret ;
- focus : anneau visible ;
- active : texte Nuit Profonde.

**[PROPOSÉE POUR LE WEB]**

#### Accent

Réserver Orange Élan à une action événementielle ou un signal fort, jamais comme style par défaut. Fond Orange Élan, texte Nuit Profonde (4,96:1), libellé gras ; hover Nuit Profonde avec texte Blanc Neutre. **[PROPOSÉE POUR LE WEB, fondée sur l'accent explicite]**

#### Disabled

- fond Gris Neutre, texte Bleu Ardoise à opacité 60 %, aucune ombre ;
- curseur `not-allowed`, attribut `disabled` ou `aria-disabled="true"` correctement géré ;
- l'état ne doit jamais être indiqué par la couleur seule.

**[PROPOSÉE POUR LE WEB]**

### Navigation

#### Desktop

- hauteur cible 80 px ; logo à gauche, liens à droite, CTA unique en dernier ;
- fond Blanc Neutre ou Nuit Profonde, sans gradient ;
- état actif par soulignement 2 px Bleu Élan et graisse 700 ;
- hover par soulignement ou fond Bleu Brume très localisé ;
- conserver une zone `X` autour du logo.

**[PROPOSÉE POUR LE WEB]**

#### Mobile

- hauteur 64-72 px ; symbole 36-44 px ; bouton menu 44 × 44 px ;
- panneau plein écran ou latéral sur fond Nuit Profonde/Blanc Neutre, liens d'au moins 48 px de hauteur ;
- fermeture visible, focus piégé dans le panneau, retour du focus au déclencheur ;
- état actif identique au desktop, complété par `aria-current="page"`.

**[PROPOSÉE POUR LE WEB]**

#### Dropdown

Seulement si l'architecture l'exige. Surface Blanc Neutre, bordure Gris Neutre, rayon 12 px, ombre fonctionnelle légère ; ouverture au clic et au clavier, fermeture avec Échap, navigation fléchée lorsque le composant suit le pattern menu. **[PROPOSÉE POUR LE WEB]**

### Cards

Une card est pertinente pour un élément autonome et cliquable (projet, événement, témoignage, personne). Elle n'est pas le conteneur par défaut de chaque paragraphe. **[PROPOSÉE POUR LE WEB, cohérente avec les compositions ouvertes]**

- fond Blanc Neutre ou Bleu Brume ;
- rayon 16 px ; bordure 1 px Gris Neutre ;
- padding 24 à 32 px ;
- aucune ombre au repos ; ombre très légère ou translation de 2 px au hover si la card est interactive ;
- média bord à bord permis en haut ;
- titres alignés à gauche ;
- accent Orange Élan limité à un badge, un numéro ou un repère, jamais à toute la card.

### Formulaires

#### Champs

- label Open Sans 14-16 px, graisse 600, au-dessus du contrôle ;
- input, textarea, select : hauteur 48 px minimum, padding 12 × 16 px, fond Blanc Neutre, texte Nuit Profonde, bordure 1 px Bleu Ardoise ;
- rayon 10 px ; placeholder plus discret mais d'un contraste minimum 4,5:1 ;
- hover : bordure Bleu Élan ;
- focus : bordure Bleu Élan 2 px + anneau externe 3 px Bleu Brume ;
- textarea : hauteur initiale 128 px, redimensionnement vertical ;
- message d'aide rattaché avec `aria-describedby`.

**[PROPOSÉE POUR LE WEB]**

#### Checkbox et radio

- zone interactive 44 × 44 px ; contrôle visuel 20 × 20 px ;
- coché : fond Bleu Ardoise, marque Blanc Neutre ;
- radio : cercle interne Bleu Élan ;
- focus identique aux champs ; label entier cliquable.

**[PROPOSÉE POUR LE WEB]**

#### Erreurs

- bordure et message `error`, icône ou texte explicite, jamais couleur seule ;
- message placé immédiatement sous le champ ;
- résumé des erreurs en tête pour les formulaires longs ;
- ne pas effacer la saisie après erreur.

**[PROPOSÉE POUR LE WEB]**

### Sections éditoriales

#### Hero

Deux variantes recommandées : **[PROPOSÉE POUR LE WEB]**

1. aplat Nuit Profonde avec titre Blanc Neutre/Bleu Brume, accent court Orange Élan et symbole surdimensionné recadré à faible contraste ;
2. split 5/7 avec texte sur fond uni et photographie authentique, sans texte posé sur une zone chargée.

Une promesse principale, un texte bref, un CTA principal et au plus un CTA secondaire. Hauteur minimale indicative : 70-85vh sur desktop, auto sur mobile.

#### Texte + image

Grille 5/7 ou 6/6, alternance non systématique, image 4:3 ou 3:2. Le texte ne dépasse pas 720 px et garde un espace clair avec le média. **[PROPOSÉE POUR LE WEB]**

#### Mission / Ground-Grow-Widen

Présenter les trois étapes comme un parcours éditorial connecté plutôt que trois cards identiques : ligne de progression, index 01-03, variation de hauteur inspirée du symbole. Sur mobile, passer en séquence verticale. **[PROPOSÉE POUR LE WEB]**

#### Chiffres clés

Chiffres en Satoshi Bold, grands et peu nombreux, libellé Open Sans. Employer Bleu Élan ou Bleu Ardoise ; Orange Élan uniquement sur un chiffre prioritaire. Toujours fournir le contexte et la source. **[PROPOSÉE POUR LE WEB]**

#### Témoignages

Citation mise en page ouverte, portrait facultatif, nom et rôle clairement séparés. Préférer un témoignage fort par viewport à un carrousel automatique. **[PROPOSÉE POUR LE WEB]**

#### Projets

Mosaïque éditoriale ou liste riche avec photographie, résultat et lien. Les cards sont permises parce que chaque projet est autonome, mais varier les formats plutôt que répéter une grille uniforme. **[PROPOSÉE POUR LE WEB, inspirée des projections]**

#### Événements

Hiérarchie : date, titre, lieu/format, disponibilité, CTA. La date peut recevoir l'accent Orange Élan. Ne pas coder l'état uniquement par couleur. **[PROPOSÉE POUR LE WEB]**

#### Équipe

Portraits 4:5, noms et rôles lisibles, biographies courtes accessibles sans hover. Favoriser les regroupements qui montrent le collectif ; ne pas surcharger chaque portrait de badges. **[PROPOSÉE POUR LE WEB]**

#### CTA

Aplat Bleu Ardoise ou Nuit Profonde, message court, une action principale. Le motif peut occuper une bordure ou un angle sans dépasser 30 %. **[PROPOSÉE POUR LE WEB + limite EXPLICITE]**

#### Footer

Fond Nuit Profonde, logo Bleu Brume, texte Blanc Neutre/Bleu Brume, liens regroupés par fonction et signature si l'espace le permet. Prévoir coordonnées, réseaux, mentions légales et focus visibles. **[PROPOSÉE POUR LE WEB]**

---

## J. Motion

Le symbole et le discours évoquent un mouvement continu et une progression ascendante. **[EXPLICITE]** Les animations web doivent traduire cette idée sans spectacle gratuit. **[PROPOSÉE POUR LE WEB]**

- micro-transition standard : 180 ms, courbe `cubic-bezier(0.2, 0, 0, 1)` ;
- transition de panneau/navigation : 280 ms, même courbe ;
- hover : changement de couleur, soulignement ou translation maximale de 2 px ;
- apparition : opacité 0 → 1 et translation verticale 12 px → 0, 320 ms, une seule fois ;
- motif : léger dévoilement par masque ou déplacement maximal de 8 px ; pas de boucle permanente ;
- symbole : ne pas déformer ses barres ; une révélation progressive du tracé est permise si le fichier vectoriel officiel le supporte ;
- carrousel : jamais d'autoplay rapide ; contrôles et pause obligatoires si autoplay indispensable.

Avec `prefers-reduced-motion: reduce`, supprimer translations, parallaxes et animations de tracé ; conserver seulement des changements instantanés ou fondus ≤ 100 ms. **[PROPOSÉE POUR LE WEB - accessibilité]**

---

## K. Accessibilité

Les exigences suivantes sont des adaptations web indispensables : **[PROPOSÉE POUR LE WEB]**

- viser WCAG 2.2 niveau AA ;
- contraste minimal 4,5:1 pour texte courant, 3:1 pour grand texte et composants graphiques ;
- corps de texte minimal 16 px sur mobile et 18 px par défaut sur desktop ;
- zoom jusqu'à 200 % sans perte de contenu ;
- focus visible de 3 px, jamais supprimé ;
- ordre de tabulation identique à l'ordre visuel et logique ;
- cibles tactiles d'au moins 44 × 44 px ;
- navigation et composants entièrement utilisables au clavier ;
- landmarks HTML, niveaux de titres cohérents et lien d'évitement ;
- labels persistants pour les formulaires ; placeholder non substitutif ;
- états actifs, erreurs et succès jamais indiqués par la couleur seule ;
- textes alternatifs adaptés à la fonction des images ;
- sous-titres/transcriptions pour les contenus audiovisuels ;
- respecter `prefers-reduced-motion` et, si un thème sombre existe, `prefers-color-scheme` sans modifier l'identité.

### Adaptations nécessaires de la charte

- Le logo Blanc Neutre sur Bleu Élan est acceptable visuellement mais la combinaison atteint seulement 4,07:1 : elle reste réservée au logo, au grand texte ou aux éléments graphiques, pas au petit texte. **[PROPOSÉE POUR LE WEB]**
- Bleu Élan sur Bleu Brume (3,58:1) est adapté aux grands titres et aux formes, pas au corps de texte. **[PROPOSÉE POUR LE WEB]**
- Orange Élan sur Blanc Neutre (3,68:1) est un accent graphique, pas une couleur de texte courant. Pour un lien orange, ajouter soulignement et employer une variante accessible validée, sans l'introduire comme nouvelle couleur de marque. **[PROPOSÉE POUR LE WEB]**
- Les très grands titres à interligne serré de la charte doivent se détendre sur mobile pour éviter chevauchements et coupures. **[PROPOSÉE POUR LE WEB]**

---

## L. Design Tokens

Les commentaires `EXPLICITE`, `DÉDUITE` et `WEB` conservent la provenance des décisions.

```css
:root {
  /* Colors - EXPLICITE */
  --color-night: #091116;
  --color-slate: #1c475f;
  --color-drive: #2982b3;
  --color-mist: #deeef7;
  --color-white-neutral: #fafafa; /* corrigé depuis RGB 250, 250, 250 */
  --color-orange-drive: #ec4700;
  --color-gray-neutral: #e5e7e6;

  /* Functional colors - DÉDUITE */
  --brand-primary: var(--color-slate);
  --brand-secondary: var(--color-drive);
  --brand-accent: var(--color-orange-drive);
  --background-primary: var(--color-white-neutral);
  --background-secondary: var(--color-mist);
  --surface: var(--color-white-neutral);
  --text-primary: var(--color-night);
  --text-secondary: var(--color-slate);
  --border: var(--color-gray-neutral);

  /* Semantic colors - WEB, états fonctionnels uniquement */
  --success: #147a50;
  --warning: #9a5b00;
  --error: #b42318;

  /* Typography - EXPLICITE families; WEB scale */
  --font-brand: "Satoshi", "Open Sans", Arial, Helvetica, sans-serif;
  --font-sans: "Open Sans", Arial, Helvetica, sans-serif;
  --font-size-caption: 0.875rem; /* 14px - EXPLICITE */
  --font-size-small: 1rem;
  --font-size-body: clamp(1rem, 0.95rem + 0.2vw, 1.125rem);
  --font-size-body-lg: clamp(1.125rem, 1.05rem + 0.25vw, 1.25rem);
  --font-size-h4: clamp(1.375rem, 1.25rem + 0.4vw, 1.5rem);
  --font-size-h3: clamp(1.75rem, 1.5rem + 0.8vw, 2.25rem);
  --font-size-h2: clamp(2.125rem, 1.7rem + 1.3vw, 3rem);
  --font-size-h1: clamp(2.5rem, 1.9rem + 2vw, 4rem);
  --font-size-display: clamp(3rem, 2.2rem + 2.8vw, 4.5rem); /* 72px max EXPLICITE */
  --line-height-tight: 1.05;
  --line-height-heading: 1.15;
  --line-height-body: 1.6;
  --tracking-tight: -0.025em;
  --tracking-label: 0.1em;
  --font-regular: 400;
  --font-medium: 500;
  --font-semibold: 600;
  --font-bold: 700;

  /* Spacing - WEB */
  --space-1: 0.25rem;
  --space-2: 0.5rem;
  --space-3: 0.75rem;
  --space-4: 1rem;
  --space-5: 1.5rem;
  --space-6: 2rem;
  --space-7: 3rem;
  --space-8: 4rem;
  --space-9: 6rem;
  --space-10: 8rem;

  /* Radius - WEB, dérivé des formes arrondies */
  --radius-sm: 0.5rem;
  --radius-md: 0.75rem;
  --radius-lg: 1rem;
  --radius-xl: 1.25rem;
  --radius-pill: 999px;

  /* Borders - WEB */
  --border-width: 1px;
  --border-width-strong: 2px;
  --border-default: var(--border-width) solid var(--border);
  --border-strong: var(--border-width-strong) solid var(--color-slate);
  --focus-ring: 0 0 0 3px var(--color-drive);
  --focus-offset: 2px;

  /* Shadows - WEB, fonctionnelles et discrètes */
  --shadow-sm: 0 2px 8px rgb(9 17 22 / 8%);
  --shadow-md: 0 8px 24px rgb(9 17 22 / 12%);

  /* Layout - WEB */
  --container-max: 80rem; /* 1280px */
  --content-max: 45rem; /* 720px */
  --gutter-mobile: 1.25rem;
  --gutter-tablet: 2rem;
  --gutter-desktop: 3rem;
  --section-space: clamp(4rem, 2.5rem + 5vw, 8rem);
  --touch-target: 2.75rem; /* 44px */

  /* Motion - WEB */
  --duration-fast: 120ms;
  --duration-base: 180ms;
  --duration-slow: 320ms;
  --ease-progress: cubic-bezier(0.2, 0, 0, 1);
}

@media (prefers-reduced-motion: reduce) {
  :root {
    --duration-fast: 0ms;
    --duration-base: 0ms;
    --duration-slow: 100ms;
  }
}
```

---

## M. Do / Don't

### À faire

- utiliser les fichiers maîtres officiels du logo ;
- faire dominer les bleus et les neutres ;
- conserver des espaces généreux et des alignements nets ;
- exprimer la progression par la hiérarchie et le rythme ;
- montrer de vraies interactions collectives ;
- utiliser le motif comme signature secondaire ;
- vérifier le contraste de chaque combinaison ;
- adapter l'échelle typographique au viewport ;
- rendre chaque état interactif perceptible au clavier ;
- documenter toute nouvelle extrapolation avec son statut.

### À ne pas faire

- recomposer le logo avec une police ;
- ajouter contour, ombre, gradient ou texture au logo ;
- étirer, retourner ou tourner le symbole ;
- remplacer Nuit Profonde par `#000000` dans une composition de marque ;
- utiliser Orange Élan comme grand fond dominant ;
- colorer des paragraphes ou titres entiers en Orange Élan ;
- empiler des cards pour structurer tout le site ;
- utiliser une photo chargée derrière un logo ou un texte ;
- mélanger plusieurs familles d'icônes ;
- ajouter des animations décoratives en boucle.

---

## Design Guardrails

1. Utiliser uniquement les sept couleurs de marque documentées ; les couleurs sémantiques sont réservées aux états système.
2. Employer `#FAFAFA` pour le Blanc Neutre ; ne jamais reprendre la coquille `#2FAFAFA`.
3. Ne jamais substituer `#000000` à Nuit Profonde `#091116` dans une composition de marque.
4. Réserver Orange Élan aux accents ponctuels et aux repères ; il ne doit pas devenir un fond dominant.
5. Ne jamais appliquer de dégradé aux couleurs de marque, au logo ou au symbole.
6. Utiliser exclusivement les fichiers officiels du logo ; ne jamais le recomposer ni modifier ses liaisons.
7. Préserver la zone de sécurité `X` du logo et vérifier sa lisibilité à la taille réellement rendue.
8. Ne jamais ajouter contour, ombre, motif ou texture au logo ou au symbole.
9. Ne jamais déformer, étirer, tourner, renverser ou fragmenter le symbole.
10. Poser le logo sur une image uniquement si la zone est sobre et fortement contrastée.
11. Maintenir le motif à 30 % maximum de toute composition.
12. Ne jamais placer le motif derrière du texte courant, un formulaire ou une action principale.
13. Utiliser Satoshi avec parcimonie comme caractère de marque et Open Sans pour l'interface et les contenus.
14. Conserver une hiérarchie typographique forte, mais limiter les titres à trois lignes sur mobile.
15. Ne pas utiliser Bleu Élan, Orange Élan ou Bleu Brume comme couleur de texte courant sans contrôle WCAG.
16. Privilégier les compositions ouvertes, les séparations par espace et les grilles asymétriques ; ne pas tout enfermer dans des cards.
17. Choisir des photographies authentiques de progression et de collectif ; éviter les scènes génériques, figées ou compétitives.
18. Employer une seule famille d'icônes outline, arrondie et géométrique dans tout le produit.
19. Limiter les animations à l'explication d'un état, d'une progression ou d'une transition ; aucune boucle décorative.
20. Toute règle absente de la charte doit être marquée **[PROPOSÉE POUR LE WEB]** avant d'être considérée comme norme.
