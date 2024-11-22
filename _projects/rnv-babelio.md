---
title: "Intégration de Babelio dans le catalogue Renouvaud"
date: 2024-11-22
weight: 1
descr: Développement d'un module Primo pour l'intégration des avis de lecture provenant de la plateforme Babelio sur le catalogue du réseau vaudois de bibliothèques.
project_image: "/images/illustrations/orbe-bibliothèque-bytguignard.jpg"
project_image_caption: "Bibliothèque publique et scolaire d'Orbe"
year: 2024
client: Coordination Renouvaud
client_url: "https://www.bcu-lausanne.ch/mandats/"
client_logo: "/images/clients/RenouVaud-logo-2016-web.png"
keywords: 
 - Développement web
 - Programmation JavaScript
 - Programmation AngularJS
 - Programmation PHP
 - Documentation
 - Portail découverte
lang: Français
lang-iso: fr
ref: rnv-babelio
secret: true
---

[Le réseau Renouvaud](https://www.bcu-lausanne.ch/mandats/) regroupe [plus de 150 bibliothèques](https://map.renouvaud.ch/) 
universitaires, patrimoniales, de lecture publique et scolaires dans le canton de Vaud, en Suisse. Leur catalogue public
repose sur des instances partagées du logiciel ExLibris Alma/Primo. 

La [plateforme Babelio](https://www.babelio.com/) réunit avis de lecture, critiques et citations partagées par 1.8 millions
de lectrices et lecteurs. Ces données, enrichies d'extraits, informations biographiques, chroniques de presse et autre
détails, peuvent être intégrées aux catalogues de bibliothèque via le service [Babelthèque](https://www.babelio.com/article/2065/babeltheque).

J'ai travaillé à l'intégration dans Primo des données provenant de l'API Babelio pour les bibliothèques scolaires
et de lecture publique de Renouvaud. Le résultat de ce travail est [librement disponible sur GitHub](https://github.com/timtomch/rnv-babelio-primo).

Ces personnalisations ont été réalisées dans un [environment de développement local](https://github.com/ExLibrisGroup/primo-explore-devenv),
avant d'être testées dans une instance sandbox d'Alma/Primo puis déployées en production.