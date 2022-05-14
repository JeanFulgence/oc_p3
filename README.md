## Projet 3 - Ohmyfood!
### Introduction
Troisième projet du parcours Développeur Web d'OpenClassroom, qui a pour objectif d'intégrer la maquette d'un site de commande de repas en ligne, "Ohmyfood!". 

### Technologie
Cette intégration se fait entièrement en HTML/CSS, sans JavaScript, librairie, ni framework. Aucune balise de style ne doit figurer dans le code HTML.
L'utilisation de Sass est un plus.

### Compatibilité
Le site est développé sur une approche mobile-first. Les versions tablette et deskstop n'étant pas prioritaires, leur mise en page est libre.
L'ensemble du site devra cependant être réactive sur ces trois types de format. Le site devra passer la validation HTML et CSS du W3C.
Le site devra être compatible avec les dernières versions desktop des navigateurs Mozilla Firefox et Google Chrome.

### Contenu
#### Page d'accueil
La page d'accueil contient une courte présentation du site et de son fonctionnement, ainsi qu'une section contenant quatre menus sous forme de cartes.
Les cartes des menus contiennent un lien vers la page du menu concerné, et sa localisation. Il sera possible à terme de choisir sa localisation pour trouver des restaurants proches.

#### Pages de menu
Quatre pages contenant le menu d'un restaurant.

### Header
Le header est présent sur toutes les pages. Il contient le nom du site, et, sur les pages des menus, une icône de flèche permettant de revenir à la page d'accueil.

### Footer
Le footer est identique sur toutes les pages. Le clic sur “Contact” effectue un renvoi vers une adresse mail.

### Effets graphiques
#### Page d'accueil
Quand le site aura plus de menus, un “loading spinner” sera nécessaire. Il devra apparaître pendant 1 à 3 secondes quand on arrive sur la page d'accueil, couvrir l'intégralité de l'écran, et utiliser les animations CSS.
Le design de ce loader est libre tant qu'il est cohérent avec la charte graphique du site.

#### Pages de menu
À l’arrivée sur la page, les plats devront apparaître progressivement avec un léger décalage dans le temps. Ils pourront soit apparaître un par un, soit par groupe “Entrée”, “Plat” et “Dessert”.
Le visiteur peut ajouter les plats qu'il souhaite à sa commande en cliquant dessus. Cela fait apparaître une petite coche à droite du plat. Cette coche devra coulisser de la droite vers la gauche. Pour cette première version, l’effet peut apparaître au survol sur desktop au lieu du clic.
Si l’intitulé du plat est trop long, il devra être rogné avec des points de suspension.

#### Boutons
Au survol, la couleur de fond des boutons principaux devra légèrement s’éclaircir. L’ombre portée devra également être plus visible.
À terme, les visiteurs pourront sauvegarder leurs menus préférés. Pour cela, une icône en forme de cœur est présent sur la maquette, qui devra se remplir progressivement au clic. Pour cette première version, l’effet peut être apparaître au survol sur desktop au lieu du clic.

### Identité graphique
- Polices: Shrikhand (Logo et titres) et Roboto (texte).
- Icônes: Font Awesome.
- Palette de couleurs: primaire #9356DC; secondaire #FF79DA; tertiaire #99E2D0.
