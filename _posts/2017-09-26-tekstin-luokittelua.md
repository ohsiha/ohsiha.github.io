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
