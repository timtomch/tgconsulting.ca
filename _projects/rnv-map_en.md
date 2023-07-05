---
title: "Classification authorities conversion for Renouvaud"
date: 2022-08-25
weight: 3
descr: Post-migration automated conversion of classification authority records for a library in Western Switzerland.
project_image: "/images/illustrations/lausanne-riponne-bytguignard.jpg"
project_image_caption: "Bibliothèque Cantonale et Universitaire Riponne, Palais de Rumine, Lausanne"
year: 2020
client: Coordination Renouvaud
client_url: "https://www.bcu-lausanne.ch/mandats/"
client_logo: "/images/clients/RenouVaud-logo-2016-web.png"
keywords: 
 - Authorities file
 - Subject classification
 - Data migration
 - Python programming
lang: English
lang-iso: en
ref: rnv-map
---

[The Renouvaud network](https://www.bcu-lausanne.ch/mandats/) includes 
[139 academic, research, school and public libraries](https://map.renouvaud.ch/) in Vaud, Switzerland. 
Before it went live in 2016, its member libraries belonged to the Western Switzerland Library Network
[RERO](https://www.rero.ch).

I helped them autmate the migration of classification authorities for several collections at the
Bibliothèque Cantonale et Universitaire de Lausanne (BCUL) Riponne site that had not been processed during the initial
shift from RERO to Renouvaud. Based on the mapping provided by BCUL, I created a series of conversion scripts in
Python to apply the necessary changes to the 50,000 records involved.