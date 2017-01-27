---
title: Guidelines
layout: default
navigation_weight: 25
---

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

Note that these word counts are not targets but maximum values. Papers may be significantly shorter. Exceptions for longer papers are possible if well justified (contact the editors-in-chief before submitting papers that exceed the stated word limits).

These word counts include the abstract, tables, and figure and table captions. Author lists and references, however, are not counted. Each figure counts for an additional 300 words.

##### Papers in HTML

We encourage authors to submit their papers in HTML. There are various tools and templates for that, such as [RASH](https://github.com/essepuntato/rash/), [dokieli](https://dokie.li/), and [Authorea](https://www.authorea.com).

The *Research Articles in Simplified HTML* (*RASH*) ([doc](https://rawgit.com/essepuntato/rash/master/documentation/index.html), [paper](https://rawgit.com/essepuntato/rash/master/papers/rash-demo-iswc2015.html)) is a markup language that restricts the use of HTML elements to only 32 elements for writing academic research articles. It is possible to includes also RDFa annotations within any element of the language and other RDF statements in Turtle, JSON-LD and RDF/XML format by using the appropriate tag `script`.
Authors can start from this [generic template](https://github.com/essepuntato/rash/blob/master/template.html), which can be also found in the convenient [ZIP archive](https://rawgit.com/essepuntato/rash/master/rash.zip) containing the whole RASH package.
Alternatively, these guidelines for [OpenOffice](https://rawgit.com/essepuntato/rash/master/documentation/rash-in-odt.odt) and [Word](https://rawgit.com/essepuntato/rash/master/documentation/rash-in-docx.docx) explain how to write a scholarly paper by using the basic features available in OpenOffice Writer and Microsoft Word, in a way that it can be converted into RASH by means of the [*RASH Online Conversion Service* (*ROCS*)](http://dasplab.cs.unibo.it/rocs) ([src](https://github.com/essepuntato/rash/tree/master/tools/rocs), [paper](https://rawgit.com/essepuntato/rash/master/papers/rash-poster-www2016.html)).

As a second alternative, [dokieli](https://github.com/linkeddata/dokieli) is a client-side editor for decentralized article publishing in HTML+RDFa, annotations and social interactions, compliant with the [Linked Research](https://linkedresearch.org/) initiative. There are a variety of [examples in the wild](https://github.com/linkeddata/dokieli/wiki#examples-in-the-wild), including the [LNCS](https://dokie.li/lncs-splnproc) and [ACM](https://dokie.li/acm-sigproc-sp) author guidelines as templates.

Finally, as a third alternative, the [Authorea](https://www.authorea.com) platform is at the moment probably the easiest way to write and export papers in HTML. We are also working on supporting direct submission to our journal from within that platform.


##### Papers in Word or LaTeX

We prefer HTML, but we also accept submissions in Word or LaTeX. In that case, please use the [official templates by IOS Press](http://www.iospress.nl/service/authors/latex-and-word-tools-for-book-authors/).

##### Semantic Publishing

This is optional, but we would like to encourage you to provide semantic (meta-)data with your scientific papers, but unfortunately no accepted standards, best practices, or nice tools exist for that yet. We are working to fix this. In the meantime, and if you are a bit experienced with RDF, we are very happy to receive your RDFa-enriched paper or a submission with separate RDF statements. We are also happy to help you with that, if you are not experienced with RDF.

We hope to be able to provide more general and more user-friendly guidelines for semantic publishing in the near future.

##### Data

All relevant data that were used or produced for conducting the work presented in a paper must be made [FAIR](http://www.dtls.nl/fair-data/) and compliant with the [PLOS data availability guidelines](http://journals.plos.org/plosone/s/data-availability) prior to submission. See in particular the list of [recommended data repositories](http://journals.plos.org/plosone/s/data-availability#loc-recommended-repositories). (We might provide our own data availability guidelines in the future, but we borrow the excellent PLOS guidelines for now.) In a nutshell, data have to be made openly accessible and freely reusable via established institutions and standards, unless privacy concerns forbid such a publication. In any case, metadata have to be made publicly accessible and visible.

##### Evaluation Criteria

See the reviewing guidelines below for the specific criteria according to which submitted papers are evaluated.


### Guidelines for Reviewers

In order to facilitate a speedy reviewing process, reviewers are requested to submit their assessment within 10 days. Reviews consist of the parts described below.


##### Overall recommendation

The review of a paper should suggest one of the following overall recommendations:

- **Accept.** The article is accepted as is, or only minor problems must be addressed by the authors that do not require another round of reviewing but can be verified by the editorial and publication team.
- **Undecided.** Authors must revise their manuscript to address specific concerns before a final decision is reached. A revised manuscript will be subject to second round of peer review in which the decision will be either Accept or Reject and no further review will be performed.
- **Reject.** The work cannot be published based on the lack of interest, lack of novelty, insufficient conceptual advance or major technical and/or interpretational problems.


##### Criteria

The review should evaluate the paper with respect to the following criteria.

**Significance:**

- Does the work address an important problem within the research fields covered by the journal?

**Background:**

- Is the work appropriately based on and connected to the relevant related work?

**Novelty:**

- _For research papers:_ Does the work provide new insights or new methods of a substantial kind?
- _For position papers:_ Does the work provide a novel and potentially disruptive view on the given topic?
- _For survey papers:_ Does the work provide an overview that is unique in its scope or structure for the given topic?

**Technical quality:**

- _For research papers:_ Are the methods adequate for the addressed problem, are they correctly and thoroughly applied, and are their results interpreted in a sound manner?
- _For position papers:_ Is the advocated position supported by sound and thorough arguments?
- _For survey papers:_ Is the topic covered in a comprehensive and well balanced manner, are the covered approaches accurately described and compared, and are they placed in a convincing common framework?

**Presentation:**

- Are the text, figures, and tables of the work accessible, pleasant to read, clearly structured, and free of major errors in grammar or style?

**Length:**

- Is the length of the manuscript appropriate for what it presents?

**Data availability:**

- Are all used and produced data are openly available in established data repositories, as mandated by [FAIR](http://www.dtls.nl/fair-data/) and the [data availability guidelines](http://journals.plos.org/plosone/s/data-availability)?


##### Summary and Comments

Finally, reviewers are asked to answer the following points:

- Summary of paper in a few sentences
- Reasons to accept
- Reasons to reject
- Further comments (optional)

