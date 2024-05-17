---
title: "Personnalisations du catalogue Primo de l'Université de Genève"
date: 2023-07-04
weight: 1
descr: Développement de modules JavaScript/Angular personnalisés pour modifier l'affichage du catalogue public Alma/Primo de l'UNIGE.
project_image: "/images/illustrations/unige-unimail-bytguignard.jpg"
project_image_caption: "Bibliothèque Uni Mail, Université de Genève"
year: Depuis 2023
client: Université de Genève
client_url: "https://www.unige.ch/biblio/"
client_logo: "/images/clients/unige.png"
keywords: 
 - Développement web
 - Programmation JavaScript
 - Programmation AngularJS
 - Documentation
 - Portail découverte
lang: Français
lang-iso: fr
ref: unige-primo
---

La [bibliothèque de l'Université de Genève](https://www.unige.ch/biblio/fr) fait partie du réseau national de bibliothèques SLSP,
réunies dans le catalogue collectif [swisscovery](https://swisscovery.slsp.ch). Les membres de SLSP utilisent la plateforme de services de bibliothèque
ExLibris Alma, associée de son portail de découverte Primo (catalogue public). La configuration de base du logiciel Primo est partagée entre
les membres de SLSP (network package), à laquelle s'ajoute des personnalisations locales en fonction des besoins des bibliothèques.

Mon rôle a consisté à programmer et tester plusieurs de ces développements locaux, notamment
 
* Modification du formulaire de prêt inter-bibliothèque et demande de numérisation pour qu'il soit compatible avec les paramètres openURL
* Adaptation d'un module pour distinguer les emplacements en libre-accès des réserves
* Adaptation d'un module pour afficher des liens d'autorité via le service [Metagrid](https://metagrid.ch)
* Diverses modifications d'affichage

Ces personnalisations ont été réalisées dans un [environment de développement local](https://github.com/ExLibrisGroup/primo-explore-devenv),
avant d'être testées dans une instance sandbox d'Alma/Primo puis déployées en production.