---
title: "Implémentation de Page1+"
date: 2022-06-29
weight: 1
descr: Sélection, implémentation et soutien à la migration de données pour la mise en place du logiciel ExLibris Alma dans 18 bibliothèques collégiales en Ontario.
project_image: "/images/illustrations/georgian-library-2-bytguignard.jpg"
project_image_caption: "Bibliothèque du Georgian College à Barrie, Ontario"
year: 2018 - 2022
client: Ontario Colleges Library Service OCLS
client_url: "https://ocls.ca"
client_logo: 
keywords: 
 - Appel d'offre
 - Planification financière
 - Migration de métadonnées
 - Déduplification et nettoyage de données
 - Programmation Python
 - Soutien à l'implementation
 - Soutien à l'intégration de systèmes
lang: Français
ref: p1p
---

## Au sujet de Page1+

<a href="https://www.page1plus.ca/">Page1+</a> est la plateforme de servivces de bibliothèque de nouvelle génération
partagée par 18 collèges en Ontario. Lancée en juillet 2022, elle utilise le logiciel Alma d'ExLibris et est le résultat
d'une étroite collaboration entre les bibliothèques collégiales et le Ontario Colleges Library Service (OCLS). Ceux-ci
ont combiné leurs forces pour sélectionner un nouveau logiciel de manière concurentielle, avant d'y migrer leurs données
provenant de plusieurs systèmes pré-existants:

* SirsiDynix Symphony (14 collèges + 1 catalogue collectif)
* Mandarin M5 et Oasis (2 collèges)
* Evergreen (1 collège)
* Deux instances distinctes de Surpass Centriva (1 collège)

Ce projet a également nécessité l'intégration du nouveau logiciel avec plusieurs systèmes de gestion de l'enseignement et des
étudiants, logiciels de listes de lecture, planification horaire, infrastructure d'identification unique (Single-Sign-On), etc.
ainsi que la coordination de pratiques bibliothéconomiques des collèges participants.

## Phase d'acquisition

Durant cette première phase, mon rôle était de coordonner le processus d'acquisition par appel d'offre. Cela consistait notamment
des opérations suivantes:

* Récolte des exigences techiques et fonctionnelles auprès de toutes les parties prenantes
* Coordination et préparation d'un appel d'offre formel (Request for Proposals, RFP)
* Mise en place de critères de sélection objectifs
* Coordination de l'évaluation des offres reçues par une équipe de plus de 20 experts
* Participation au processus d'évaluation et décision ayant mené à la sélection d'ExLibris Alma
* Participation à la négociation contractuelle

L'appel d'offre a été <a href="https://www.ocls.ca/news/ontario-college-libraries-release-rfp-collaborative-library-services-platform">
publié en septembre 2020</a> et la proposition ayant remporté le contrat 
<a href="https://www.ocls.ca/news/ocls-signs-agreement-ex-libris-behalf-college-libraries-participating-clsp-project">
a été rendue publique en septembre 2021.</a>

## Phase d'implementation

Une fois faite la sélection d'un prestataire, mon rôle est devenu plus technique. J'ai continué d'offrir une expertise technique
au comité directeur d'implémentation, en plus d'aider certains collèges dans la migration de leurs métadonnées.

En tant qu'implémentation consoriale d'Alma, les collèges qui participent à Page1+ partage leurs données bibliographiques au sein
d'une "Network Zone". Bien que la mise en place de la NZ a été simplifée par la migration du catalogue collectif des collèges,
la déduplication et modification en masse de notices a toutefois été nécessaire pour mener à bien ce travail. La majeure partie
de ce travail a été réalisée par OCLS et ExLibris, j'ai pour ma part mis au point des scripts de migration pour préparer les données provenant des logiciels qui n'étaient pas nativement supportés par les routines de migration d'ExLibris, notamment

* Scripts d'export de données au format MARC et CSV (SQL)
* Routines d'enrichissement automatique de données (Python)
* Routines de dédoublonnage de données provenant de plusieurs instances (Python, OpenRefine)
* Nettoyage de données d'acquisition (Python)

### Collaboration

La préparation de l'appel d'offre a été faite en collaboration avec Liana Giovando de <a href="http://pertinence.ca/index.html">Pertinence.ca</a>,
qui a par la suite pris le rôle de gestionnaire de projet pour la phase d'implémentation.