---
title: "Babelio user reviews integration on Primo"
date: 2024-11-22
weight: 1
descr: Development of a custom Primo module for integrating user reviews from the Babelio platform for a public library network.
project_image: "/images/illustrations/orbe-bibliotheque-bytguignard.jpg"
project_image_caption: "School and public library in Orbe, Switzerland"
year: 2024
client: Coordination Renouvaud
client_url: "https://www.bcu-lausanne.ch/en/reseau-renouvaud/"
client_logo: "/images/clients/RenouVaud-logo-2016-web.png"
keywords: 
 - Web Development
 - JavaScript
 - AngularJS
 - PHP
 - Discovery portal
 - Documentation
lang: English
lang-iso: en
ref: rnv-babelio
---

[The Renouvaud network](https://www.bcu-lausanne.ch/en/reseau-renouvaud/) includes 
[over 150 academic, research, school and public libraries](https://map.renouvaud.ch/) in Vaud, Switzerland. Their public catalogue
runs on shared instances of the ExLibris Alma/Primo library services platform.

[Babelio](https://www.babelio.com/) is a platform used by 1.8 milion users to share reader reviews, ratings and citations.
This data can be used to enrich library catalogues through the [Babelthèque](https://www.babelio.com/article/2065/babeltheque)
service.

I developed a custom Primo module for integrating data from the Babelio API on the Renouvaud catalogue for public and school libraries.
The resulting code is [freely available on GitHub](https://github.com/timtomch/rnv-babelio-primo).

The module was developed using [a local development environment](https://github.com/ExLibrisGroup/primo-explore-devenv),
before being tested in a sandbox and deployed to production.