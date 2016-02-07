# Wikipedia annotated articles

### Description

This corpus contains 30 Wikipedia article pairs in English and Spanish. 
The articles correspond to three domains in equal proportions: Computer Science, 
Science, and Sports.

Two volunteers, native speakers of Spanish with high command of English, annotated  it manually at sentence level considering three classes: parallel, comparable, and other. The mean agreement between annotators had a kappa coefficient of κ∼0.7. A third annotator resolved disagreed sentences.


### Contents

- README.txt 	- This file  
- annotations/	
  - Folder with the annotations, one file per article pair with 
		  name ID_es.es.ann.csv, where ID_es corresponds to the ID of 
		  the Wikipedia article in Spanish in the pair.    
- documents/	
   - Folder with the articles in raw format, one file per article 
		  and language. The naming convention is ID_es.es.txt and 
		  ID_en.en.txt  

   - documents.txt file linking the IDs of each pair, one pair per 
  		  line. The length of the articles is also included.


### Format

The format of the annotations is as follows:  
```
#line_es    #line_en               class  
      26	      34     translated-real  
      11	      14	 comparable-real  
```

Only parallel (translated-real) and comparable (comparable-real) relations are
included.

### Citation

Please, cite the following paper if you use this corpus in your work:

Alberto Barrón-Cedeño, Cristina España-Bonet, Josu Boldoba and Lluís Màrquez.
*A Factory of Comparable Corpora from Wikipedia*.
In Proceedings of the 8th Workshop on Building and Using Comparable Corpora 
(BUCC 2015), pages 3-13, July 2015, Beijing, China


# Wikipedia parallel sets 

### Description

wkSets.tar.gz contains two datasets with parallel sentences in English and Spanish. The sentences correspond to three domains in equal proportions: Computer Science, Science, and Sports. 

The sets were obtained in a semiautomatic way. We departed from parallel corpora 
gathered automatically and sentences with more than four tokens and beginning with a letter were selected as candidates for the final sets. We estimated its perplexity with respect to a language model obtained with Europarl in order to select the most fluent sentences. Then, the parallel sentences were ranked according to their similarity and perplexity. The top-*n* fragments were manually revised and extracted to build these Wikipedia sets.

### Contents

- README.txt     &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;   - This file  
- wk.test.tok.en  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - Set1 (test) 1500 tokenised sentences in English
- wk.test.tok.es  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - Set1 (test) the corresponding parallel sentences in Spanish
- wk.dev.tok.en   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - Set2 (dev) 900 tokenised sentences in English
- wk.dev.tok.es   &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; - Set2 (dev) the corresponding parallel sentences in Spanish

### Citation

Please, cite the following paper if you use this corpus in your work:

Alberto Barrón-Cedeño, Cristina España-Bonet, Josu Boldoba and Lluís Màrquez.
*A Factory of Comparable Corpora from Wikipedia*.
In Proceedings of the 8th Workshop on Building and Using Comparable Corpora 
(BUCC 2015), pages 3-13, July 2015, Beijing, China



