---
title: "AtoM finding aid accessibility remediation"
date: 2024-04-17
weight: 1
descr: Accessibility improvements to PDF finding aids generated from EAD for the University of Toronto Archives.
project_image: "/images/illustrations/uoft-robarts-library-bytguignard.jpg"
project_image_caption: "Robarts Library, University of Toronto"
year: 2023 - 2024
client: University of Toronto Libraries
client_url: "https://onesearch.library.utoronto.ca/information-technology-services-its"
client_logo: "/images/clients/utl-logo.svg"
keywords: 
 - Access to Memory (AtoM)
 - XML
 - EAD
 - XSLT
 - Formatting Objects (FO)
 - Accessibility remediation
lang: English
lang-iso: en
ref: uoft-atom
---

[Discover Archives](https://discoverarchives.library.utoronto.ca/index.php/) is a shared portal for exploring archival holdings
at the University of Toronto and its federated colleges. Archival fonds are described using the EAD metadata standard and managed
on an [Access to Memory (AtoM)](https://www.accesstomemory.org/en/) instance hosted by the UofT Libraries Information Technology Services.

AtoM provides a mechanism to automatically generate PDF finding aids from EAD descriptions, using XSL Transforms via XML-FO (Formatting Objects). 
However, the resulting PDFs often fail to meet certain accessibility requirements such as metadata for screen readers, 
bookmarks and a document structure that enables navigation. 

My work consisted in fixing such issues by editing the XSL Transforms. Other formatting issues were also addressed to meet UofT's
local display requirements, including the following improvements:

- Add document structure tags (headings, table headers, etc.) to PDF bookmarks for navigation
- Specify document language in PDF metadata (useful for screen readers)
- Identify decorative elements (e.g. logos) to reduce redundant descriptions
- Hyperlink URLs and email addresses in descriptions
- Address formatting issues such as text overflow for long inventory numbers, repetitive labels, line and page breaks, etc. 
- Implement limited Markdown support in description fields
- Custom fonts and other visual tweaks
- Identify strategies for inserting a different logo for each archives repository

The resulting accessibility improvements are operational at UofT since February 2025 and have been 
submitted for inclusion in the AtoM code base, so as to benefit the broader user community.

This work was funded by the 2023 University of Toronto Libraries Chief Librarian Innovation Grant titled [“Committed to Web Accessible Archival Description Discovery”](https://docs.google.com/presentation/d/1nY5ZGEWSZR_9V4LBIQBki-gbLPsEhtLsF0f4zh4e858/edit#slide=id.p1).