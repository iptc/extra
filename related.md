---
layout: default
title: IPTC EXTRA
---
## Related Work

Taxonomies are used by many news organizations to classify their content. Classification is used in various ways, including to structure website navigation menus to help readers locate relevant content, to organize editorial workflows and to enrich search. [News organizations classify news items](https://www.uie.com/articles/taxonomy_content_publishing) using either automated or human means - and often a combination of the two.

Some organizations, such as [The Associated Press](https://www.ap.org), [New York Times](www.nytimes.com), [Thomson Reuters](http://www.reuters.com/) and the [BBC](bbc.co.uk), have [built their own taxonomies to classify news](http://www.poynter.org/news/media-innovation/222187/how-taxonomies-help-news-organizations-understand-and-categorize-their-content). Many news organizations rely on the [IPTC’s Media Topics](https://iptc.org/standards/media-topics) as the basis of their classification of content.

The IPTC taxonomies may be applied manually by journalists or by archivists, often with quite inconsistent results. For example, this study discusses [manual classification of Spanish and Portugese newspaper archives](http://ir.ii.uam.es/neptuno/publications/neptuno-esws04.pdf).

There have been various attempts to automatically classify news content using IPTC taxonomies. In general, this involves software using natural language processing, semantic analysis and statistical pattern matching techniques to analyze each news item, and identify relevant metadata tags. Automated classification systems have been created for news in many languages, including [Arabic](https://vtechworks.lib.vt.edu/bitstream/handle/10919/51269/KananFoxArabicTextClassification.pdf), [English](http://nlp.lsi.upc.edu/papers/montoyo01.pdf), [Catalan and Portuguese](http://www.dfki.uni-kl.de/~bernardi/News/publication-download/SWCASE_NEWS.pdf) and [Spanish](http://link.springer.com/chapter/10.1007/978-3-540-74628-7_16#page-1).

Automated classification systems require regular maintenance in order to remain relevant and up-to-date. Most classification workflows allow for manual overrides to the resulting classification, with problematic documents being set aside for further review. New content must be incorporated into existing or new categories. Subject matter experts are required to review problematic documents and to tend to the needs of the automated classification systems, to [prevent results degrading over time](http://www.computerweekly.com/feature/Data-classification-why-it-is-important-and-how-to-do-it).

There are many toolkits and software systems for doing statistical classification of text content, such as [OpenNLP](http://opennlp.apache.org), [SRILM](http://www.speech.sri.com/projects/srilm) and [NLTK](http://www.nltk.org). However, none of these toolkits support the rules-based approach we plan for EXTRA. One open source toolkit that may be useful for building EXTRA is the [Elasticsearch Percolator](https://www.elastic.co/guide/en/elasticsearch/reference/current/search-percolate.html), which is designed to efficiently match queries (rules) to documents (news items).

Two open source frameworks which may be useful ways to deploy EXTRA are [GATE](https://gate.ac.uk) and [UIMA](https://uima.apache.org). GATE and UIMA are designed to allow third-party components to be plugged into their standardized platforms, to make it easier for developers to discover and work with sophisticated linguistic analysis tools.
