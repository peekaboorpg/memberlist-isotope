# Liste des membres avec filtres, tri et barre de recherche, sans reload de page v.1.0
Ce script vous permet de __filtrer la liste des membres par groupe, et de la trier par dernière connexion, pseudo, date d’inscription et champ Humeur__ (personnellement, je renomme le champ Humeur en champ Faceclaim, ce qui me permet donc de trier par faceclaim, mais vous pouvez mettre ce que vous voulez !). Vous avez également à disposition __une barre de recherche par pseudo__.

Le script utilise le plugin [isotope.js](https://isotope.metafizzy.co/), qui permet de faire tout cela __sans aucun rechargement de page__, contrairement au comportement natif de forumactif. Malgré tout, mon code conserve __une pagination réglable__, elle aussi sans rechargement.

L’avantage de ce code est aussi de pouvoir __changer le nombre de membres par page sans pour autant impacter le nombre de sujets par page__, contrairement au fonctionnement natif de forumactif.

Live preview : *https://rheah.forumactif.com/memberlist*

## À savoir
* Le script est techniquement compatible avec __toutes les versions de forum__.
  * Néanmoins, si vous utilisez le <ins>thème par défaut</ins> de phpBB2, phpBB3, PunBB ou ModernBB, il faut bien cibler le `<tbody>` qui entoure les blocs membres, en indiquant `.CLASS_DE_VOTRE_CHOIX tbody` sur la variable `memberList`.
  * Néanmoins encore, si vous utilisez le <ins>thème par défaut</ins> d’Invision, il faut ajouter `<a href="{memberrow.U_VIEWPROFILE}" class="nom">{memberrow.USERNAME}</a>` au sein de la div `<div id="pm{memberrow.ROW_NUMBER}">`.
* A l’arrivée sur /memberlist, cette liste des membres est toujours __triée par dernière connexion décroissante__.
* La direction est __croissante par défaut pour tous les autres tris__.
* Deux boutons vous permettent ensuite de __changer la direction du tri__ (croissant ↔ décroissant).
* La mise en place de ce script __implique la modification du template memberlist_body__, notamment l’ajout de la structure html pour les différents boutons de filtrage/tri, ainsi que de class sur les champs utilisés pour le tri dans chaque bloc membre.
* Pour mettre en place le filtre sur les groupes, __vous devrez indiquer la couleur de pseudo pour chaque groupe dans le script__.
* Note : le script __met quelque temps à afficher les blocs membres__, c’est pourquoi j’ai ajouté une petite mention « Chargement… » qui s’affiche en attendant que les blocs membres soient prêts.

# Installation
## Modifier le template memberlist_body
Texte

## Ajout du script
Texte

# Autres modifications possibles
Texte

# Crédits
Texte
