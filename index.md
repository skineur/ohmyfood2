# Ohmyfood :plate_with_cutlery:
Ohmyfood! est une entreprise de commande de repas en ligne. Notre concept permet aux utilisateurs de composer leur propre menu et réduire leur temps d'attente dans les
restaurants car leur menu est préparé à l'avance. Plus de perte de temps à consulter la carte

![Capture d’écran 2022-06-27 180919](https://user-images.githubusercontent.com/2298186/175997245-127a2b2e-6246-4e4e-8402-8bc79867ab3b.png)


## Technologies
Le développement du site web a été réaliser sous Visual Studio Code avec les technologies
- Html5
- CSS3
- SASS
- Git/Github

## Fonctionnalités
La cible étant les personnes connectées et pressées, le site est développé en utilisant l'approche mobile-first. Néanmoins une version tablette et desktop est réalisé à l'aide des média queries

### Page d'accueil
- Affichage de la localisation des restaurants. À terme il sera possible de choisir sa localisation pour trouver des restaurants proches d'un certain lieu.
- Une courte présentation de l'entreprise.
- Une section contenant les 4 menus sous forme cartes. Au clic sur la carte, l'utilisateur est redirigé vers la page du menu.

### Pages de menu
- 4 pages contenant chacune le menu d'un restaurant

### Footer
- Le footer est identique sur toutes les pages.
- Au clic sur &laquo;Contact&raquo;, un renvoi vers une adresse mail est effectué.

### Header
- Le header est présent sur toutes les pages.
- Sur la page d’accueil, il contient le logo du site.
- Sur les pages de menu, il contient en plus un bouton de retour vers la page d’accueil

## Comment demarrer le projet
Cloner le projet puis exécuter la commande sass pour regénérer le fichier css

```bash
sass index.scss:style.css
```
