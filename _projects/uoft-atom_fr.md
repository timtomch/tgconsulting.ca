---
title: "Descriptions de fonds d'archives accessibles pour AtoM"
date: 2024-04-17
weight: 1
descr: Amélioration de l'accessibilité universelle de descriptions de fonds au format PDF générés depuis les notices EAD pour les archives de l'Université de Toronto.
project_image: "/images/illustrations/uoft-robarts-library-bytguignard.jpg"
project_image_caption: "Bibliothèque Robarts, Université de Toronto"
year: 2023 - 2024
client: Bibliothèques de l'Université de Toronto
client_url: "https://onesearch.library.utoronto.ca/information-technology-services-its"
client_logo: "/images/clients/utl-logo.svg"
keywords: 
 - Access to Memory (AtoM)
 - XML
 - EAD
 - XSLT
 - Formatting Objects (FO)
 - Accessibilité universelle
lang: Français
lang-iso: fr
ref: uoft-atom
---

Les fonds d'archives de l'Université de Toronto et de ses collèges affiliés sont présentés sur le portail
[Discover Archives](https://discoverarchives.library.utoronto.ca/index.php/). Ce dernier utilise le logiciel
[Access to Memory (AtoM)](https://www.accesstomemory.org/fr/) hébergé par les services informatiques des bibliothèques.

AtoM offre un mécanisme pour générer automatiquement des descriptifs de fonds au format PDF. Cette opération
utilise les transformations XSL (XSLT) pour convertir les métadonnées EAD vers XML-FO (Formatting Objects) et enfin PDF.
Cependant, les fichiers qui en résultent ne répondent souvent pas aux standards d'accessibilité universelle en raison de métadonnées manquantes.

Mon travail a consisté à modifier les transformations XSL pour améliorer l'accessibilité universelle des descriptifs de fonds, ainsi que
d'apporter d'autres améliorations visuelles, notamment

- Ajout de balises permettant la navigation de la structure du document (en-têtes, tables, etc.)
- Ajout de métadonnées permettant l'utilisation de technologies d'accessibilité universelle (lecture d'écran)
- Identification des éléments décoratifs (logos) pour améliorer la navigation
- Ajout d'hyperliens dans les descriptions
- Résolution de problèmes de formatage comme débordement de texte, étiquettes répétitives, sauts de page, etc.
- Reconnaissance limitée de la syntaxe Markdown dans les champs de description
- Changement de la police par défaut et autres améliorations visuelles
- Mise en place d'une stratégie permettant d'insérer un logo différent pour chaque fonds d'archive

Les améliorations à l'accessibilité universelle qui découlent de ce projet sont opérationnelles depuis février 2025 et
ont été intégrées au code AtoM afin de bénéficier à l'ensemble de la communauté.

Ce projet a été financé par la bourse d'innovation 2023 du Bibiliothécaire en chef de l'Université de Toronto [“Committed to Web Accessible Archival Description Discovery”](https://docs.google.com/presentation/d/1nY5ZGEWSZR_9V4LBIQBki-gbLPsEhtLsF0f4zh4e858/edit#slide=id.p1).