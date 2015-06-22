---
layout: default
title: Data
permalink: /data/
---
### Our Data

[![Knoedler Dataset](http://i.imgur.com/OMKPN81.png "Knoedler Dataset")](https://drive.google.com/file/d/0B0yBC2pH_uAwanZmSHhET05WZkk/view?usp=sharing)

Click [here](https://drive.google.com/file/d/0B0yBC2pH_uAwanZmSHhET05WZkk/view?usp=sharing) to go to our project's Google Drive where we're hosting a clean data set of the first six stock books of the Knoedler Gallery Archive. This data was exported from the [](http://www.getty.edu/research/tools/provenance/search.html)Getty Provenance Index database.

### About Our Data

As described in the History section of our website, this dataset is the result of countless hours transcribing handwritten stock books. There are multiple levels of human interaction with the data that results in no small number of idiosyncrasies and inconsistencies. This is a simple reality of working with structured data and it proves to be a major challenge when working with visualization software that can only be successful when the data is consistent.

### Challenges: Location

One particular challenge we came across is determining location names. Over the course of the thousands of entries one can find references to English, French, and vernacular or local-language names for the same city. Diacritics are not universally applied, so that searches for the accurate vernacular München (Munich) will miss the countless Munchen entries.

A similar difficulty emerges on a more domestic level for art objects that were sold in the New York metropolitan area. Each borough, even post-incorporation, may be referred to as a discrete locality, often designated by baffling shorthand (Broo.lyn, Brk.lyn, etc). Furthermore, sales within Manhattan are designated by 'City' or simply a street address. The latter in particular thwarts many of the tools available to data cleaners because the powerful 'find/replace' and 'filter' functions are rendered useless. In the version that is available for download, the major city names have been standardized but the Manhattan locations, much like their real-life counterparts, remain chaotic and unusable. Finally, even when these location fields are standardized most mapping visualization tools can only use coordinate data and, as a result, there is an additional labor of converting the text locations to numeric coordinates.

The date format provided a significant challenge which, much like location names, develops at multiple stages in the process. Although the transcribers do an excellent job of standardizing date information to a mm/dd/yyyy format, the authors of the stock book occasionally abbreviate dates to a simple mm/yyyy format, consigning the exact day to obscurity. In these cases, we have simply used the first day of the month as a place holder (see Data Provenance section below). The next challenge is the way Microsoft Excel and/or Google Docs understands dates and their formatting. In the first place, dates before 1900 can only be treated as raw information, preventing Excel from sorting those dates appropriately. That wouldn't be so bad if one could simply convert all date information to the mm/dd/yyyy format and then treat all date values as raw information so that entries could be sorted chronologically. Instead, Excel employs a bewildering system wherein readable date values (1900 and on) are converted to a nonsensical five digit number when represented as raw information and not 'Date' formatted. The most successful but not entirely satisfying solution we found is detailed in the Data Provenance document.

The Getty Thesaurus of Geographic Names proved an invaluable reference during this phase of data cleaning. Not only does it offer an authoritative name for locations,but geographic coordinates are also included within each entry.

These two examples highly the complexity of operation required to get the data into shape for use in the visualization tools. They also illustrate the many moments in which a researcher alters the data they’ve received. As this alteration is a necessary evil, it is essential that these changes are tracked and detailed, if not only to lend credibility to any results the researcher might publish or present but also for the researcher’s own records (and sanity).

### Challenges: Date

The date format also provides a significant challenge. Much like location names, the data develops at multiple stages in the process. Although the transcribers do an excellent job of standardizing date information to a mm/dd/yyyy format, the authors of the stock book occasionally abbreviate dates to a simple mm/yyyy format, consigning the exact day to obscurity. In these cases, we have simply used the first day of the month as a place-holder (see our Data Provenance document for further information).

The next challenge is the way Microsoft Excel and Google Docs understand dates and their formatting. In the first place, dates before 1900 can only be treated as raw information, preventing Excel from sorting those dates appropriately. That wouldn't be so bad if one could simply convert all date information to the mm/dd/yyyy format and then treat all date values as raw information so that entries could be sorted chronologically. Instead, Excel employs a bewildering system wherein readable date values (1900 and on) are converted to a nonsensical five-digit number when represented as raw information and not 'Date' formatted. The most successful but not entirely satisfying solution we found is detailed in the Data Provenance document. 

These two examples (location and date format) exemplify the complexity of operation required to get the data into shape for use in the visualization tools. They also illustrate the many moments in which a researcher alters the data they’ve received. As this alteration is a necessary evil, it is essential that these changes are tracked and detailed, if not only to lend credibility to any results the researcher might publish or present but also for the researcher’s own records (and sanity). 

### Data Provenance

By definition data provenance is the tracking of changes made in the cleaning of data sets. Click here to view our document. For more information about Data Provenance please refer to our resource page.



