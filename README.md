
# Site CV de Chérhazad BOUSTANI - Conceptrice Développeuse d'Applications Full Stack Filière JAVA en recherche d'alternance

## Introduction 

Bonjour, moi c'est Chérhazad BOUSTANI. Je suis issue d'une formation Bac +5 en Biologie des plantes pour l'agro-environnement et je suis en réorientation professionnelle dans le Développement Full Stack. J'ai créé ce site CV pour avoir de la visibilité notamment dans le cadre de ma recherche d'alternance.

## Structure du site

Ce site CV est pour l'instant composé d'une seule page présentant brièvement mon parcours de formation et mes expériences profesionnelles. Des rubriques supplémentaires présentent mes coordonnées, mes compétences, mes atouts, mon niveau de connaissance en langues, des liens externes vers mes réseaux et un formulaire de contact pour pouvoir me joindre. 

## Etapes de construction de ce site CV

### Installation de npm et ses packages
- dans le terminal : npm install -g npm@10.5.0 

### Donner les autorisations à mon mac pour son installation
- dans le terminal : sudo chown -R $USER $(npm config get prefix)/{lib/node_modules,bin,share}

### Installation de Boostrap avec npm
- dans le terminal : npm install bootstrap

### Dans mon dossier local
- création du répertoire sass
- création du fichier index.scss dans répertoire sass
- importation du fichier bootstrap.scss depuis le fichier index.scss

### Dans le terminal 
- se placer dans le dossier sass
- npm install -g sass
- compiler index.scss vers le fichier css/style.css avec la commande : sass --watch index.scss style.css

### Dans VSCode
- importer (avec @import) le fichier style.css dans le fichier index.html
- vérifier que les classes bootstrap fonctionnent 
- si oui, ajouter un fichier _variables.scss dans le répertoire sass
- dans variables.scss, ajout des variables $danger, $warning, $primary $success (couleurs de mon choix)
- importer en 1ère ligne le fichier _variables.scss depuis le fichier index.scss
- vérifier que les nouvelles couleurs sont bien utilisées (btn btn-success) => bouton couleur choisie dans la variable

## Remerciements 

Je remercie les personnes m'ayant fourni les ressources pour pouvoir construire ce site CV. 
