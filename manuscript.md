---
title: 'A species-specific Nanopore basecalling model improves sequencing accuracy for _Mycobacterium tuberculosis_ '
keywords:
- nanopore
- bioinformatics
- mycobacterium-tuberculosis
- basecalling
lang: en-GB
date-meta: '2021-11-25'
author-meta:
- Michael B. Hall
- Zamin Iqbal
header-includes: |-
  <!--
  Manubot generated metadata rendered from header-includes-template.html.
  Suggest improvements at https://github.com/manubot/manubot/blob/main/manubot/process/header-includes-template.html
  -->
  <meta name="dc.format" content="text/html" />
  <meta name="dc.title" content="A species-specific Nanopore basecalling model improves sequencing accuracy for _Mycobacterium tuberculosis_ " />
  <meta name="citation_title" content="A species-specific Nanopore basecalling model improves sequencing accuracy for _Mycobacterium tuberculosis_ " />
  <meta property="og:title" content="A species-specific Nanopore basecalling model improves sequencing accuracy for _Mycobacterium tuberculosis_ " />
  <meta property="twitter:title" content="A species-specific Nanopore basecalling model improves sequencing accuracy for _Mycobacterium tuberculosis_ " />
  <meta name="dc.date" content="2021-11-25" />
  <meta name="citation_publication_date" content="2021-11-25" />
  <meta name="dc.language" content="en-GB" />
  <meta name="citation_language" content="en-GB" />
  <meta name="dc.relation.ispartof" content="Manubot" />
  <meta name="dc.publisher" content="Manubot" />
  <meta name="citation_journal_title" content="Manubot" />
  <meta name="citation_technical_report_institution" content="Manubot" />
  <meta name="citation_author" content="Michael B. Hall" />
  <meta name="citation_author_institution" content="European Bioinformatics Institute, Hinxton, Cambridge, CB10 1SD, UK" />
  <meta name="citation_author_orcid" content="0000-0003-3683-6208" />
  <meta name="twitter:creator" content="@mbhall88" />
  <meta name="citation_author" content="Zamin Iqbal" />
  <meta name="citation_author_institution" content="European Bioinformatics Institute, Hinxton, Cambridge, CB10 1SD, UK" />
  <meta name="citation_author_orcid" content="0000-0001-8466-7547" />
  <meta name="twitter:creator" content="@ZaminIqbal" />
  <link rel="canonical" href="https://mbhall88.github.io/tubby-manuscript/" />
  <meta property="og:url" content="https://mbhall88.github.io/tubby-manuscript/" />
  <meta property="twitter:url" content="https://mbhall88.github.io/tubby-manuscript/" />
  <meta name="citation_fulltext_html_url" content="https://mbhall88.github.io/tubby-manuscript/" />
  <meta name="citation_pdf_url" content="https://mbhall88.github.io/tubby-manuscript/manuscript.pdf" />
  <link rel="alternate" type="application/pdf" href="https://mbhall88.github.io/tubby-manuscript/manuscript.pdf" />
  <link rel="alternate" type="text/html" href="https://mbhall88.github.io/tubby-manuscript/v/fc5c7df114255eec6850d12d4249e619d85e8f3c/" />
  <meta name="manubot_html_url_versioned" content="https://mbhall88.github.io/tubby-manuscript/v/fc5c7df114255eec6850d12d4249e619d85e8f3c/" />
  <meta name="manubot_pdf_url_versioned" content="https://mbhall88.github.io/tubby-manuscript/v/fc5c7df114255eec6850d12d4249e619d85e8f3c/manuscript.pdf" />
  <meta property="og:type" content="article" />
  <meta property="twitter:card" content="summary_large_image" />
  <link rel="icon" type="image/png" sizes="192x192" href="https://manubot.org/favicon-192x192.png" />
  <link rel="mask-icon" href="https://manubot.org/safari-pinned-tab.svg" color="#ad1457" />
  <meta name="theme-color" content="#ad1457" />
  <!-- end Manubot generated metadata -->
bibliography:
- content/manual-references.json
manubot-output-bibliography: output/references.json
manubot-output-citekeys: output/citations.tsv
manubot-requests-cache-path: ci/cache/requests-cache
manubot-clear-requests-cache: false
...






<small><em>
This manuscript
([permalink](https://mbhall88.github.io/tubby-manuscript/v/fc5c7df114255eec6850d12d4249e619d85e8f3c/))
was automatically generated
from [mbhall88/tubby-manuscript@fc5c7df](https://github.com/mbhall88/tubby-manuscript/tree/fc5c7df114255eec6850d12d4249e619d85e8f3c)
on November 25, 2021.
</em></small>

## Authors



+ **Michael B. Hall**<br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [0000-0003-3683-6208](https://orcid.org/0000-0003-3683-6208)
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [mbhall88](https://github.com/mbhall88)
    · ![Twitter icon](images/twitter.svg){.inline_icon width=16 height=16}
    [mbhall88](https://twitter.com/mbhall88)<br>
  <small>
     European Bioinformatics Institute, Hinxton, Cambridge, CB10 1SD, UK
  </small>

+ **Zamin Iqbal**<br>
    ![ORCID icon](images/orcid.svg){.inline_icon width=16 height=16}
    [0000-0001-8466-7547](https://orcid.org/0000-0001-8466-7547)
    · ![GitHub icon](images/github.svg){.inline_icon width=16 height=16}
    [iqbal-lab](https://github.com/iqbal-lab)
    · ![Twitter icon](images/twitter.svg){.inline_icon width=16 height=16}
    [ZaminIqbal](https://twitter.com/ZaminIqbal)<br>
  <small>
     European Bioinformatics Institute, Hinxton, Cambridge, CB10 1SD, UK
     · Funded by Grant XXXXXXXX
  </small>



## Abstract {.page_break_before}

<!--From https://www.microbiologyresearch.org/prepare-an-article#2-->

<!--The abstract should, if possible, introduce the subject in the first sentence and-->
<!--present the main conclusion in the last sentence. References should not be cited, and-->
<!--any abbreviations used must be defined.-->



## Keywords {.page_break_before}

## Author notes

## Abbreviations

## Impact statement

## Data summary

<!--https://www.microbiologyresearch.org/prepare-an-article#3-->

<!--Authors providing supporting external data such as sequencing, datasets, code and-->
<!--software should include a Data Summary describing this, including the DOI(s) and/or-->
<!--accession numbers(s), and the associated URL.-->

<!--Datasets, software and code deposited in repositories such as Figshare, Zenodo or GitHub-->
<!--should also be included as a unique reference in the Reference list.-->

<!--Microbial Genomics is a mandatory open data journal and as such asks authors to always-->
<!--include a Data Summary describing all supporting external data.-->



## Introduction {.page_break_before}

<!--https://www.microbiologyresearch.org/prepare-an-article#4-->
<!--State the objectives of the work and cite previous relevant work to set the scene. The-->
<!--Introduction should not constitute a full review, but should be sufficiently detailed to-->
<!--allow readers to interpret the rest of the article.-->



## Methods

<!--https://www.microbiologyresearch.org/prepare-an-article#5-->
<!--The methods should be comprehensive and provide sufficient detail to allow your work to-->
<!--be repeated. Software used should be consistently cited and its version and parameters-->
<!--included. Indicate the suppliers of chemicals and equipment if this may affect the-->
<!--results; if there are name changes between your work and submission, please ensure this-->
<!--is clearly indicated. We do not need suppliers’ addresses.-->



## Results

<!--https://www.microbiologyresearch.org/prepare-an-article#6-->

<!--Please organise your Results section with enough subheadings to allow readers to gain a-->
<!--clear picture of the work. The section should indicate the key questions being-->
<!--addressed, the outcomes of experiments, and any interpretation of these results. You may-->
<!--include here any figures and tables within the body of the text to assist Editors and-->
<!--reviewers in assessing the work more easily.-->

<!--To help Editors and reviewers assess the reproducibility of your work, include the-->
<!--number of times your experiment was repeated and the type of result shown (mean, median,-->
<!--representative, etc.). If results are expressed as percentages, the absolute value-->
<!--corresponding to 100% should be stated. Indicate the variability of the results-->
<!--statistically wherever possible; when error terms are given, state the measure of-->
<!--dispersion and the number of observations. Specify the statistical techniques you used,-->
<!--and where necessary either describe the technique or provide a reference.-->



## Discussion

<!--https://www.microbiologyresearch.org/prepare-an-article#7-->

<!--Your discussion should not be too long. Compare your results with previous findings-->
<!--without revisiting your results in full, and use subheadings where appropriate to-->
<!--highlight the points under discussion. It may be helpful to list the main conclusions at-->
<!--the end.-->
<!--Where appropriate, you may wish to provide a combined Results and Discussion section.-->



## Funding information

<!--https://www.microbiologyresearch.org/prepare-an-article#8-->
<!--Describe in detail the funding sources that supported this work, including the names of-->
<!--funding bodies and grant numbers. Any authors who are associated with specific funding-->
<!--sources should be named. You must also state whether anyone employed by the funders,-->
<!--other than the authors, played any role in the study or in the preparation of the-->
<!--article or decision to publish; these persons need to be named and their role described.-->
<!--If you did not receive funding for the work, include the line "This work received no-->
<!--specific grant from any funding agency" under the Funding information heading.-->



## Acknowledgements

## Author contributions

<!--https://www.microbiologyresearch.org/prepare-an-article#8-->


## Conflicts of interest

<!--https://www.microbiologyresearch.org/prepare-an-article#8-->

## Ethical statement

<!--https://www.microbiologyresearch.org/prepare-an-article#8-->

<!--Any experimental work with humans or animals must include a statement that the Ethical-->
<!--Committee of the institution in which the work was done has approved the work. This-->
<!--includes research which uses samples obtained through routine diagnostic procedures or-->
<!--treatments. For human work we also require a statement regarding informed consent.-->

<!--We will not accept articles in which the ethical aspects are open to doubt, and-->
<!--encourage all authors to consult the relevant EQUATOR guidelines for reporting-->
<!--experiments involving humans or animals.-->



## References {.page_break_before}

<!-- Explicitly insert bibliography here -->
<div id="refs"></div>
