---
layout: page
title: ACDIC
description: Analysis of Concordances and Discordances of Iconographic Canons using Ripa's Iconologia.
img: 
importance: 1
category: developed
related_publications: true
redirect: https://github.com/ACD-IC
---

The large number of anthologies, commentaries and indexes published in the 16th century demonstrate the drive towards standardization and canonization that permeated this century. Among the most influential reference works for the visual arts was Cesare Ripa’s *Iconologia*. First published in 1593, Ripa’s text collected an extensive repertory of ready-to-use allegorical descriptions and models which artists could conform to, serving as a foundation tool for the **codification of a shared visual vocabulary**. 

The *Iconologia* achieved extraordinary success: **38 expanded editions in five languages** over the following two centuries. Successive editions enriched and transformed the original work, **tailoring it to the distinct local and historical contexts** of each publication. Its success was rooted in its **modular structure**: each allegory functioned as a discrete unit open to variations. As a result, some allegories were documented only in particular editions, while previously described allegories were revised, either through changes to their textual descriptions or their associated attributes.

A systematic **analysis of the concordances and divergences among the described allegories** in each edition of the *Iconologia* would offer a valuable means of **tracing the evolution of Renaissance visual models** across Europe. However, due to the scale and complexity of the corpus, such an undertaking has been attempted only for a few selected editions. 

The project addresses these limitations by consolidating all existing digitized editions of the *Iconologia* into a **IIIF-based digital library**. Allegories will be then extracted from each edition and **automatically analyzed to trace their persistence, evolution, or disappearance across editions.**

This processing will be performed **using a combination of LLMs and open-source OCR engines** (Kraken/eScriptorium) for layout analysis and text extraction, making it possible to **extract allegories alongside their illustrations.** The resulting dataset will be further curated, **linked to external knowledge bases, and structured using the CIDOC-CRM** **ontology**, the *de facto* standard for semantic description of cultural and art historical information. The final dataset will contain information about each edition, its allegories and their textual descriptions. To support advanced queries and data analytics, **it will be made accessible as a downloadable dataset and through a SPARQL API interface**.

The project will produce (i) an accessible IIIF-based digital library of all *Iconologia* editions, (ii) a structured and accessible dataset of all the documented allegories linked to their textual and visual descriptions, and (iii) an quantitative and spatiotemporal analysis of concordances and divergences across all editions. This work will lay the foundation for further data-driven analyses on how cultural contexts and historical periods impact the evolution, contamination, and diversification of visual language.
