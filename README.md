VI_FIIT_projekt
================

Projekt na vyhladavanie info.. repozitár, ktorý obsahuje informácie o projekte

Vstupné dáta
================

Ukážka vstupných dát je v adresári /data.

sample_dbpedia_long_abstracts_en.xml - ukážka vstupných dát z dbpedie

sample_enwiki-latest-abstract.xml - ukážka vstupných dát z wikipedie

Ukážka fungovania
===================

Príklad vstupných dát - DBPedia:

<http://dbpedia.org/resource/A> <http://dbpedia.org/ontology/abstract> "A (named a /ËˆeÉª/, plural aes) is the first letter and vowel in the ISO basic Latin alphabet. It is similar to the Ancient Greek letter alpha, from which it derives. The upper-case version consists of two more or less vertical lines, joined at the top, and crossed in their middle by a horizontal bar."@en .

Príklad vstupných dát - Wikipedia:

"<abstract>"English articles}}"</abstract>"

Výstup programu:

Program bude porovnávať text ktorý sa nachádza medzi <abstract></abstract> pri wikipedii. U DBPedie sa abstrakt nachádza medzi "".

Pri zistení prvej nezhody, program zahlási, že abstrakt nie je rovnaký a podobne bude pokračovať ďalej.

Na konci zahlási štatistické informácie po prehľadaní dodaných súborov.
