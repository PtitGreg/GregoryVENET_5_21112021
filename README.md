# Projet 5 de la formation Dev web Openclassrooms

[Page disponible sur GitHub Pages](https://ptitgreg.github.io/GregoryVENET_5_21112021/)

## Scénario
Vous êtes en poste dans une agence de développement web depuis quelques semaines maintenant. Après avoir réalisé avec succès l’intégration de quelques sites web (HTML/CSS), on vous confie une nouvelle mission.

Votre client est Kanap, une marque de canapés qui vend ses produits depuis sa boutique exclusivement. Aujourd’hui, celle-ci souhaiterait avoir une plateforme de e-commerce en plus de sa boutique physique pour vendre ses produits sur Internet.

<p align="center">
 <img src="https://user.oc-static.com/upload/2021/09/29/16329291678171_image2.png" width="200px"/>
</p>
<p align="center">Logo de Kanap</p>

 

Dans le cadre de cette mission, vous travaillez avec une équipe constituée de :

* Corinne, le CTO de l’agence ;
* Frank, le développeur front-end qui s’est chargé d’intégrer la maquette statique du site ;
* Bilal, le développeur back-end qui implémente l’API à laquelle est connecté le front-end.

Corinne vous envoie un e-mail pour vous briefer sur la mission :

> De : Corinne
> À : Vous
> Objet : Site e-commerce Kanap 
>
> Hello !
>
> Comme on en a discuté hier, voici les informations pour que tu puisses démarrer > l’implémentation du site de Kanap de manière dynamique. 
>
> Voici les différentes tâches que tu vas devoir mener à bien :
>
> Unifier les travaux déjà réalisés par l’équipe en intégrant dynamiquement les > > éléments de l’API dans les différentes pages web avec JavaScript. Le code du > front-end et de l’API est disponible sur ce [repo](https://github.com/OpenClassrooms-Student-Center/P5-Dev-Web-Kanap).
> Mettre en place un plan de test d’acceptation à partir de ce [template](https://s3.eu-west-1.amazonaws.com/course.oc-static.com/projects/DWJ_FR_P5/DW+P5+-+Modele+plan+tests+acceptation.xlsx) que nous > avons pour habitude d’utiliser.
> Pour plus de précisions, voici les [spécifications techniques et fonctionnelles](https://s3.eu-west-1.amazonaws.com/course.oc-static.com/projects/DWJ_FR_P5/DW+P5+-+Specifications+fonctionnelles.pdf) > du projet. Tu pourras y trouver tous les détails de celui-ci, les attentes pour > chaque page du site web et les détails de l’API. 
>
> N'hésite pas à venir me voir si tu as la moindre question, ma porte est toujours > ouverte.
>
> Bonne journée,
>
> Corinne
>

Un peu plus tard, Frank vous envoie un e-mail pour vous apporter quelques précisions complémentaires sur son travail :

> De : Frank
> À : Vous
> Objet Maquettes statiques du site de Kanap 
>
> Salut,
>
> Visiblement c’est le moment pour toi de rejoindre le projet ! Je viens donc te > donner quelques informations sur la partie que j’ai pu réaliser, pour t’aider lors > de ton développement.
>
> 4 pages ont été mises en place : page d’accueil, page Produit, page Panier et la > page Confirmation. Sur l’ensemble des pages, toutes les parties statiques sont > en place, elles sont donc prêtes à recevoir le contenu dynamique.
>
> Aussi, sur chaque page, un exemple de la partie dynamique est systématiquement > donné ; de cette façon, tu n’as pas à t’occuper de la mise en place de la > structure HTML ni du style CSS, tout est déjà fait. Tu n’as plus qu’à t’occuper > d’intégrer ces éléments dynamiquement grâce à JS et l’API.
>
> Enfin, dans le code HTML j’ai intégré des “id” dans différentes balises, cela > devrait t’aider à intégrer les éléments dynamiques. Avec tout ça, normalement tu > n’auras pas besoin de toucher au code HTML/CSS.
>
> Bon développement !
>
> Frank
>

Ça y est, vous avez toutes les informations pour démarrer votre projet. Bon courage !

Pour ce projet, vous ne pouvez utiliser que du code JavaScript pur. L'utilisation de tout framework ou librairie JavaScript (React, Angular, Vue ou jQuery, par exemple) est interdite pour ce projet.

Pour vous aider à réaliser ce projet, voici un exemple de découpage des étapes à suivre. Vous y trouverez des conseils pour chaque étape, ainsi que sur l’utilisation des ressources pour ce projet.

# Compétences évaluées
* Gérer des événements JavaScript
* Valider des données issues de sources externes
* Créer un plan de test pour une application
* Interagir avec un web service avec JavaScript
