---
title: "Conversion d’autorités de classification RERO vers Renouvaud"
date: 2022-08-25
weight: 2
descr: Transformation de notices d’autorité de classification pour l'enrichissement du catalogue Renouvaud.
project_image: "/images/illustrations/lausanne-riponne-bytguignard.jpg"
project_image_caption: "Bibliothèque Cantonale et Universitaire Riponne, Palais de Rumine, Lausanne"
year: 2020
client: Coordination Renouvaud
client_url: "https://www.bcu-lausanne.ch/mandats/"
client_logo: "/images/clients/RenouVaud-logo-2016-web.png"
keywords: 
 - Registre d'autorité
 - Classification matières
 - Migration de données
 - Programmation Python
lang: Français
lang-iso: fr
ref: rnv-map
---

[Le réseau Renouvaud](https://www.bcu-lausanne.ch/mandats/) regroupe [139 bibliothèques](https://map.renouvaud.ch/) 
universitaires, patrimoniales, de lecture publique et scolaires dans le canton de Vaud, en Suisse. 
Avant son lancement en 2016, les bibliothèques vaudoises faisaient partie du réseau des bibliothèques de Suisse
occidentale ([RERO](https://www.rero.ch)).

Ce projet a consisté en la migration automatique des autorités de classification de certaines collections du site
Riponne de la Bibliothèque Cantonale et Universitaire de Lausanne (BCUL) qui n'avaient pas été traitées lors du passage de RERO à
Renouvaud. Sur la base d'un mapping fourni par la BCUL, mon travail a consisté à écrire une série de scripts de conversion
(utilisant le language Python) pour appliquer les corrections nécessaires aux 50,000 notices concernées.