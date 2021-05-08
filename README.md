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
  - [About The Project](#about-the-project)
  - [Concept](#concept)
  - [Built With](#built-with)
- [Getting Started](#getting-started)
  - [Prerequites frontend](#prerequites-frontend)
  - [Prerequitest backend](#Prerequites-backend)
    - [Arkkitehtuuri](#arkkitehtuuri)
    - [NodeJS](#nodejs)
    - [Python/Azure/Jne](#pythonazurejne)
    - [Tietokanta](#tietokanta)

## About The Project
This repository is part of Haaga-Helia University of Applied Sciences' Software Project II course. The aim of the course is to create a new application using open data. 

The business partner of the course was YLE.

We ended up using Yle’s Aarena interface, which provides information on the various materials available through the Aarena. 

## Concept
Haluamme tarjota käyttäjälle sovelluksen, jolla voi hyödyntää Yle Areenan sisältöä. Konseptille on tarve, sillä Areenassa ei ole käyttäjäsidonnaista suosittelua. ​
Sovelluksemme antaa suosituksia Yle Areenan sisällöstä käyttäjälle, joka voi hyväksyä tai hylätä suositellut ehdotukset Tinderistä tutulla tavalla eli  "swaippaamalla" ne sovelluksen ruudulla oikealle tai vasemmalla. Jos sovelluksen antamasta ehdotuksesta "tykätään" (swaipataan oikealle), ehdotus siirtyy "tykkäsit näistä" -listalle. Jos käyttäjä avaa sovelluksen ensimmäisen kerran niin sovellus kertoo lyhyesti, että käyttäjän tulee swaippailla hetki ohjelmia ja mennä sen jälkeen katsomaan, että mitä suosituksia on saanut. ​
Viiden swaippauksen jälkeen käyttäjä ohjataan siirtymään listaruutuun.
* Listaruutu sisältää käyttäjälle suositeltuja ohjelmia. Suosittelut voivat koostua muiden käyttäjien suosituksista
* Suositussekoitus sisältää muutaman suosituksen knn-suosittelijasta, muutama täysin satunnainen suositus ja muutama tulee sen perusteella mistä käyttäjä on aiemmin tykännyt.
* Listaruudussa voi olla myös top 10 tykätyimmät ohjelmat sekä esimerkkinä vaikka komediat näkyvillä. 
​
## Built With

* MongoDB
* Phyton
* React-Native
* Nodejs.

## Getting Started
This is an example of how you may give instructions on setting up your project locally. To get a local copy up and running follow these simple example steps

### Prerequitest frontend
This is an example of how to list things you need to use the software and how to install them.

## Step 1
As prequisite to get the application up and running you need to have installed the following:

  * npm
  * expo CLI
  * emulator or expo mobile app in your mobile device, See detailed Expo documentation from https://expo.io/

## Prerequitest backend
This is an example of how to list things you need to use the software and how to install them.

### Arkkitehtuuri
Kuvaus tekniikoiden ja rajapintojen yhteyksistä. Sanallisesti kuvattuna sekä visuaalisesti.

![Arkkitehtuuri_proto](./images/arkkitehtuuri_proto.png)

### NodeJS
Sanallisesti kuvattu, että mitkä on backendin merkityksellisimmät tehtävät projektissa.

### Python/Azure/Jne
Projektin pihvi. Se, millä tuotteella tai tavalla prosessoimme datan niin, että voimme toimittaa käyttäjälle (ja loppujen lopuksi) Ylelle lisäarvoa.

### Tietokanta
Kuvaus käyttämistämme tiedon säilömisen ratkaisuista ja lyhyet perustelut, että miksi mitäkin on käytetty. On mahdollista, että tietokantoja on useita, sillä kaiken datan ei välttämättä kannata asua samassa kannassa.




