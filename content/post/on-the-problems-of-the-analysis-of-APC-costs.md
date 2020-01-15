---
title: "On the problems of the analysis of APC-costs"
date: 2020-01-02T08:00:00+01:00
author: Karsten Schuldt (FH Graubünden)
draft: false
tags: ["analytics", "open access", "apc", "openapc"]
---

Discussing about the SONAR-project, sometimes librarians and other colleagues seem to expect SONAR to deliver facts about “the costs of Open Access” for their institution. For this to happen, changes have to made, not in the SONAR-project, but within their institutions. This blog-post will shortly discuss those possibilities.

<!--more-->

### What are we dealing with, when we talk about “costs of OA”?

It has become commonly accepted in the scientific community that Open Access comes with costs attached. Sustainable infrastructures, editorial work and other costs have to be financed somehow. But, as the concept of “Article Processing Charges” (APC) which have to be paid for the publication of OA-articles have taken root, it also has become commonplace to focus singular on those costs when talking about the “costs of OA”. It is clear that this focus excludes other cost (e.g. for Open Journal Systems run by libraries, OA-officies), which should be kept in mind if somebody wants to determine the whole cost for OA. But in this post, we will focus on APCs.

### Data points for APCs

If one wishes to integrate the costs of APCs into the analysis of OA, one needs to have data of the actual APCs paid. This data is not openly available. (Otherwise, it would be solely a technical problem – one that has already been resolve; see below.)

There are basically two points were this data could be harvested:
1. The institutions or persons which pay the APCs
1. The publishers which collect the APCs

Different strategies can be utilized to gather data at these points.

#### Institutions and persons which pay APCs

Who pays APCs? This is not a trivial question. While literature on APCs often assumes that there are clear institutional procedures for their handling, in reality a plurality of possible “payers” exist:
* Libraries, either from their budget for collection development or fund allocated specifically for APCs – or even other funds
* Science funders, either directly through offsetting and other agreements or through project funding
* Academic institutions on different levels (on a central level, on the level of institutes, on the level of researchers)
* Sometimes, APCs are not paid by the person or institution which is responsible for a publication (e.g. in a network of researchers, a researcher in a country / institution with an offsetting agreement “pays”, even though others have written a publication) or APCs are split between participating researchers
* Researchers themselves have used project grants, other funds or their private money to pay for APCs

There are probably other instances of APC-payments, but the message is clear: There is no one institution that pays APCs, but this is a fluid landscape of options. If one includes international research-projects (that use different national structures of funding) or the different forms of “waiving” APCs, full or in part, by publishers, this only gets more complicated. There is also the problem of other fees, e.g. for “color publishing”, which are paid by researchers for OA- and not-OA-publications alike.

Keeping that in mind, it is clear that it is not possible to gather automatically all the payments for APCs at the point of payment itself. They have be collected somehow with input from within institutions. There are approaches to this on an institutional level (see below), but other options would be thinkable as well (e.g. on a national level or field-specific levels for international research networks).

### The OpenAPC initiative

Today, the OpenAPC initiative is the most advanced infrastructure to collect data on APCs. (Pieper & Broschinski 2018; Jahn & Tullney 2016) It was set-up by the “Transparent Infrastructure for Article Charges”-project that run in Germany from 2015 to 2018. OpenAPC now consists of a growing data-set accessible on [Github](https://github.com/OpenAPC/openapc-de) and maintained by the university library of Bielefeld.

Participating academic institutions contribute, in a defined data-structure, data about payed APCs. This data gets cumulated into the data-set. OpenAPC itself provides a [server with treemap analysis](https://treemaps.intact-project.org/apcdata/openapc/) of this data, but the set is open and downloadable for other usages as well. For example, this data is used by the [Open Access Monitor Germany](https://open-access-monitor.de/#/publication-costs). Institutions which provide their data to OpenAPC get this data analyzed by the OA monitor.

Participation in the OpenAPC initiative is voluntary. The Github page provides a list of participating institutions. There is a strong focus on Germany, but institutions from Norway, Sweden, France, the United Kingdom and other countries provide data as well. Up until now, only the Swiss National Science Foundation has provided data from Switzerland.

Participating in the initiative leads to the establishment of internal structures to gather the APC-costs by the institutions. Lisa Lovén (2019) from the Stockholm University Library describes this process for Swedish universities. All of them are now obligated to provide this data (in Swedish kronor), so every university set up their own infrastructure for reporting. While the text describes a centralized structure as the best approach, where theoretically every APC should go through the university library, this does not have to by the case in every institution. Other forms of reporting are possible (and probably more useful in less centralized systems like Swiss universities), as long as they end in one data-point for every institution.

Lovén’s article gives an example for a national solution as well: all of the data from Sweden is collected, transformed into the data-structure of OpenAPC (e.g. converted into Euro) and then pushed to the initiative. Such a system could also be established in other countries, in a form that is workable in the structure of scientific institutions of the respective country.

In Switzerland, institutions could set up a solution for collecting and reporting the data of the APCs paid to OpenAPCs. (The how-to is [described in detail here](https://github.com/OpenAPC/openapc-de/wiki/Data-Submission-Handout), all the participating institutions could provide guidance for the establishment of internal structures.) They would then be included into the OA-analysis of the OA-monitor Germany, using DOIs as data-point connecting publications and APCs. A national solution for Switzerland – maybe with Sweden as precedent – would require a political, and not technical, solution, e.g. on the level of swissuniversities. Will Swiss academic institutions be willing to gather the data of the APCs they paid? Will there be a joint effort of all or most of those institutions to gather this data?

### Data from publishers

APCs are usually paid to established publishers (like Elsevier, Springer) or organizations (like PLOS), with which libraries and national structures for scientific services often negotiate and sign contracts for reading and increasingly for publishing (e.g. the aforementioned offsetting deals). Those entities could also provide data on APCs, but until now there seems to be no initiative to demand this data.

However, the COUNTER-project would provide a precedent of establishing a standard for the reporting of data to libraries. [COUNTER](https://www.projectcounter.org/) was implemented through a coordinated effort by libraries to persuade publishers to provide usage date for electronic documents in a consistent way, using arguments and their power as negotiating partners (e.g. the ones with the money). It could be theorized that such a persuasion could also be organized for data on APCs, in particular when libraries are not acting alone but in coordination with academic institutions and funders. That would need the political will to bring up this question in negotiations and the establishment of an infrastructure for the reporting of such data.

Yet, COUNTER also provides a precedent of problems to come, if this route is chosen: still today, data is reported differently and not always comprehensively. Especially smaller organizations and publishers sometimes seem to have problems in establishing this reporting, although the standard has achieved its 4th release.

### Concerning SONAR

It should have become clear, that SONAR will not be able to provide an analysis on the costs of OA for Swiss institutions, firstly because the data is still missing, and secondly because efficient solutions already exist abroad.

The role of the project can be to highlight this question as a concern for Swiss libraries and to point out  possible solutions. If necessary in a further step, SONAR, as a key OA player, can provide IT expertise and resources to help developing and providing a suitable infrastructure.

Furthermore, the content tracking service of SONAR will provide a different but complementary approach, focused on the monitoring of the rate of effective OA publications, and not on the costs.

### Literature

Jahn, Najko, and Marco Tullney. “A Study of Institutional Spending on Open Access Publication Fees in Germany.” *PeerJ* 4 (August 9, 2016): e2323. https://doi.org/10.7717/peerj.2323.

Lovén, Lisa. “Monitoring Open Access Publishing Costs at Stockholm University.” *Insights* 32, no. 1 (January 17, 2019): 3. https://doi.org/10.1629/uksg.451.

Pieper, Dirk, and Christoph Broschinski. “OpenAPC: A Contribution to a Transparent and Reproducible Monitoring of Fee-Based Open Access Publishing across Institutions and Nations.” *Insights* 31, no. 0 (October 10, 2018): 39. https://doi.org/10.1629/uksg.439.
