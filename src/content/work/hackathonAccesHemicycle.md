---
title: Accès Hémicycle Hackathon 
publishDate: 2025-01-9 00:00:00
img: /assets/projet/HackathonHemicycle/accueilHackathon.png
img_alt: Accueil app Gestion Astreinte
description: |
  Sur la période du 6 au 9 janvier 2025, réaliser à travers un hackathon, une application pour l'accès des députés dans l'Hémicycle.
tags:
  - Design
  - Dev
  - User Testing
---

## Contexte

> Pour enforcer la sécurité des députés siégeant à l'Assemblée nationale, il a été décidé de fournir un nouveau badge contenant un QR Code. Un sas de sécurité aux endroits qui ne sont accessibles qu'aux députés contrôlera l'ensemble des accès via leur QR Code personnel. Et je suis chargé de créer une application permettant de scanner ces QR Code afin de pouvoir valider l'entrée dans l'hémicycle en vérifiant les informations incluses.

## Introduction

Cette application a été réalisé avec la technologie windows form et le langage C# avec l'inclusion du framework .Net. Ce choix c'est fait sur la base de mes facilités, en effet, pour réaliser ce projet dans un temps très court, prendre une technologie dont nous sommes habitués facilite la réalisation. De plus, l'application avec C# contrairement à du développement mobile, peut me permettre plus facilement d'intégrer un lecteur de Qr Code via une scanette.
Il y a également sur un serveur, une base de données avec les informations  officiel des députés, récupérer sur le site officiel de l'Assemblée.

Ce projet qui s'est réalisé sur la période du 6 au 9 janvier 2025 avait pour but, dans le cadre d'un hackathon, nous tester à créer un projet sur un temps beaucoup plus court que ce que nous pouvions avoir pour habitude.

## Objectif principal de l'application

Pour répondre à la demande fictive, l'application devait pouvoir scanner les QR code de type VCard présent sur les cartes des députés, dont les informations étaient incluses. On arrive donc sur une première page, dont la charte graphique a été pensé pour ressembler à un site officiel de l'Assemblée Nationale. On peut donc scanner dès l'accueil de l'application.
![](/assets/projet/HackathonHemicycle/accueilHackathon.png "Accueil")
Et voici le résultat une fois le QR Code scanné avec le lancement de la caméra
![](/assets/projet/HackathonHemicycle/accesParQrCode.png "Accès par Qr Code")
On retrouve les informations du députés prouvant son identité, et son entrée est accepté et inscrite dans la base de données.

## Accès dérivé à l'Hémicycle

Accéder via Qr Code à l'Hémicycle est bien ! Cependant, cela ne nous garanti pas que le Député est un problème avec sa carte (perte de la carte, Qr Code abimé, ...). C'est pour cela qu'une autre possibilité a été posé, proposant ainsi, avec un accès par connection, à une des pages de l'application qui affiche la liste complète des députés avec une pagination, une barre de recherche afin de pouvoir vérifier la présence de la personne dans la liste, et l'affichage possible de la photo du député pour vérifier les informations de la personne par rapport à sa carté d'identité ou autres. 
![](/assets/projet/HackathonHemicycle/deputesListe.png "Liste des députés")
![](/assets/projet/HackathonHemicycle/affichageDepute.png "Photo du député sélectionné")

Cela nous permet de vérifier les informations de la personne, puis en double cliquant, nous pouvons laisser l'accès à l'hémicycle à la personne avec l'ajout de la date et heure d'entrée à l'Hémicycle, mais également dans les logs afin de stipuler que cette personne n'est pas entré avec le standard voulu. Cela pourrait servir de prévention et d'avertissement en cas de récidive. 

Ci-joint le lien de la vidéo youtube en non répertorié pour le rendu et le fonctionnement du projet : <a href="https://www.youtube.com/watch?v=iB9kb0mmhQk ">Accès Hémicycle</a>

### Conclusion 

Ce projet réalisé pendant les cours a été très enrichissante, d'un point de vue du temps limite de réalisation. Cela nous amenait à faire des choix stratégiques pour avoir un bon fonctionnement de celui-ci. 

### Outils et Langages utilisés

- Visual Studio
- C#
- .Net
