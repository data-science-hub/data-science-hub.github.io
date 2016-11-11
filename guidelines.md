---
title: Guidelines
layout: default
navigation_weight: 25
---

_(The information below is preliminary and subject to change. The properties and features of this journal are being discussed [here](https://github.com/data-science-hub/data-science-hub.github.io/issues).)_


### Guidelines for Authors

Authors should closely follow the guidelines below before submitting a manuscript.

##### Language

All papers have to be written in English.

##### Paper Length

The following length limits apply for the different paper types:

- Research papers: 12 000 words
- Position papers: 8 000 words
- Survey papers: 16 000 words
- Reports: 5 000 words

Note that these word counts are not targets but maximum values. Papers may be significantly shorter.

These word counts include the abstract, tables, and figure and table captions. Author lists and references, however, are not counted. Each figure counts for an additional 300 words.

##### Papers in HTML

We encourage authors to submit their papers in HTML. There are various tools and templates for that, such as [RASH](https://github.com/essepuntato/rash/) and [dokieli](https://dokie.li/).


The *Research Articles in Simplified HTML* (*RASH*) ([doc](https://rawgit.com/essepuntato/rash/master/documentation/index.html), [paper](https://rawgit.com/essepuntato/rash/master/papers/rash-demo-iswc2015.html)) is a markup language that restricts the use of HTML elements to only 32 elements for writing academic research articles. It is possible to includes also RDFa annotations within any element of the language and other RDF statements in Turtle, JSON-LD and RDF/XML format by using the appropriate tag `script`.
Authors can start from this [generic template](https://github.com/essepuntato/rash/blob/master/template.html), which can be also found in the convenient [ZIP archive](https://rawgit.com/essepuntato/rash/master/rash.zip) containing the whole RASH package.
Alternatively, these [guidelines for OpenOffice](https://rawgit.com/essepuntato/rash/master/documentation/rash-in-odt.odt) explain how to write a scholarly paper by using the basic features available in OpenOffice Writer, in a way that it can be converted into RASH by means of the [*RASH Online Conversion Service* (*ROCS*)](http://dasplab.cs.unibo.it/rocs) ([src](https://github.com/essepuntato/rash/tree/master/tools/rocs), [paper](https://rawgit.com/essepuntato/rash/master/papers/rash-poster-www2016.html)).

As a second alternative, [dokieli](https://github.com/linkeddata/dokieli) is a client-side editor for decentralized article publishing in HTML+RDFa, annotations and social interactions, compliant with the [Linked Research](https://linkedresearch.org/) initiative. There are a variety of [examples in the wild](https://github.com/linkeddata/dokieli/wiki#examples-in-the-wild), including the [LNCS](https://dokie.li/lncs-splnproc) and [ACM](https://dokie.li/acm-sigproc-sp) author guidelines as templates.

##### Semantic Publishing

This is optional, but we would like to encourage you to provide semantic (meta-)data with your scientific papers, but unfortunately no accepted standards, best practices, or nice tools exist for that yet. We are working to fix this. In the meantime, and if you are a bit experienced with RDF, we are very happy to receive your RDFa-enriched paper or a submission with separate RDF statements. We are also happy to help you with that, if you are not experienced with RDF.

We hope to be able to provide more general and more user-friendly guidelines for semantic publishing in the near future.

##### Papers in Word or LaTeX

We prefer HTML, but we also accept submissions in Word or LaTeX. In that case, please use the [official templates by IOS Press](http://www.iospress.nl/service/authors/latex-and-word-tools-for-book-authors/).

##### Data

All relevant data that were used or produced for conducting the work presented in a paper must be made [FAIR](http://www.dtls.nl/fair-data/) prior to submission. In particular, data have to be made openly accessible and freely reusable via established institutions and standards, unless privacy or confidentiality concerns forbid such a publication. In any case, metadata have to be made publicly accessible and visible.

##### Evaluation Criteria

See the reviewing guidelines below for the specific criteria according to which submitted papers are evaluated.


### Guidelines for Reviewers

In order to facilitate a speedy reviewing process, reviewers are requested to submit their assessment within 10 days.

Reviews consist of the following parts described below.


##### Overall recommendation

The review of a paper should lead to one of the following overall recommendations:

- **Accept.** The article is accepted as is, or minor presentation, grammatical, or spelling problems raised in review must be addressed by the authors and verified by the editorial and publication team.
- **Undecided.** Authors must revise their manuscript to address specific concerns before a final decision is reached. A revised manuscript will be subject to second round of peer review in which the decision will be either Accept or Reject and no further review will be performed.
- **Reject.** The work cannot be published based on the lack of interest, lack of novelty, insufficient conceptual advance or major technical and/or interpretational problems.


##### Summary

Reviewers should briefly summarize key problems, approach, results, and claims of the article. 


##### Significance

- Is the significance of the problem area clearly stated and compelling?
- In other words, what evidence is provided that the problem area is of importance?
- Who will be interested in reading the paper?
- Is the paper likely to be one of the ten most significant papers published in the discipline this year?


##### Novelty

- Are the claims appropriately discussed in the context of previous literature?
- Is there published work that challenges the claimed novelty?


##### Clarity

- Is the manuscript well written?
- Does it use language that is undefined or unfamiliar to the reviewer?
- Do the figure or table legends clearly communicate the nature and contents of the figure or tables?
- Are there awkward phrases or errors with respect to spelling or grammar?

##### Soundness

- Is the approach valid?
- Are the use of statistics and treatment of uncertainties correctly handled?
- Are there any aspects of the approach that could compromise the integrity of the study?

##### Reproducibility

- Could the work be reasonably reproduced by similarly qualified individual or group?
- Are the resources used in the study available to others to replicate their findings?
- Are the data and software openly available, or is there an appropriate rationale for why they cannot be made available (such as privacy issues)?
- If the data or software are not directly available, is there a clear mechanism for obtaining these?
- Do the data or software reuse standards?
- Are data and software versions provided for the used resources?

##### FAIRness

- Have the authors made efforts to make their resources maximally FAIR - Findable, Accessible, Interoperable and Reusable - in line with the [FAIR](http://www.dtls.nl/fair-data/) principles?

##### Suggested improvements

Reviewers are required to provide concrete suggestions as to how the authors can improve their work and directly address raised concerns. This can include new experiments, use of other datasets, comparison with other work, a different statistical evaluation, etc.

