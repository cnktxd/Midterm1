---
title: "Nuclear Explosion Testings"
author: 
  - Soyugur, Cankat[^1]
bibliography: ../bibliography/biblio.bib
csl: ../csl/apa.csl
header-includes:
  - \usepackage{polyglossia}
  - \setmainlanguage{english}
  - \usepackage{booktabs}
  - \usepackage{caption} 
  - \captionsetup[table]{skip=10pt}
output:
  bookdown::pdf_document2:
    fig_caption: yes
    fig_height: 3
    fig_width: 4
    keep_tex: no
    latex_engine: xelatex
    number_sections: yes
    toc: no
geometry: margin=1in
link-citations: yes
urlcolor: blue
fontsize: 12pt
biblio-style: apalike
---


<!-- ======================================================================= -->
<!-- ============================== FOOTNOTES ============================== -->
<!-- ======================================================================= -->
[^1]: 20080501, [Github Repo](https://github.com/cnktxd/Midterm1.git)


# Introduction

The purpose of my work is to investigate the dataset about nuclear explosions. By editing the given dataset, I removed the rows that included "NA" values and also deleted the columns that were no use to me such as "magnitude_body" and "magnitude_surface". The other variables are: date_long(Shows the complete date of the testing), year, country(Which country conducted the test), region(Where the test was conducted at), latitude, longitude, depth, yield_lower, yield_higher, purpose(Why the test was conducted for), name(Name of the detonated warhead) and type(How the nuclear test was conducted). I found this data from "https://github.com/rfordatascience/tidytuesday". With cropping the rows that had "NA" values, I have 1382 entries in total.

The questions I decided on are "In which test site did the USA conduct the most nuclear tests?" and "Where did France conduct it's nuclear tests at". These questions are related to the 4 articles I have found and they provided me with extra information I stated in the literature review section. Also from the dataset, I can gather the needed data by using some functional codes. 

## Literature Review

Even though the literature I found is mostly made of data from the testings of nuclear weapons, the 4 articles and reports I found also include and give valuable information about the questions I am asking.

For the first question, which is "In which test site did the USA conduct the most nuclear tests?". The US is shown to have conducted almost all of it's nuclear tests in Nevada Test Site or NTS as an abbreviation. Before the tests at NTS, USA conducted it's tests at various places around the pacific as given in quote: [@bergkvist:2000] "Nuclear weapon development continued in the USA and tests were conducted in 1946-62 at various atolls and islands in the Pacific Ocean. The first hydrogen bomb was tested in 1951, at Enewetak Atoll, then part of a UN Trust territory administered by the USA, now part of the Marshall Islands.".In the introduction section of the article from [@anaïs:2016] it is stated how many tests were conducted and how big of a yield the tests had at the NTS is stated, which is also relevant to my first question with quote: "At the Nevada Test Site (NTS) northwest of Las Vegas, Nevada, 928 above- and below-ground nuclear tests occurred between 1951 and 1992. There were nearly 90 tests at the NTS in 1962 alone (NTS interviewee). Bombs of 61 and 74 kilotonnes were detonated at the NTS during the 1950s – by contrast, the bomb dropped on Hiroshima had a nuclear yield of approximately 15 kilotonnes."

For the second question which is "Where did France conduct it's nuclear tests at?", information about the French nuclear tests are less shared to the public than the USA's nuclear tests because of various reasons. These reasons include the failures of the tests, the health problems created by the test as stated in [@danielsson:1984] with quote: "Most political, church and civic leaders in French Polynesia immediately voiced strong fears that any nuclear tests made in the Tuamotus might, as the American tests did in Micronesia, adversely affect the health of the 7 000 people living there." and "By the beginning of July 1966, after three years of intense preparations, the Moruroa testing base was operational. The first bomb was placed on a barge anchored in the lagoon and detonated. The result was a catastrophe-all the water contained in the shallow reef basin was sucked up into the air and then rained down, covering all islets with heaps of irradiated fish and clams, whose slowly rotting flesh continued to stink for weeks." However, from [@willis:2006] it can be said that the testing of the French warheads were mostly conducted in the French Polynesia, especially in Moruroa and Tuamotus islands, but these were also not that effective and therefore, were not reported as after the failure of the first few tests, the types of which were "SURFACE" and "TOWER", the French converted to different types of testing types. 






\newpage
# References {#references}
<div id="refs"></div>

