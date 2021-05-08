[![Contributors][contributors-shield]][contributors-url]
[![Issues][issues-shield]][issues-url]

[contributors-shield]: https://img.shields.io/github/contributors/jussihayha/DataTinderit.svg?style=for-the-badge
[contributors-url]: https://github.com/jussihayha/DataTinderit/graphs/contributors
[issues-shield]: https://img.shields.io/github/issues/jussihayha/DataTinderit.svg?style=for-the-badge
[issues-url]: https://github.com/jussihayha/DataTinderit/issues
[product-screenshot]: images/logo_viritys_transparent.png


![logo](./images/DataTinderlogo.JPG)

# Tables of contents
- [Tables of contents](#Tables-of-contents)
  - [About The Project](#about-the project)
  - [Concept](#concept)
  - [Käytetyt tekniikat](#käytetyt-tekniikat)
- [Kuinka pääsen alkuun](#kuinka-pääsen-alkuun)
  - [Ennakkotoimet frontend](#ennakkotoimet-frontend)
  - [Ennakkotoimet backend](#ennakkotoimet-backend)
    - [Arkkitehtuuri](#arkkitehtuuri)
    - [NodeJS](#nodejs)
    - [Python/Azure/Jne](#pythonazurejne)
    - [Tietokanta](#tietokanta)

## About The Project
Tämä repository on osa Haaga-Helia ammattikorkeakoulun Ohjelmistoprojekti II -kurssia. Kurssin tavoittena on luoda uusi sovellus, palvelu tai muita hyödyttävä opensource lisäosa käyttämällä avointa dataa. 

Kurssin yritysyhteistyökumppanina toimi YLE, joka esitteli omia avoimia rajapintojaan ja kertoi toiveistaan ja ideoistaa, että miten niitä voisi hyödyntää.

Päädyimme käyttämään Ylen Areena-rajapintaa, joka tarjoaa tietoa erilaisesta materiaalista, joka on saatavilla Areenan kautta. 

## Concept
Haluamme tarjota käyttäjälle sovelluksen, jolla voi hyödyntää Yle Areenan sisältöä. Konseptille on tarve, sillä Areenassa ei ole käyttäjäsidonnaista suosittelua. ​
Sovelluksemme antaa suosituksia Yle Areenan sisällöstä käyttäjälle, joka voi hyväksyä tai hylätä suositellut ehdotukset Tinderistä tutulla tavalla eli  "swaippaamalla" ne sovelluksen ruudulla oikealle tai vasemmalla. Jos sovelluksen antamasta ehdotuksesta "tykätään" (swaipataan oikealle), ehdotus siirtyy "tykkäsit näistä" -listalle. Jos käyttäjä avaa sovelluksen ensimmäisen kerran niin sovellus kertoo lyhyesti, että käyttäjän tulee swaippailla hetki ohjelmia ja mennä sen jälkeen katsomaan, että mitä suosituksia on saanut. ​
Viiden swaippauksen jälkeen käyttäjä ohjataan siirtymään listaruutuun.
* Listaruutu sisältää käyttäjälle suositeltuja ohjelmia. Suosittelut voivat koostua muiden käyttäjien suosituksista
* Suositussekoitus sisältää muutaman suosituksen knn-suosittelijasta, muutama täysin satunnainen suositus ja muutama tulee sen perusteella mistä käyttäjä on aiemmin tykännyt.
* Listaruudussa voi olla myös top 10 tykätyimmät ohjelmat sekä esimerkkinä vaikka komediat näkyvillä. 
​
## Käytetyt tekniikat

* MongoDB
* Phyton
* React-Native
* Nodejs.

## Kuinka pääsen alkuun
Tässä kappaleessa ohjeet kuinka saat paikallisen kopion käyttöösi.

### Ennakkotoimet frontend
Tässä lista asioista, joita tarvitset ohjelmistojen käyttöön ja kuinka asennus tapahtuu.

## Askel 1
Tee seuraavat ennakkotoimet ja asenna:

  * npm
  * expo CLI
  * expo-mobiilisovellus mobiililaitteellesi tai emulaattori, katso yksityiskohtaiset Expo-ohjeet osoitteesta: https://expo.io/

## Ennakkotoimet backend
Tämä sisältää tarkempia kuvauksia käyttämistämme tekniikoista.

### Arkkitehtuuri
Kuvaus tekniikoiden ja rajapintojen yhteyksistä. Sanallisesti kuvattuna sekä visuaalisesti.

![Arkkitehtuuri_proto](./images/arkkitehtuuri_proto.png)

### NodeJS
Sanallisesti kuvattu, että mitkä on backendin merkityksellisimmät tehtävät projektissa.

### Python/Azure/Jne
Projektin pihvi. Se, millä tuotteella tai tavalla prosessoimme datan niin, että voimme toimittaa käyttäjälle (ja loppujen lopuksi) Ylelle lisäarvoa.

### Tietokanta
Kuvaus käyttämistämme tiedon säilömisen ratkaisuista ja lyhyet perustelut, että miksi mitäkin on käytetty. On mahdollista, että tietokantoja on useita, sillä kaiken datan ei välttämättä kannata asua samassa kannassa.




