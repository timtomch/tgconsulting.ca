---
title: "Primo custom developments for the University of Geneva"
date: 2023-07-04
weight: 2
descr: Development of custom Alma/Primo modules for the University of Geneva library catalogue.
project_image: "/images/illustrations/ge-conservatory-library-bytguignard.jpg"
project_image_caption: "Library of the City of Geneva Conservatory and Botanical Gardens"
year: 2023
client: Université de Genève
client_url: "https://www.unige.ch/biblio/"
client_logo: "/images/clients/unige.png"
keywords: 
 - Web Development
 - JavaScript
 - AngularJS
 - Discovery portal
 - Documentation
lang: English
lang-iso: en
ref: rnv-idref
secret: true
---

The [University of Geneva library](https://www.unige.ch/biblio/en) is a member of the Swiss national library network SLSP
and [swisscovery](https://swisscovery.slsp.ch) union catalogue. SLSP members are using the ExLibris Alma library services platform
and Primo discovery layer (public catalogue). While SLSP members share a common look and feel and configuration on their
Primo instances (network package), they are also able to alter their catalogue locally to fit their needs.

My role was in developing and testing several such local changes, including

* Modifying the inter library loan and digitization request formular to support openURL parameters
* Adapting a module to visually distinguish open stacks from reserve locations
* Adapting a module to display linked authority data through the [Metagrid](https://metagrid.ch) service
* Various display customizations

These were programmed using [a local development environment](https://github.com/ExLibrisGroup/primo-explore-devenv),
before being tested in a sandbox and deployed to production.