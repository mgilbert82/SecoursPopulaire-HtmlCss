# SecoursPopulaire-HtmlCss

## Contexte: Projet étude en langages HTML et CSS / Utilisation de la bibliotèque Bootstrap
___________________________________________________________________________________________________

Pré-requis, frameworks et ressources :
Bibliotèques utilisées: 

### Utilisation de SASS pour l'organisation et l'optimisation de CSS

- npm install node-sass	=> Permet d’installer le module sass sur son projet
- npx node-sass scss/main.scss style.css
=>Permet de convertir le scss en css
- npx node-sass scss/main.scss style.css —watch	=> Permet de convertir à chaque enregistrement du fichier scss (modification)
- npm install postcss postcss-cli
=> Installer une extension permettant de minifier notre code css
- npm install css nano
=> Installer le plugin pour minifiier le CSS
- npx postcss style.css --use cssnano -o style.min.css
=> Exécuter la minification


### Utilisation de Bootstrap

<!-- Bootstrap CSS link -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css"
    rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3"
    crossorigin="anonymous">
<!-- Bootstrap icone link -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.8.1/font/bootstrap-icons.css">

###  FontAwesome:
  <!--Font awesome -->
  https://kit.fontawesome.com/3524a5a0f2.js
  
### Illustrations:
Les images ont été pris sur le site Pixabay.
  
  ___________________________________________________________________________________________________

## Objectif: Réaliser un site vitrine pour une assocation, le rendre responsive (mobile first).

Le site possède 4 pages : 
- une page d'accueil 
- une page avec les actions réalisées par l'association (soutien scolaire, sortie éducative, braderie/don)
- une page avec une demande de soutien bénévole/partenaire
- une page regroupant les informations liées à l'association
- une page comportant un formulaire a été réalisée (page soutenir > je veux m'inscrire)

  ___________________________________________________________________________________________________

## Design général du site

Un jeu de couleur chaude a été utilisée dont voici les teintes :
- #F4CC70
- #FFB064
- #DE7A22
- #E7DAC1
- #A28C76
- #716C60

Les polices utiliées proviennent du site GoogleFont :

- Poppins: 200/300
- Radio Canada: 300/400
- Ubuntu: 300/400
- Noir et Blanc
