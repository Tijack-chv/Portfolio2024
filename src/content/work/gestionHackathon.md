---
title: Gestion Hackathon
publishDate: 2024-11-15 00:00:00
img: /assets/projet/captureAP3GestionHackathons/mis/homeStatistiques.png
img_alt: Accueil app Gestion Hackathon
description: |
  Projet Etudes.
  Développer une application qui permet de gérer la gestion des Hackathons.
tags:
  - Design
  - Dev
  - User Testing
  - Backend
---

## Contexte 

> Devant l'engouement des hackathons en France, répondant à une volonté de développer toujours davantage le numérique au service de la société, il y a 2 ans, a été créée une start-up Hackat'Innov qui a pour but de simplifier la gestion de l'organisation d'Hackathons. Et cette jeune entreprise souhaite développer davantage ce réseau et proposer d'autres fonctionnalités.

## Introduction 

Cette application a été réalisé avec la technologie windows form et le langage C# avec l'inclusion du framework .Net. Ce choix c'est fait puisque l'objectif était de réaliser un site web avec Laravel et une application lourde avec C#, en équipe de deux. On a donc fait le choix de la technologie entre nous en fonction de nos facilités. 
Nous avons également un serveur de base de données avec l'ensemble des données nécessitant au fonctionnement du projet. 
Ce projet c'est réalisé sur la période du 6 septembre au 15 novembre 2024.

## Connexion 

Pour accéder à l'application, il fallait se connecter au préalable. A l'éxécution de l'application, la page de connexion ci-dessous s'affichait.
    ![](/assets/projet/captureAP3GestionHackathons/mis/pageConnexion.png "Page de connexion")<br>
Seule une personne ayant les droits administrateur pouvait se connecter. De plus, la connexion nécessitait, si accepté, une double authentification via une connexion OTP. Le code est généré via un Qr Code qui est proposé dans l'application, dans les paramètres. Et une fois scanné dans une application tel que Google Auth ou Aegis, on a un code qui se regénère toutes les 10-15 secondes. <br>
![](/assets/projet/captureAP3GestionHackathons/mis/ConnexionOTP.png "Connexion OTP")
![](/assets/projet/captureAP3GestionHackathons/mis/ParamètresSecuritéSuppEtMenu.png "")

## Accueil

Ensuite, nous arrivions dans l'accueil de l'application avec l'affichage des statistiques importantes de l'application. Ces statistiques faisant appel aux données de la base de données.
![](/assets/projet/captureAP3GestionHackathons/mis/homeStatistiques.png "Accueil Application avec Statistiques")
Une barre de menu ouvrable à partir du bouton de menu affiche la liste des pages disponibles de l'application
![](/assets/projet/captureAP3GestionHackathons/mis/menuBar.png "Barre de menu")

## Hackathon

Voici la page d'accès pour les Hackathons. On peut retrouver dès l'ouverture, la liste des Hackathons dans une table. On peut à partir de la liste ou de la barre de menu, ajouter ou modifier un hackathon. 

![](/assets/projet/captureAP3GestionHackathons/mis/Hackathons.png "Listes des Hackathons")
![](/assets/projet/captureAP3GestionHackathons/mis/HackathonsModification.png "Modification Hackathon")

Et nous avons également un sous menu au click droit de la table, qui nous permet également de voir les équipes inclus dans l'hackathon sélectionner, voir l'affiche de l'hackathon ou de voir le jury de l'hackathon.

![](/assets/projet/captureAP3GestionHackathons/mis/SousMenuHackathons.png "SousMenuHackathons")

Si jamais aucun groupe de jury n'a été choisi pour l'hackathon, et que celui-ci est à une date futur, on peut ajouter le groupe du jury.
Ce jury doit être constitué de minimum de 5 personnes. <br>
![](/assets/projet/captureAP3GestionHackathons/mis/choixJury.png "Ajout du jury dans un hackathon")

## Equipe / Membre

Voici la page pour la gestion des membres et des équipes. Nous pouvons ajouter / modifier les membres ou les équipes, et inclure des membres dans une équipe. 
![](/assets/projet/captureAP3GestionHackathons/mis/MembreEquipe.png "Liste Membres Equipes")

## Jury

Pour la page Jury,, comme pour les équipes et les membres, nous pouvons ajouter ou modifier un membre du jury, le visuel se place en fonction des choix, et on peut également afficher les hackathons où le jury est présent.
![](/assets/projet/captureAP3GestionHackathons/mis/JurysSousMenuEtAjoutModif.png "Liste des Jurys, affichage ajout/modif et sous menu")

## Paramètre

Cette page a déjà été en partie présenter. Celle-ci permet d'activer ou non la connexion OTP, on peut également l'enlever. La possiblité de modifier son mot de passe est également présente. 
![](/assets/projet/captureAP3GestionHackathons/mis/ParamètresSecuritéSuppEtMenu.png "Paramètre OTP")

## Information

Cette page correspond à la page de log où certaines intéractions de l'application conduise à la création de données de log qui sont visibles sur cette page. On peut également savoir qui est responsable de cette donnée et pourquoi. 
![](/assets/projet/captureAP3GestionHackathons/mis/InformationsAvecMessageDoubleClick.png "Log affichage")

## Conclusion

Ce projet réalisé pendant les cours et pendant les heures extra-scolaires m'a permis de pouvoir réaliser un projet étudiant pour la première fois en collaboration. Donc avec deux applications dont les objectifs étaient différents, mais avec une intéraction avec la base de données qui était pareil. Cela a été un projet très enrichissant d'un point de vue de méthodologie et d'expérience dans la technologie réalisé.

### Outils et Langages utilisés

- Visual Studio
- C#
- .Net