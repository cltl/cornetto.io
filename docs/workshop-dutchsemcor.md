---
layout: page
title: "Workshop DutchSemCor"
permalink: /workshop-dutchsemcor/
---
The Workshop DutchSemCor was held on Friday, May 16, 2008. The presentation slides from the meeting are included in the Agenda (see below).

**Workshop Topics and Aims**  
During this workshop we would like to discuss the development of a large, semantically tagged corpus for Dutch, comparable to the English SemCor and equivalents in other languages. Such a corpus is lacking and hampers Dutch language-technology development. Recently, a new large semantic database for Dutch has been built, the Cornetto database, which opens up the possibility to also deliver a semantically tagged corpus for Dutch. This corpus may play a key role in language technology research for Dutch, and also in linguistic and cognitive research that relates linguistic form to meaning. Combining the best of both worlds, the corpus will be tagged using a combination of automatic techniques and manual editing. Automatic tagging techniques include on the one hand supervised methods, which can be trained on already tagged subcorpora as training data, enabling them to tag other subcorpora, and on the other hand unsupervised techniques that rely on other sources such as the Cornetto database itself. It is to be expected that the manual editing of the corpus will feed back in the form of adaptations to the semantic database Cornetto. Possible characteristics of the envisaged DutchSemCor project are:

- a large corpus with sense-tags from the Cornetto database:  
  - with a focus on the most-frequent, most-polysemous and domain-independent nouns, verbs and adjectives  
  - excluding tagging of (fixed) collocational constructions  
The motivation for this restriction is that sense-selection for collocations requires firstly recognization of the collocation (IRME) and secondly representation of the meaning of the collocation in the Cornetto database. These seem to us matters for future research that will be enabled by the DutchSemCor corpus.  
  - excluding metaphoric and metonymic uses  
The same holds for metaphoric and metonymic uses of words. Automatic detection and interpretation of these  
aphenomena will be enabled by the DutchSemCor corpus as future research projects.  
  - including some domain specialization as illustration  
Domain-based WSD is emerging and promising but it is also relatively easy and thus avoids solving the hard domain-independent cases. We will include some specialized domain-tagging in the corpus but we expect that this issue can be solved without a DutchSemCor corpus, e.g. by automatically acquiring (unsupervised) domain corpora. These solutions are less language-dependent as well.  
- a variety of sense-taggers based on different techniques: knowledge rich, supervised, unsupervised  
- a sense-annotation tool that interacts with the Cornetto database

**Programme**  
At the workshop, we will present our preliminary plans and ideas about a project to build a Dutch SemCor. Furthermore, there are two invited presentations on the building of the English SemCor and a similar corpus for Basque. The afternoon session is used for discussion on issues related to the building and use of such a corpus.  
The following issues will be briefly introduced:  
- machine learning from semantically tagged corpora (prof. dr. Antal van den Bosch, ILK Research Group, Tilburg University)  
- community tagging and wikipedia as additional resource (prof. dr. Maarten de Rijke, Intelligent Systems Lab, Universiteit van Amsterdam)  
- language technology companies that may use such a corpus (dr. Leonoor van der Beek, Q-Go, Amsterdam)  
- semantic tagging in D-COI and SONAR (dr. Paola Monachesi, Uil-OTS, Utrecht)  
- linguistic research into the relation between form and meaning with the help of a semantically annotated corpus (Trijntje Pasma, Fac. der Letteren, VU, Amsterdam)

**Agenda**

<table>
<tbody>
<tr>
<td>10:00 - 10:30</td>
<td>Coffee</td>
</tr>
<tr>
<td>10:30 - 11:00</td>
<td>Project overview (Piek Vossen) ppt</td>
</tr>
<tr>
<td>11:00 - 11:30</td>
<td>Cornetto (Piek Vossen)</td>
</tr>
<tr>
<td>11:30 - 12:30</td>
<td>Basque SemCor (Eneko Agirre) ppt</td>
</tr>
<tr>
<td>12:30 - 13:30</td>
<td>Lunch</td>
</tr>
<tr>
<td>13:30 - 14:30</td>
<td>SemCor (Helen Langone) ppt </td>
</tr>
<tr>
<td>14:30 - 14:45</td>
<td>Coffee</td>

</tr>
<tr>
<td>14:45 - 16:15</td>
<td>
    Annotation tools for semantic tagging (Jakub Zavrel) <i>cancelled</i>
    Machine learning from semantically tagged corpora (Antal van den Bosch) ppt
    Community tagging and Wikipedia as additional resource (Maarten de Rijke) ppt
 Semantic Role Tagging in a Dutch Corpus (Paola Monachesi) ppt
    The use of a semantically tagged corpus by Language Technologies Companies (Leonoor van der Beek) ppt
    The use of a semantically tagged corpus for language and metaphor research (Trijntje Pasma) ppt
</td>
</tr>
<tr>
<td>16:15 - 16:30</td>
<td>Discussion</td>
</tr>
<tr>
<td>16:30 </td>
<td>Drinks</td>
</tr>
</tbody></table> 

**Organised by**  
Piek Vossen (Fac. der Letteren, Vrije Universiteit Amsterdam)  
Isa Maks (Fac. der Letteren, Vrije Universiteit Amsterdam)  
Antal van den Bosch (ILK Research Group, Tilburg University)  
Maarten de Rijke (Intelligent Systems Lab, Universiteit van Amsterdam)

**Invited Speakers and Talks**  
**Helen Langone, Cognitive Science Laboratory, Princeton University**  
Helen Langone has a BS in Computer Science (1987) and MA in Linguistics (1998). She has been programming professionally for 20 years, the past 8 years of which have been in the lexicographic domain. She consults in the area of commercial lexicography, working on dictionaries for Random House, OUP, CUP, and Lexico (dictionary.com). She has been a freelance consultant, and now part-time Technical Staff member, on the WordNet project on and off since 2002, contributing to a project to disambiguate the WordNet glosses.

**SemCor and its { offspring, progeny, issue }: what can future projects learn from the experience of those who came before?**  
Semantically annotated corpora marry dictionary definitions to words in context. Such a union brings together complementary aspects of the meaning of a word: syntagmatic and paradigmatic. A word is understood by the words it keeps company with in discourse, but also with respect to its relatives in its lexical "family tree". A semantically annotated corpus can therefore be a useful lexico-semantic asset for NLP researchers who are building and training systems for WSD, Q&A;, Summarization, Information Retrieval and Information Extraction.  
Semcor, in which the Brown corpus was semantically tagged to WordNet, is the grandfather of semantically annotated corpora. The disambiguated WordNet gloss project and the Basque Semcor are its latest progeny. Many issues that arose for Semcor will be encountered by its successors, and pitfalls that one project trips on will lie in wait for another. Targeted vs. sequential tagging, granularity of the senses, tagging to a static or moving target...how these questions are answered can forestall certain problems but invite others. The question I will consider in this talk is: What can future projects learn from the experience of those who came before?

**Eneko Agirre, University of the Basque Country, UPV/EHU, Basque Country**  
Eneko Agirre received his PhD (1999) and B.A. (1990) in Computer Science by the University of the Basque Country, M.Sc. (1991) in Cognitive Science by the University of Edinburgh. He is currently a lecturer in the Computer Science Faculty of the University of the Basque Country since 1995. He has published over ninety refereed articles and conference papers in Natural Language Processing, mainly in the areas of Lexical Knowledge Acquisition, Word Sense Disambiguation and Semantic Processing. He has been the co-editor of the book “WSD: Algorithms and applications”. He is a member of the program committees for major conferences like GWC, ACL, HLT, CONLL, TSD, RANLP and EMNLP, and has organized several workshops in major conferences (ACL and EACL). He is a usual reviewer for other major conferences including IJCAI, and several journals including LRE, NLE, JSL, ACM Computing Surveys, ACM TOIS and IEEE Intelligent Systems. He participates in the KNOW and KYOTO projects, and has participated in HERMES and MEANING. He has organized the SemEval-2007 semantic evaluations competition and workshop.

**A methodology for the joint development of the Basque WordNet and Semcor**  
This talk describes the methodology adopted to jointly develop the Basque WordNet and a hand annotated corpora (the Basque Semcor). This joint development allows for better motivated sense distinctions, and a tighter coupling between both resources. The methodology involves edition, tagging and refereeing tasks. The talk will review the guidelines for taggers and wordnet editors, and present the interfaces used.

**Location**  
Hortus Botanicus Amsterdam  
Plantage Middenlaan 2a, Amsterdam, 020 - 6259021 www.dehortus.nl

* * *

Last update: 5 June, 2008, e.maks (at) let.vu.nl
