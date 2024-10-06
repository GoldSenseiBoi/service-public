# Projet : Devoir à la maison à rendre sur Heroku ou Alwaysdata de Ibrahima Sory DIALLO

## Description
Ce projet a pour objectif de reproduire une page HTML/CSS en respectant des consignes spécifiques, notamment l'usage des balises sémantiques, l'utilisation de Bootstrap pour la mise en page, et l'implémentation de la responsivité. Le projet est déployé sur une plateforme d'hébergement comme Heroku ou Alwaysdata.

## Contenu du projet
Le projet contient les fichiers suivants :
- `index.html` : le fichier HTML principal qui structure la page.
- `index.css` : le fichier CSS qui contient les styles personnalisés.
- Répertoire `img` : ce répertoire contient les images utilisées dans le projet.

## Détails de l'implémentation

1. **Balises sémantiques :**
   - J'ai utilisé des balises telles que `<section>`, `<article>`, `<main>`, et `<aside>` pour structurer le contenu de manière sémantique. Cela améliore l'accessibilité et le référencement de la page.

2. **Mise en page :**
   - La mise en page est construite à l'aide du système de grille de Bootstrap. Chaque section de la page est alignée de manière fluide en utilisant les classes de Bootstrap pour garantir une structure responsive.
   - Les articles et les parties latérales ont des largeurs régulières (égale, double ou triple) comme demandé. Cela a été fait en utilisant les classes `col-*` de Bootstrap.

3. **Responsivité :**
   - La page est responsive grâce à l'utilisation du framework Bootstrap et de media queries dans le fichier CSS. J'ai testé la page sur différentes résolutions, y compris les versions mobiles.
   - Une version spécifique pour mobile est incluse, avec des ajustements sur la taille des éléments et la disposition des sections.

4. **Menu :**
   - Le menu principal est entièrement géré en CSS. Il utilise les fonctionnalités de survol pour faire apparaître des sous-menus lorsque l'utilisateur passe la souris sur la barre de navigation.

5. **Hébergement :**
   - Le projet peut être déployé sur Heroku ou Alwaysdata, en suivant les instructions pour ces plateformes.

## Justification du code
- **Grille Bootstrap** : La mise en page principale est réalisée à l'aide d'un Grid Layout de Bootstrap avec des colonnes ajustées pour s'adapter aux différentes tailles d'écran.
- **Balises sémantiques** : J'ai utilisé des balises HTML5 sémantiques pour garantir que la structure de la page soit claire et conforme aux standards modernes du web.

## Instructions pour exécuter le projet
1. Cloner le dépôt ou télécharger le projet.
2. Ouvrir le fichier `index.html` dans un navigateur pour visualiser la page.
3. Pour déployer sur Heroku ou Alwaysdata, suivez les instructions de déploiement spécifiques à ces plateformes.
"""

# Write the README file to the project directory
readme_file_path = os.path.join(project_dir, 'README.md')
with open(readme_file_path, 'w') as readme_file:
    readme_file.write(readme_content)

