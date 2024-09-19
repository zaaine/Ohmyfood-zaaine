# Oh-my-food_projet4_Zaaine

**Création d'un site mobile-first pour un groupe de restaurants**

## Marque & Identité

**Ohmyfood** est une entreprise de commande de repas en ligne. Notre concept innovant permet aux utilisateurs de composer leur propre menu à l'avance, réduisant ainsi leur temps d'attente en restaurant, car leurs plats sont préparés à l'avance. Plus besoin de consulter la carte une fois sur place !

## Proposition de valeur

Nous souhaitons offrir à nos clients un accès privilégié aux menus de restaurants gastronomiques. Après un lancement réussi à New York, nous visons désormais la capitale mondiale de la gastronomie : Paris.

## Positionnement

Nous ciblons un marché de niche, en partenariat avec des restaurants haut de gamme dans les villes où nous sommes implantés. Notre ambition est d’être perçus comme un service de commande en ligne premium, à la fois pratique et élégant.

## Concurrence

| Nom de l'entreprise | Nombre de salariés | Domaine d'activité                           | Points forts                                                                            | Points faibles                                                        |
| ------------------- | ------------------ | -------------------------------------------- | --------------------------------------------------------------------------------------- | --------------------------------------------------------------------- |
| **Mylittlefoodie**  | Environ 50         | Réservation dans des palaces parisiens       | Bonne implémentation en France, tarifs préférentiels, site dynamique, bon référencement | Menus non visibles, réservations limitées à deux jours par semaine    |
| **LebonParis**      | 15                 | Classement des restaurants selon leurs menus | Grande variété de restaurants, menus bien mis en avant sur la page d'accueil            | Pas de possibilité de réservation, impossibilité d'agrandir les menus |

## Cible

Nous nous adressons aux classes moyennes et supérieures, connectées, pressées, et désireuses de déguster des produits de qualité rapidement.

## Identité graphique

- **Polices**
  - Logo et titres : _Shrikhand_
  - Texte : _Roboto_
- **Couleurs**
  - Primaire : `#9356DC`
  - Secondaire : `#FF79DA`
  - Tertiaire : `#99E2D0`

## Enjeux

### Problématique

Nous souhaitons déployer notre service à Paris, capitale de la gastronomie.

### Objectifs

- **Phase 1 :** Créer un site mettant en avant les menus de 4 restaurants parisiens réputés.
- **Phase 2 :** Offrir la possibilité de composer son propre menu et de réserver en ligne.

## Fonctionnement

### Budget

20 000 €

### Planning

- **Date de livraison** de la première version du site : 1 mois après le début du projet.

### Technologies

- Le site sera développé en **CSS avec Sass**, sans JavaScript.
- Les fichiers sources `.scss` et le CSS compilé devront être disponibles dans des fichiers dédiés.
- Le développement devra adopter l'approche **Mobile First** : intégration de la maquette mobile en premier, puis adaptation pour tablette et desktop.
- Aucun framework (comme Bootstrap) ne devra être utilisé.
- Aucune règle CSS ne doit être appliquée directement via l’attribut `style` dans les balises HTML.
- Le code sera versionné sur **GitHub** avec des commits réguliers pour suivre l’avancement et faciliter la mise en ligne.

### Compatibilité

Le site, conçu en priorité pour des utilisateurs pressés et connectés, doit être **responsive** et adapté à tous les types d’écrans (mobile, tablette, desktop).

- Les pages devront passer la validation **W3C** pour HTML et CSS sans erreur.
- Compatibilité requise avec les dernières versions de **Chrome** et **Firefox**.

## Livrables attendus

### Contenu des pages

- **Page d'accueil :**
  - Localisation des restaurants. À terme, l’utilisateur pourra choisir sa localisation pour trouver des restaurants à proximité.
  - Brève présentation de l'entreprise.
  - Section avec 4 menus sous forme de cartes. Au clic, redirection vers la page du menu correspondant.
- **Pages de menu (x4) :**
  - Chaque page présente le menu d’un restaurant spécifique.

### Header & Footer

- **Header :**
  - Sur la page d'accueil : contient le logo du site.
  - Sur les pages de menu : contient le logo et un bouton de retour à la page d'accueil.
- **Footer :**
  - Identique sur toutes les pages, il contient un lien de contact renvoyant à une adresse e-mail.

### Effets graphiques et animations

- Les effets au survol ou au clic doivent utiliser des **animations ou transitions CSS**, sans JavaScript ni bibliothèque externe. Les effets doivent inclure un retour à l'état initial lorsque le survol est terminé.
- **Boutons :**
  - Au survol, la couleur de fond des boutons doit s'éclaircir légèrement, avec une ombre plus marquée.
  - Un bouton "J’aime" en forme de cœur est prévu dans la maquette, se remplissant au survol ou au clic (selon la plateforme).

### Page d'accueil

- Un **loader** est prévu pour simuler un chargement entre 1 et 3 secondes lors de l’arrivée sur la page. Ce loader couvrira l’écran entier et sera animé en CSS.

### Pages de menu

- À l'arrivée sur une page, les plats apparaîtront progressivement avec un léger décalage temporel, par section (Entrée, Plat, Dessert).
- Les utilisateurs peuvent ajouter des plats à leur commande en cliquant dessus. Une coche coulissera de la droite vers la gauche pour indiquer la sélection. Sur desktop, l’effet peut apparaître au survol.

## Organisation du projet

Toutes les étapes de validation seront supervisées par **Paul**, le chef de projet.

## Lien vers la maquette

[Accéder à la maquette Figma](<https://www.figma.com/design/O1ACDayPjlxCUHgjgvoE0j/Maquettes-Ohmyfood-(mobile-et-desktop)-(Copy)?node-id=0-1&node-type=canvas&t=FCvisbnjZ64SvZIr-0>)
