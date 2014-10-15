VI_FIIT_projekt
================

Projekt na vyhladavanie info.. repozitár, ktorý obsahuje informácie o projekte

Vstupné a výstupné dáta
================

Ukážka vstupných dát je v adresári /data.

sample_dbpedia_long_abstracts_en.xml - ukážka vstupných dát z dbpedie

sample_enwiki-latest-abstract.xml - ukážka vstupných dát z wikipedie

Ukážka výstupných dát je v adresári /data.

sample_abstract-output.xml

Ukážka fungovania
===================

Príklad vstupných dát - DBPedia:

"A (named a /ËˆeÉª/, plural aes) is the first letter and vowel in the ISO basic Latin alphabet. It is similar to the Ancient Greek letter alpha, from which it derives. The upper-case version consists of two more or less vertical lines, joined at the top, and crossed in their middle by a horizontal bar."@en .

Príklad vstupných dát - Wikipedia:

English articles}}

Výstup programu:

Program bude počítať výskyt jednotlivých slov zo vstupu a počítať podobnosť výskytu pre celkový objem slov pre daný abstrakt. V oboch prípadoch aj pri wiki aj pri dbpedie a pri výskyte rovnakého slova porovnáme početnosť výskytu.

DBPedia: A (named a /ˈeɪ/, plural aes) is the first letter and vowel in the ISO basic Latin alphabet. It is similar to the Ancient Greek letter alpha, from which it derives. The upper-case version consists of two more or less vertical lines, joined at the top, and crossed in their middle by a horizontal bar.

Wiki: English articles}}

a 3 / 55		English 1 / 2
named 1 / 55		articles 1 / 2 
eɪ 1 / 55
plural 1 / 55
aes 1 / 55
is 2 / 55
the 5 / 55
first 1 / 55
letter 1 / 55	
and 2 / 55
vowel 1 / 55
in 2 / 55
ISO 1 / 55
basic 1 / 55
Latin 1 / 55
alphabet 1 / 55
It 2 / 55
similar 1 / 55 
to 1 / 55
Ancient 1 / 55
Greek 1 / 55
letter 1 / 55
alpha 1 / 55
from 1 / 55
which 1 / 55
derives 1 / 55
upper-case 1 / 55
version 1 / 55
consists 1 / 55
of 1 / 55
two 1 / 55
more 1 / 55
or 1 / 55
less 1 / 55 
vertical 1 / 55
lines 1 / 55
joined 1 / 55
at 1 / 55
top 1 / 55		
crossed 1 / 55
their 1 / 55
middle 1 / 55
by 1 / 55
horizontal 1 / 55
bar 1 / 55

Vysledok podobnosti: 0
