---
layout: page
description: a project with a background image
img: assets/img/iswc15logo.png
importance: 1
category: workshop
title: "OrdRing 2014"
date: "2016-05-02"
---

# 3rd International Workshop on Ordering and Reasoning

**October 20th, 2014 Riva del Garda, Trentino, Italy Collocated with the 13th International Semantic Web Conference ([ISWC 2014](http://iswc2014.semanticweb.org/))**

## Content

[News](#news) [Abstract](#abstract) [Motivation](#objectives) [Topic Of Interest](#topics) [Submissions](#SUBMISSIONS) [Program](#program) [Proceedings](#PROCEEDINGS) [Important Dates](#IMPORTANT%20DATES) [Workshop Chairs](#WORKSHOP%20CHAIRS) [Program Committee](#PC)

## NEWS

The two best papers of OrdRing2014 have the opportunity to be published on [Journal on Data Semantics](http://www.springer.com/computer/database+management+%26+information+retrieval/journal/13740).

## ABSTRACT

More and more applications require real-time processing of massive, dynamically generated, ordered data; where order is often an essential factor reflecting recency, proximity or relevance. Stream and rank-aware data management techniques are progressively providing reactive and reliable query answering over such massive datasets. Key to their success is the use of [streaming algorithms](#objectives "If N is the size of the input, a problem is considered to be “well- solved” by a streaming algorithm if such an algorithm requires at most O(poly(log(N)) space and time") that harness the natural or enforceable orders in the data. Semantic technologies can play a relevant role in this setting, exploiting their expressive power to integrate those highly dynamic sources. In the recent years, different work started to push order-related concepts in semantic technologies, such as Stream Reasoning and top-k ontological query answering. This workshop (as its predecessors in [2011](http://ordring2011.search-computing.org/), and [2013](events/ordring2013)) aims at bringing together this growing and very active community interested in **[integrating ordering with reasoning](http://www.semantic-web-journal.net/sites/default/files/swj246_1.pdf "Emanuele Della Valle, Stefan Schlobach, Markus Krötzsch, Alessandro Bozzon, Stefano Ceri, Ian Horrocks: Order matters! Harnessing a world of orderings for reasoning over massive data. Semantic Web 4(2): 219-231 (2013)")** by using methods inspired by stream and rank-aware data management.

## MOTIVATION

The continuous growth of volume, velocity and variety of data poses new challenge for their processing, especially when it has to be done in real-time or near-real time. It often happens that orders are involved in those processes: the input data can be ordered by some criteria (e.g. recency, proximity), and so the output data (e.g. relevance). In both cases, orders can play a key-role, enabling the design of ad-hoc algorithms and processes that exploit those orders to increase the performance. A relevant example can be found in rank-aware data management, where there are techniques to perform query answering through streaming algorithms that exploit the natural or enforceable orders in the data. Moreover, in stream data management, algorithms are not only designed to be online and streaming, but also any-time: they processes the input data and they produce sequences of valid answers at different time instants. The expressive power of Semantic technologies is needed in those applications, but Semantic Technologies risk being unable to address the needs of those applications, because they do not consider ordering as an essential property. Ranking results is often seen as an “added task”, performed after inference, without affecting the inference process, which is order-agnostic. However, we perceive a trend towards order-aware semantic technologies: both researchers and practitioners understand that _order matters in reasoning over massive and highly dynamic data_. The idea of Stream Reasoning is gaining considerable momentum. Some top-k query answering techniques for Linked Data appeared. Several works are considering SPARQL query answering on RDF annotated with labels partially ordered. The Description Logic community is investigating top-k ontological query answering. We see this workshop as a further step to stimulate and guide a paradigm shift in semantic technologies. We aim at involving researchers and experts in stream and rank-aware data management to put together their competences and to share them with the community. The final goal of the workshop is to contribute to this young, but very active trend of order-aware data processing.

## TOPICS OF INTEREST

Topics include, but not limited to:

- Inference with streaming algorithms
- Ontological query answering over data streams
- Incremental maintenance of materialization of data streams
- Continuous query answering over data streams
- Ontological top-k query answering over massive ordered data
- Data compression algorithms for data stream processing
- Continuous query answering and top-k query answering for fuzzy logics
- Knowledge Representation for ordered facts
- APIs for data stream exchange
- Topologies for distributed processing of data streams
- Role of parallelization and distribution in order-aware semantic technologies
- Approximation approaches to inference with orderings
- Proposals for and applications of benchmarks
- Applications of stream reasoning and top-k ontological query answering
- Implementation and evaluation experiences

## SUBMISSIONS

We will welcome submissions describing ideas, experiments, and application visions originating from requirements for, and efforts aimed at, interleaving ordering and reasoning. We will encourage **short position** and **short demo papers** not exceeding 6 pages as well as longer **technical papers** not exceeding 12 pages. They should follow the LNCS proceedings style files..

Submissions should be formatted according to the Lecture Notes in Computer Science guidelines for proceedings available at [http://www.springer.com/computer/lncs?SGWID=0-164-7-72376-0](http://www.springer.com/computer/lncs?SGWID=0-164-7-72376-0). Papers should be submitted in PDF format. All submissions will be done electronically via the OrdRing2014 web submission system ([http://www.easychair.org/conferences/?conf=ordring2014](http://www.easychair.org/conferences/?conf=ordring2014)).

At least one author of each accepted paper must register for the workshop. Information about registration will appear soon on the [ISWC 2014 Web page](http://iswc2014.semanticweb.org/registration).

## PROGRAM

- 9:00-9:10 Workshop introduction
- 9:10-9:30 _“[Towards a Top-K SPARQL Query Benchmark Generator](/slides/2014/10/Top-k-DBPSB-OrdRing2014.pptx)"_. Shima Zahmatkesh, Emanuele Della Valle, Daniele Dell'Aglio and Alessandro Bozzon.
- 9:30-9:50 _“[Enhanced e-Learning Experience by Pushing the Limits of Semantic Web Technologies](/slides/2014/10/EnhancedLearningExperience_OrdRing2014.pdf)”._ Andrea Zielinski and Jürgen Bock.
- 9:50-10:10 _“[Towards Efficient Processing of RDF Data Streams](/slides/2014/10/ordring2014_allaves.ppt)”._ Alejandro Llaves, Javier D. Fernández and Oscar Corcho.
- 10:10-10:30 _“[Towards an Efficient Semantically Enriched Complex Event Processing and Pattern Matching](/slides/2014/10/Presentation-ISWC.pdf)”._ Syed Gillani, Gauthier Picard, Frederique Laforest and Antoine Zimmermann.
- 10:30-11:00 Break
- 11:00-11:20 _“[Towards a Logic-Based Framework for Analyzing Stream Reasoning](/slides/2014/10/bdef2014-ordring-talk.pdf)”._ Harald Beck, Minh Dao-Tran, Thomas Eiter and Michael Fink.
- 11:20-11:50 Keynote: _"[RDF Stream Processing: Let's React!](http://fr.slideshare.net/jpcik/rdf-stream-processing-lets-react)"_, Jean-Paul Calbimonte
- 11:50-12:30 Discussion, wrap-up and best paper announcement

## PROCEEDINGS

The Workshop Proceedings are now published as CEUR Workshop Proceedings: [http://ceur-ws.org/Vol-1303/](http://ceur-ws.org/Vol-1303/) .

## IMPORTANT DATES

- Abstract submission deadline: 30 June 2014
- Paper submission: 7 July 2014 14 July 2014
- Author notifications: 30 July 2014
- Camera ready version due: 20 August 2014

## WORKSHOP CHAIRS

- [Irene Celino](http://iricelino.org/) (CEFRIEL)
- [Oscar Corcho](http://mayor2.dia.fi.upm.es/oeg-upm/index.php/en/teachers/11-ocorcho) (UPM)
- [Emanuele Della Valle](http://emanueledellavalle.org) (Politecnico di Milano)
- [Daniele Dell'Aglio](http://www.dellaglio.org/) (Politecnico di Milano)
- [Markus Krötzsch](http://korrekt.org/) (Technische Universität Dresden)
- [Stefan Schlobach](http://www.few.vu.nl/%7Eschlobac/) (Vrije Universiteit Amsterdam)

## PROGRAM COMMITTEE

- Alessandro Bozzon (TU Delft)
- Jean-Paul Calbimonte (École Polytechnique Fédérale de Lausanne)
- Peter Haase (fluid Operations)
- Alejandro Llaves (Universidad Politécnica de Madrid)
- Carsten Lutz (University of Bremen)
- Alessandro Margara (University of Lugano)
- Tomas Masopust (TU Dresden)
- Jeff Z. Pan (University of Aberdeen)
- Giuseppe Pirrò (University of Koblenz-Landau)
- Axel Polleres (WU Wien)
- Umberto Straccia (ISTI-CNR)
- Anni-Yasmin Turhan (TU Dresden)
- Guido Vetere (IBM)
- Haofen Wang (East China University of Science and Technology)
- Kewen Wang (Griffith University)
- Zhe Wu (Oracle)
