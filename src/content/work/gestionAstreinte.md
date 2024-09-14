---
title: Gestion Astreinte 
publishDate: 2024-06-30 00:00:00
img: /assets/captureMissionStage/compteRendu2/accueilGestAstNewV2.PNG
img_alt: Accueil app Gestion Astreinte
description: |
  Réaliser des modifications de l'application interne Gestion Astreinte pour le service informatique chez Lactalis.
tags:
  - Design
  - Dev
  - User Testing
---

## Introduction

> Gestion Astreinte est une application interne pour le service informatique chez <a href="https://www.lactalis.com/">Lactalis</a>, permettant de réaliser une gestion de toutes les interventions possibles puis de calculer la récupération lié à l'ensemble des interventions exécutés. 

Cette application a été réalisé, avec le framework Jhypster et avec JAVA/Angular.

Ce projet, qui s'est réalisé pendant une période de stage de 6 semaines, avait pour but d'améliorer cette application sur des implémentations de nouvelles fonctionnalités, sur des corrections de bug, et pour un point de vue personnel, l'enrichissement sur l'apprentissage d'une nouvelle technologie et d'une méthode de travail complétement nouvelle.

Pour regrouper les demandes d'amélioration de l'application, nous utilisions JIRA, système de suivi des bugs et gestion des incidents.
Chaque amélioration de l'application que j'ai pu réaliser vont être présenté par partie ci-dessous.

### Mission 1

La première mission qui m’a été confiée est sur l’application Gestion Astreinte. Afin de permettre au Manager d’avoir une vision très rapide sur les nouvelles Interventions et/ou Récupérations mises à jour, je dois intégrer dans la page principale, l’accès à une sidebar, disponible uniquement par le manager, qui permet de voir toutes les interventions
et récupérations de son équipe. Le nombre d’éléments dans cette sidebar doit être également renseigné sur le bouton d’ouverture de cette sidebar. Ensuite, chaque occurrence doit pouvoir avoir une checkbox afin de pouvoir passer les éléments quand celui -ci a bien été vu par le Manager.
Voici un aperçu de l'ouverture de la sidebar une fois le bouton cliqué par le Manager :
![](/public/assets/captureMissionStage/compteRendu2/sideBarOuvertNewV2.PNG "Sidebar")


### Mission 2 

Cette deuxième mission avait pour but de corriger la visibilité de certaines données confidentielles dont l'accès était possible pour tous. Seulement les membres RH ont le droit de voir cette donnée.
Et voici l'affichage final de ce qui était attendu dans un premier temps pour tous les utilisateurs, et le second pour les membres RH.
![](/public/assets/captureMissionStage/compteRendu3/visibiliteUserDonneeConfidentiel.PNG "Affichage  utilisateur")

![](/public/assets/captureMissionStage/compteRendu3/visibiliteAdminDonneeConfidentiel.PNG "Affichage membre RH")

### Mission 3

Il m'a été demandé ensuite de régler l'erreur sur la prise de récupération. En effet, nous pouvions choisir de prendre une récupération sur un week-end. Il m'a fallu donc enlever la possibilité de choisir un week-end, en passant par l'ajout d'un composant calendrier de <a href="https://primeng.org/">PrimeNg</a>. Il a fallu également reprendre l'impossibilité de prendre une récupération sur une date déjà passé. 
![](/public/assets/captureMissionStage/compteRendu3/popup%20preCalendar.PNG "Affichage Zone de saisie de la date")
![](/public/assets/captureMissionStage/compteRendu3/popup%20Calendar.PNG "Affichage du Calendrier")

### Mission 4 

Après l'avis de certains utilisateurs pouvant utiliser la sidebar réaliser dans la première mission, il m'a été demandé d'améliorer celle-ci. 

En effet, la demande était de pouvoir voir l'ensemble des informations de l'interventions. 
Avec le peu de place que donne une sidebar, l'idée était de placer un bouton d'inspection sur chaque occurence pour qu'une fois le bouton cliquer, une pop-up apparaît avec l'ensemble des données demandés.

Et voici le rendu final de ces améliorations :
![](/public/assets/captureMissionStage/compteRendu3/sidebarComplety.PNG "Affichage Sidebar")
![](/public/assets/captureMissionStage/compteRendu3/dialogueSidebar.PNG "Affichage Pop-up Interventions")

### Mission 5 

Enfin, ma dernière tâche pendant cette période de stage a été de régler un bugfix qui se trouvait sur l'application.
En effet, sur une des pages où est affiché l'ensemble des interventions contenu dans un tableau, celle-ci se subissait pas d'actualisation uniquement quand la ligne du tableau était sélectionnné ailleurs.
Pour se faire, il m'a fallu faire une méthode permettant de desélectionner la ligne du tableau au moment de certaines actions. 

#### Conclusion

Ce projet pendant mon stage m'a permis de découvrir une nouvelles technologies mais surtout, une nouvelle façon de travailler, et de concevoir le métier de développeur. 

#### Outils et Langages utilisés
  Voici la liste des outils utilisés pour ce projet :
- IntelliJ
- NodeJs
- Maven (inclus dans IntelliJ)
- JHypster
- JIRA


Et la liste des langages vu : 
- HTML
- SCSS
- Typescript
- JAVA
- XML