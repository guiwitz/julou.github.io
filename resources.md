---
layout: page
title: Resources
# permalink: /resources/
# navigation_weight: 0
---

*toward an open lab / reproducible practices in research:*  

Whether research should be *absolutely* reproducible is a complicated question, nonetheless I do believe than one should be able to reproduce ones own analysis without pain (even in the future) and to share them along with the publications. This may sound all obvious, but not be so easy to achieve in practice!

Here are some tips for students, based on my iterations toward more reproducible practices:

- Start from the beginning: although it may sometimes feel like a waste of time, putting yourself in the situation to redo your analysis easily will make your researcher's life easier (and to the very least help you to rerun chuncks from earlier work).

- For each usual task (data analysis, plotting, citing references), you should master one tool down to its dirty details.

- Relying on text-based formats (e.g. Markdown, LaTeX, CSV) is critical in order to be able to use version control to maintain your code, to write manuscripts, etc. This may indeed guide your choice of tools. A good starting points ot learn version control with `git` is the [Software Carpentry tutorial](https://swcarpentry.github.io/git-novice/). [GitHub's documentation](https://help.github.com) provides help on more advanced topics.


## handling data

- For data analysis and plotting, I enjoy very much (most of the time!) working with `R`'s [`tidyverse`](https://www.tidyverse.org), in particular `dplyr` and `ggplot2`. If you are new to R or to data analysis from the command line, the companion book *R for Data Science* (available [online](http://r4ds.had.co.nz)) is the best introduction you can dream of. My advice: study sections 2 to 8 thoroughly, the next ones will be useful to go deeper on specific topics based on your needs.  
Hint: if you need to speed up your analysis with `dplyr` have a look at its parallelized counterpart [`multidplyr`]().

- Follow simple guidelines when [recording data in spreadsheets](http://blog.revolutionanalytics.com/2017/11/good-practices-spreadsheets.html)


## handling text

- Despite LaTeX's popularity in quantitative fields, I believe that the time is ripe to leave it to advanced editing where microtypography matters... Simpler syntaxes (in particular Markdown) are sufficient for literate data analysis (e.g. with Rmarkdown or R notebooks) and even for more advance tasks like [writing a dissertation](https://github.com/tompollard/phd_thesis_markdown) or [an article](https://github.com/rstudio/rticles). Whatever format you choose to rely on, don't miss that `pandoc` is an incredibly powerful conversion tools between most formats (.md, .tex, .rtf, .docx, etc).  
Hint: the Markdown converter used by RStudio (`pandoc-citeproc`) is able to handle citations just like bibtex would (and in fact simpler!).

- For storing and citing articles, [Zotero](https://zotero.org) is the most versatile open-source software. <!-- However, its user experience is a bit rough on the edges: it took me a while to go back to it after using Papers during three years. Check [my tips to streamline saving,  storing, and citing](). -->



## handling DNA sequences

- [Benchling](https://benchling.com) is the 21st century sequence editor to design and keep track of your molecular biology experiments: design primers, align sequencing chromatograms, test your next cloning *in silico*. It even as an integrated lab notebook!  
Big drawback: your data must be hosted on their servers...


## handling microscopy data

- [Micro-Manager](https://micro-manager.org) is an open-source software for microscope control. If your hardware falls in the list of (over 200) supported items, it is very easy to configure and can be extended to support advanced features such as hardware triggering (on which we wrote a step-by-step tutorial). 

- A smooth [introduction lecture to fluorescence microscopy](https://www.ibiology.org/ibioeducation/taking-courses/ibiology-microscopy-short-course/introduction-to-fluorescence-microscopy-2.html).

<!-- - *archiving/browsing microscopy images (fiji, omero, bioformats) -->


## academia survival kit

- Uri Alon's [materials for nurturing scientists](http://www.weizmann.ac.il/mcb/UriAlon/materials-nurturing-scientists)
- [*Some Modest Advice for Graduate Students*](http://onlinelibrary.wiley.com/doi/10.2307/20166580/full) by S. Stearns and R. Huey's [*Reply to Stearns: Some Acynical Advice for Graduate Students*](http://onlinelibrary.wiley.com/store/10.2307/20166581/asset/bes21987682150.pdf?v=1&t=jauajito&s=d0bcc7d5cc17ded6f0410b8e9fc808b64d4a7e51).
- Writings such as B. Latour's [*Petites leçons de sociologie des sciences*]() and I. Stengers' [*Sciences et pouvoirs*]() ([*Power and invention*](https://www.upress.umn.edu/book-division/books/power-and-invention)) have helped me to overcome various academic frustrations and hopefully to fight their causes. [*Making genes, making waves*]() by J. Beckwidth is another inspiring read.
- L'Atelier des Jours à Venir, a French non-profit company promoting reflexive and responsible research practices, gathered valuable [resources](resources).
<!-- - contribution NKI -->
- On research integrity:
  + [Scientific Red Cards](https://scientificredcards.wordpress.com) 
  + [Workshops](http://www.joursavenir.org/activities/university-courses) by l'Atelier des Jours à Venir.
  + [Retraction Watch](https://retractionwatch.com) 
  + [PubPeer](https://pubpeer.com)
  <!-- + blog post -->
  