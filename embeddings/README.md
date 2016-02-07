********************************************************************************
```PLEASE, contact me if you want the models as they do not fit here! ```
********************************************************************************

### Description

Embeddings for English, Spanish and German with billion words (except for words!). 
The embeddings have been obtained using the CBOW algorithm implemented in Word2vec [1], using a window of 5 tokens and a dimension of either 50 or 300 elements.


Size of the original corpora (Europarl/Quest+Wikipedia):

``` 
  Lines        Words          Language
  105.117.852  2.267.380.415  all.en.tok
   32.918.712    842.585.552  all.es.tok
   40.956.648    728.949.587  all.de.tok
```

Size of the models: 

```
   5.1G  all.de.300.w2v
   884M  all.de.50.w2v
   5.4G  all.en.300.w2v
   938M  all.en.50.w2v
   2.3G  all.es.300.w2v
   392M  all.es.50.w2v
```

Reference
----------

[1] Tomas Mikolov, Kai Chen, Greg Corrado, and Jeffrey Dean. 
    *Efficient Estimation of Word Representations in Vector Space*. 
    In Proceedings of Workshop at ICLR, 2013.

