---
layout: default
title: Tekstin luokittelua
---

Tekstin luokitteleminen on eräs laskennallisen kielitieteen sovelluksista.
Se soveltuu hyvin esimerkiksi sosiaalisen median sisältöjen luokittelemiseen vaikkapa niiden tunnesävyn perusteella.

Vaiheet:

1. Kerätään data (esimerkiksi Twitterin REST-rajapinnan avulla)
1. Tuotetaan opetusaineisto tai hyödynnetään olemassa olevaa aineistoa
1. Jalostetaan dataa. Ensimmäinen vaihe on sanojen palauttaminen perusmuotoon
1. Tuotetaan yksittäisiä sisältöjä edustavat sanapussit (bag-of-words)
1. Suodatetaan pois merkityksettömät sanat (stopwords)
1. Painotetaan sanojen merkittävyyttä niiden informaatioarvon perusteella - avuksi esimerkiksi TD-IDF
1. Opetetaan luokittelija
1. Arvioidaan luokittijan suorituskykyä ja hienosäädetään kunnes se on riittävä
1. Luokitellaan aineisto kokonaisuudessaan

Aineistoa:

* https://twitter.com/tuomassalo/status/912563287568601088
* Machine Learning, NLP: Text Classification using scikit-learn, python and NLTK. [(Shaikh, 2017)] (https://medium.com/towards-data-science/machine-learning-nlp-text-classification-using-scikit-learn-python-and-nltk-c52b92a7c73a)
* A journey to Dockerize Voikko & Python App [(Karhunen, 2017)](https://janikarhunen.fi/a-journey-to-dockerize-voikko-and-python-app.html)
* Tiedoksi Sukija-sovellus: Puheenvuorot.kansanmuisti.fi (ja	hiukan sanoja) [(Salo, 2011)](http://lists.puimula.org/pipermail/voikko/2011-November/001637.html)
