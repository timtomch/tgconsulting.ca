---
title: "Page1+ implementation"
date: 2022-06-29
weight: 1
descr: Procurement, implementation and data migration support for ExLibris Alma as a next generation library services platform for 18 college libraries in Ontario.
project_image: "/images/illustrations/georgian-library-2-bytguignard.jpg"
project_image_caption: "Georgian College Library in Barrie, Ontario"
year: 2018 - 2022
client: Ontario Colleges Library Service OCLS
client_url: "https://ocls.ca"
client_logo: 
keywords: 
 - Competitive procurement
 - Project management
 - Financial planning
 - Metadata migration
 - Automated data deduplication and cleanup
 - Python programming
 - Implementation support
 - System integration support
lang: English
ref: p1p
---

## About Page1+

<a href="https://www.page1plus.ca/">Page1+</a> is the next-generation library services platform for 18 Ontario colleges. 
Launched in July 2022, it utilizes ExLibris Alma
and is the result of an extensive collaborative process by the Ontario college libararies and the Ontario Colleges Library Service
(OCLS) to select and implement a new library system. It involved selecting a new vendor and software and migrating bibliographic,
holdings and patron data from a variety of existing systems:

* 14 colleges migrating from SirsiDynix Symphony
* 2 colleges migrating from Mandarin M5 and Oasis
* 1 college migrating from Evergreen
* 1 college migrating from two separate instances Surpass Centriva
* The Colleges Union Catalogue migrating from SirsiDynix Symphony

It also involved integrating with various Student Information Systems, Learning Management Systems, reading list and library scheduling 
software, Single-Sign-On infrastructure, etc. as well as coordinating policies across participating colleges.

## Procurement phase

I coordinated the competitive procurement process of a library services platform solution for OCLS and the 18 colleges involved 
in the project. This included

* Gathering technical and functional requirements across all stakeholders
* Coordinating the preparation and publication of a Request for Proposals (RFP) document
* Establishing objective decicision criteria
* Coordinating the evaluation of RFP responses by a team of over 20 subject matter experts
* Participation in the evaluation and award of ExLibris Alma as successful proponent
* Participation in contract negotiation

The RFP was <a href="https://www.ocls.ca/news/ontario-college-libraries-release-rfp-collaborative-library-services-platform">
published in September 2020</a> and 
<a href="https://www.ocls.ca/news/ocls-signs-agreement-ex-libris-behalf-college-libraries-participating-clsp-project">
publicly awarded in September 2021.</a>

## Implementation phase

Once the successful proponent was selected, I continued to offer technical expertise to the project's implementation steering
committee, as well as data migration support for some colleges.

As a consortial implementation, the colleges participating in Page1+ share bibliographic records within their "Network Zone".
Although setting up the Network Zone was greatly simplified thanks to the migration of the Colleges Union Catalogue, this step
still required deduplicating and mass-processing records. While most of this work was done by OCLS and ExLibris, I produced
migration scripts to prepare and deduplicate data migrated from systems not natively supported by the vendor's migration procedures.
This involved notably

* SQL scripts to export Evergreen data to MARC and CSV format
* Python scripts for automatic enrichment of MARC records exported from Surpass Centriva
* OpenRefine operations and Python scripts to deduplicate MARC records exported from multiple ILS instances
* Python scripts for cleaning up acquisition metadata

### Collaboration

The preparation of the RFP was done in collaboration with Liana Giovando of <a href="http://pertinence.ca/index.html">Pertinence.ca</a>,
who subsequently took over the project management role for the implementation phase.