# The Network of Intellectual Cooperation
*[Martin Grandjean](http://www.martingrandjean.ch) University of Lausanne* 

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1257287.svg)](https://doi.org/10.5281/zenodo.1257287)

## ABOUT ##
Source files of a network analysis based on the archives of the League of Nations' [International Committee on Intellectual Cooperation](https://en.wikipedia.org/wiki/International_Committee_on_Intellectual_Cooperation) (ICIC) between 1919 and 1927. These data are made public and available to the community for testing, further analysis, or simply as a training data set.

To cite this data set: 

> GRANDJEAN Martin (2018). *The Network of Intellectual Cooperation*, Data set, https://github.com/grandjeanmartin/intellectual-cooperation. DOI [10.5281/zenodo.1257287](https://doi.org/10.5281/zenodo.1257287)

To cite the 2018 thesis:

> GRANDJEAN Martin (2018). *Les réseaux de la coopération intellectuelle, la Société des Nations comme actrice des échanges scientifiques et culturels dans l'entre-deux-guerres*, Université de Lausanne, Lausanne, 600p. [[PDF here](https://halshs.archives-ouvertes.fr/tel-01853903)]

To cite the 2026 book:
> GRANDJEAN Martin (2026). *La coopération intellectuelle. Relations scientifiques et diplomatie culturelle à la Société des Nations (1919–1939)*, Neuchâtel, Editions Alphil-Presses Universitaires Suisses. [[PDF here](https://www.alphil.com/accueil/1484-1842-la-cooperation-intellectuelle-.html)] 

## BOOK DATA ##
<img src="https://raw.githubusercontent.com/grandjeanmartin/intellectual-cooperation/master/book/images/fig%201.10.png" alt="the network of intellectual cooperation" width="180" align="right">

### Gephi network

**> FILE 1** NETWORK: GEXF file (A file that can be opened directly with Gephi)

**> FILE 2** NETWORK: (A backup copy of the file that can be opened in Gephi Lite, see "Interactive network visualization" below)

### Figures

**> FOLDER** All the illustrations from the book are included in the [book/images](https://github.com/grandjeanmartin/intellectual-cooperation/tree/master/book/images) folder. But it's easier to view them through the [companion website](https://intellectualcooperation.org/la-cooperation-intellectuelle), which allows you to load them more efficiently. PNG 150dpi (72dpi for the large ones), ask the author if you want high quality versions.

### Companion website

**> FILE 3** WEBSITE: HTML page (This is actually a backup copy of the one currently displayed on [intellectualcooperation.org/la-cooperation-intellectuelle](https://intellectualcooperation.org/la-cooperation-intellectuelle))

## THESIS DATA ##
### Base data
<img src="https://raw.githubusercontent.com/grandjeanmartin/intellectual-cooperation/master/images/1mode.png" alt="1-mode network" width="180" align="right">

**> FILE 4** EDGES: [CSV file containing 26.5K lines](https://github.com/grandjeanmartin/intellectual-cooperation/blob/master/data/IntellectualCooperation_edges.csv) (source, target, type, weight)

**> FILE 5** NODES: [CSV file containing 3.2K lines](https://github.com/grandjeanmartin/intellectual-cooperation/blob/master/data/IntellectualCooperation_nodes.csv) (id, name, first name, affiliation, gender, indexations)

**> FILE 6** METRICS: [PDF file containing 2.8K lines](https://github.com/grandjeanmartin/intellectual-cooperation/blob/master/data/IntellectualCooperation_metrics.pdf) (indexations, degree, weighted degree, closeness, betweenness, eigenvector) [Also available as a CSV](https://github.com/grandjeanmartin/intellectual-cooperation/blob/master/data/IntellectualCooperation_metrics.csv)

### Multilevel data
<img src="https://raw.githubusercontent.com/grandjeanmartin/intellectual-cooperation/master/images/multilayer.png" alt="1-mode network" width="180" align="right">

This additional dataset is built on the previous one by adding level 1 nodes (organizations), level 2 nodes (top organizations), internal edges in these layers (with a weight >1 to be more visible) and affiliation edges between the layers. 

**> FILE 7** EDGES: [XLSX file containing 29.8K lines](https://github.com/grandjeanmartin/intellectual-cooperation/blob/master/data/Multilayer_edges.xlsx) (source, target, type, weight, level)

**> FILE 8** NODES: [XLSX file containing 3.2K lines](https://github.com/grandjeanmartin/intellectual-cooperation/blob/master/data/Multilayer_nodes.xlsx) (id, name, first name, affiliation, gender, indexations, level name, level number)

The proposed visualization has been produced with the *Network Splitter 3D* Gephi plugin.

### Additional data
A file that explains the meanings of the abbreviations used to classify the nodes above.

**> FILE 9** CLASSIFICATION: [CSV file containing 41 lines](https://github.com/grandjeanmartin/intellectual-cooperation/blob/master/data/classification.csv) (abbreviated category, category name, group of categories)

## INTERACTIVE NETWORK VISUALIZATION ##
Forthcoming

## LICENCE ##
The data is shared under a CC-BY-SA 4.0 License.

## OTHER PUBLICATIONS ##
Papers using these data sets :

> GRANDJEAN Martin (2019). *Analyzing and Visualizing the Complexity and Multidimensionality of an Historical Network*, DARIAH-CH. [PDF](https://serval.unil.ch/notice/serval:BIB_411B82F235BC)

> GRANDJEAN Martin (2018). *Towards the Formalization of Metadata Network Analysis in History: a Complex and Multidimensional Case Study*, DARIAH-CH. [PDF](https://halshs.archives-ouvertes.fr/halshs-01899945)

> GRANDJEAN Martin (2017). *Analisi e visualizzazioni delle reti in storia : l'esempio della cooperazione intellettuale della Società delle Nazioni*, Memoria e Ricerca, 25, 2, 371-393. DOI [10.14647/87204](https://www.rivisteweb.it/doi/10.14647/87204) / [PDF in french](https://halshs.archives-ouvertes.fr/halshs-01610098) / [Summary](http://www.martingrandjean.ch/complex-structures-and-international-organizations/)

> GRANDJEAN Martin (2017). *Multimode and Multilevel: Vertical Dimension in Historical and Literary Networks*, Digital Humanities 2017. [PDF](https://halshs.archives-ouvertes.fr/halshs-01525539)

> GRANDJEAN Martin (2016). *Archives Distant Reading: Mapping the Activity of the League of Nations' Intellectual Cooperation*, Digital Humanities 2016, 531-534. [PDF](https://halshs.archives-ouvertes.fr/halshs-01525565)

> GRANDJEAN Martin (2016). *Social Network Analysis of the League of Nations' Intellectual Cooperation, an Historical Distant Reading*, Digital Humanities Benelux 2016. [PDF](https://halshs.archives-ouvertes.fr/hal-01525570v1)

> GRANDJEAN Martin (2015). *Introduction à la visualisation de données : l'analyse de réseau en histoire*, Geschichte und Informatik, 18/19, 109-128. [PDF](https://halshs.archives-ouvertes.fr/halshs-01525543)

> GRANDJEAN Martin (2014). *La connaissance est un réseau : perspective sur l'organisation archivistique et encyclopédique*, Les Cahiers du Numérique, 10, 3, 37-54. DOI [10.3166/lcn.10.3.37-54](https://www.cairn.info/revue-les-cahiers-du-numerique-2014-3-p-37.htm) / [PDF](https://halshs.archives-ouvertes.fr/halshs-01525545)

