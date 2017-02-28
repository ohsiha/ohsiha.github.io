---
layout: default
title: Luentopäiväkirja / OHSIHA 2017
---

Tämä on Ohjelmallisen sisällönhallinnan kevään 2017 toteutuskerran luentopäiväkirja. Toteutus noudattelee [vuoden 2016 toteutuskertaa](https://iislab.ee.tut.fi/piiri/ohjelmallinen-sis%C3%A4ll%C3%B6nhallinta-2016/wiki/luentop%C3%A4iv%C3%A4kirja). Alan dynaamisuudesta johtuen sisältöjä ja toteutustapaa kuitenkin kehitetään jatkuvasti.

# Luentopäiväkirja 

Tulossa:

<!-- * perjantaina 17. helmikuuta: [Vaali- ja Wikidatahackathon](https://ohsiha.github.io/2017/02/06/Vaali-ja-Wikidata-hackathon)  -->
* maanantaina 13. maaliskuuta kello 14: [APIOps goes Tampere University of Technology](https://www.meetup.com/APIOps-Tampere/events/237342343/)
* maanantaina 27. maaliskuuta kello 13 (Tampereen yliopisto): Data, analytiikka ja journalismi (Teemo Tebest)

## Luentoviikko 4.1 (viikko 10) SUDL ja teknologiademoja

Maanantaina 6. maaliskuuta kello 14.15 Jussi Hannunen esittelee Smart University Design Labin ja kello 15.10 Mikael Lagerbom demoaa Node.js-kehitystä, ks. [SUDL-vierailu ja Node.js-demo](https://ohsiha.github.io/2017/02/28/sudl-ja-nodejs.html). Koodiklinikalla on esittelyssä Django.

## Luentoviikko 3.7 (viikko 8) Sisällönhallinta- ja julkaisujärjestelmät

[Esitys](luento/37/esitys.pdf) PDF-muodossa.

Luento käyntiin sivupohjamoottoridemolla ([markdown](https://github.com/jukkahuhtamaki/pcm-demo/tree/master/markdown), [flask/template](https://github.com/jukkahuhtamaki/pcm-demo/blob/master/flask/templates/visualize.html))  
Sisällönhallinta- ja julkaisujärjestelmien toiminnallisuus. 
Data, informaatio ja sisältö. 
Ja niin edelleen, ks. esitys. 
Keskustelua ja esimerkkejä [automatisoinnista](02/20/automaatio.html.
Koodiklinikalla Jouni Veiman vetämä [Bootstrap](http://getbootstrap.com/)-demo.

## Luentoviikko 3.6 (viikko 7) Verkkopalvelun arkkitehtuuri ja yleinen toiminnallisuus

[Esitys](luento/36/esitys.html) hypertekstinä.

[Harjoitustyöohje](harjoitustyo) on julkaistu.

Luento käyntiin [Flask-demolla](https://github.com/jukkahuhtamaki/pcm-demo/tree/master/flask). 
Asiakas-palvelin -malli vs. kolmikerrosmalli, 
verkkopalvelun keskeinen toiminnallisuus (pääsynhallinta, käyttäjän tunnistaminen, käyttöoikeuksien hallinta), 
lomakkeet (ks. [lomake-elementit](http://matriisi.ee.tut.fi/hmopetus/hm-ohj/2012/demo/html-lomakkeet/lomake-elementit.html), 
[ehdottava](http://matriisi.ee.tut.fi/hmopetus/ohsiha/2014/demo/lomake/ehdottava.html)), 
istuntojen hallinta (evästeet), 
esimerkkejä (ks. [http-perusautentikointi](http://matriisi.ee.tut.fi/hmopetus/ohsiha/2015/demo/verkkopalveluarkkitehtuuri/http-perusautentikointi.php), 
[istunto](http://matriisi.ee.tut.fi/hmopetus/ohsiha/2015/demo/verkkopalveluarkkitehtuuri/istunto.php)), 
verkkopalvelun tietoturva, 
verkkopalvelujen yleisiä ominaisuuksia, 
uudelleenkäytettävyys ja verkkopalvelun toteuttaminen, 
<!-- katsaus <a href="https://fi.wordpress.org/">Wordpress</a>-järjestelmään (ks. <a href="http://codex.wordpress.org/Installing_WordPress_Locally_on_Your_Mac_With_MAMP">asennusohje</a>, <a href="http://codex.wordpress.org/The_Loop">The Loop</a>), 
 -->
esimerkkejä verkkopalvelujen toiminnallisuudesta. 
Koodiklinikalla katsastetaan erilaisia Web-sovelluskehyksiä.  
<!-- <a href="https://iislab.ee.tut.fi/piiri/ohjelmallinen-sis%C3%A4ll%C3%B6nhallinta-2016/blog/nodejs-demo-2522016">Node.js-demo</a>. </p>-->

Linkkejä ja lisätietoa:

<ul>
<li>Web-lomakkeiden tulevaisuudesta
<ul>
<li><a class="ext" href="http://24ways.org/2009/have-a-field-day-with-html5-forms" rel="bookmark" target="_blank">Have a Field Day with HTML5 Forms</a> (<a class="ext" href="http://yaili.com/" target="_blank">Inayaili de León</a>)</li>
<li><a class="ext" href="http://www.html5rocks.com/en/tutorials/forms/html5forms/" target="_blank">Making Forms Fabulous with HTML5</a> (<a class="ext" href="http://www.html5rocks.com/profiles/#%21/jankleinert" target="_blank">Jan Kleinert</a>)</li>
<li><a class="ext" href="https://developer.mozilla.org/en/AJAX/Getting_Started" target="_blank">AJAX: Getting Started</a> (developer.mozilla.org)</li>
<li><a class="ext" href="http://www.alistapart.com/articles/behavioralseparation" target="_blank">Behavioral Separation</a> (Jeremy Keith)</li>
<li><a class="ext" href="http://www.alistapart.com/articles/understandingprogressiveenhancement" target="_blank">Understanding Progressive Enhancement</a> (<a class="ext" href="http://www.alistapart.com/authors/g/aarongustafson" target="_blank">Aaron Gustafson</a>)</li>
</ul>
</li>
<li>HTML-lomakkeet, HTTP ja CSS
<ul>
<li><a class="ext" href="http://www.w3.org/TR/html4/interact/forms.html" target="_blank">Forms in HTML documents</a> (w3.org)</li>
<li><a class="ext" href="http://www.w3.org/2001/tag/doc/whenToUseGet.html" target="_blank">URIs, Addressability, and the use of HTTP GET and POST</a> (w3.org)</li>
<li><a class="ext" href="http://www.w3.org/TR/webarch/" target="_blank">Architecture of the World Wide Web, Volume One</a> (w3.org)</li>
<li><a class="ext" href="http://www.alistapart.com/articles/practicalcss" target="_blank">Practical CSS Layout Tips, Tricks, &amp; Techniques</a> (<a class="ext" href="http://www.alistapart.com/authors/n/marknewhouse" target="_blank">Mark Newhouse</a>)</li>
</ul>
</li>
<li>PHP ja tietoturva
<ul>
<li><a class="ext" href="https://www.owasp.org/index.php/Cheat_Sheets" target="_blank">OWASP Cheat Sheets</a> (owasp.org)</li>
<li><a class="ext" href="http://php.net/manual/en/faq.passwords.php" target="_blank">Safe Password Hashing</a> (php.net)</li>
</ul>
</li>
<li>HTTP-tehokäyttö
<ul>
<li><a href="http://docs.python-requests.org/en/master/">Requests</a></li>
<li><a href="https://chrome.google.com/webstore/detail/postman/">Postman</a> </li>
</ul>
</li>
<li>Sovelluskehykset, esimerkkejä
<ul>
<li><a class="ext" href="http://codeigniter.com/" target="_blank">CodeIgniter</a> <span>(codeigniter.com)</span></li>
<li><a class="ext" href="http://www.djangoproject.com/" target="_blank">Django</a> (djangoproject.com)</li>
<li><a class="ext" href="http://www.rubyonrails.org/" target="_blank">Ruby on Rails</a> (rubyonrails.org)</li>
</ul>
</li>
<li>Ohjelmistokomponentit ja funktiokirjastot, esimerkkejä
<ul>
<li><a class="ext" href="http://magpierss.sourceforge.net/" target="_blank">MagpieRSS: RSS for PHP</a> (magpierss.sourceforge.net)</li>
<li><a class="ext" href="http://simplepie.org/" target="_blank">SimplePie</a></li>
<li><a class="ext" href="http://ckeditor.com/" target="_blank">CKEditor</a> (idly.org)</li>
<li><a class="ext" href="http://adodb.sourceforge.net/" target="_blank">ADOdb Database Abstraction Library for PHP</a> (adodb.sourceforge.net)</li>
<li><a class="ext" href="http://pear.php.net/" target="_blank">PEAR - PHP Extension and Application Repository</a> (pear.php.net)</li>
<li><a class="ext" href="http://html5boilerplate.com/" target="_blank">HTML5 Boilerplate</a> (html5boilerplate.com)</li>
</ul>
</li>
<li>Uudelleenkäytettävien ratkaisujen lähteitä
<ul>
<li><a class="ext" href="https://github.com/search?q=php&amp;type=Everything&amp;repo=&amp;langOverride=&amp;start_value=1" target="_blank">Search: php - GitHub</a></li>
</ul>
</li>
<li>Avoimen lähdekoodin lisensseistä
<ul>
<li><a class="ext" href="http://en.wikipedia.org/wiki/Open-source_license" target="_blank">Open-source license</a> (wikipedia.org)</li>
<li><a class="ext" href="http://www.onlamp.com/pub/a/onlamp/2004/11/18/licenses.html" target="_blank">Open Source Licenses Are Not All the Same</a> (Stephen Fishman)</li>
</ul>
</li>
</ul>

## Luentoviikko 3.5 (viikko 6): Tiedon koostaminen ja hallinta

Viikon sisällöt [erillisellä sivulla](02/06/Tiedon-koostaminen-ja-hallinta).

Kolmikerrosmalli. GET vs. POST. API first. Raapijat, ryömijät ja rajapinnat esimerkkien kautta. Tiedon tallentaminen ja hallinta: MongoDB. Keskiviikon Koodiklinikalla käydään läpi laajempi esimerkki Twitter-datan keräämisestä ja analyysistä (ks. [demo-twitter-collector](https://github.com/jukkahuhtamaki/demo-twitter-collector)).

## Luentoviikko 3.4 (viikko 5): Resurssista representaatioksi

Johdatus hypermediaan (ks. [opintojaksokuvaus](http://www.tut.fi/wwwoppaat/opas2015-2016/perus/laitokset/Matematiikka/MAT-80000.html)) 90 minuutissa. URI-tunniste, resurssi, representaatio. 
Demo: twiitti resurssina (ks. [simple_read.py](https://github.com/jukkahuhtamaki/pcm-demo/blob/master/twitter-api/simple_read.py)). 
HTML, CSS ja Javascript: sisältö, esitystapa, toiminnallisuus. 
Taustaa tarkemmin: Learn [HTML &amp; CSS](https://www.codecademy.com/learn/web), [Javascript](https://www.codecademy.com/learn/javascript).
Edistyneille: [Bootstrap](http://getbootstrap.com/). 
Koodiklinikalla perehdytään [Firebaseen](https://firebase.google.com/), ks. [demon kuvaus](https://github.com/piehei/ohsiha-firebase-demo).

## Luentoviikko 3.3 (viikko 4): Käytännöt ja katsaus ohjelmallisen sisällönhallinnan nykytilaan 

Toteutuskerran avausluento järjestetään maanantaina 23. tammikuuta 2017 kello 14.15 salissa SJ204.

Esitys [hypertekstinä](luento/01/esitys).

Aiheet: Opintojakson ja kevään toteutuskerran esittely ja suorittamisen käytännöt. Koodiklinikalla katselmoidaan  [ohjelmallisen sisällönhallinnan tilaa vuonna 2017](01/25/OHSIHA-vuonna-2017).