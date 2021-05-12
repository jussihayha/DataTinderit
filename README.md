[![Contributors][contributors-shield]][contributors-url]
[![Issues][issues-shield]][issues-url]

[contributors-shield]: https://img.shields.io/github/contributors/jussihayha/DataTinderit.svg?style=for-the-badge
[contributors-url]: https://github.com/jussihayha/DataTinderit/graphs/contributors
[issues-shield]: https://img.shields.io/github/issues/jussihayha/DataTinderit.svg?style=for-the-badge
[issues-url]: https://github.com/jussihayha/DataTinderit/issues
[product-screenshot]: images/logo_viritys_transparent.png


![logo](./images/DatatinderiLogo.JPG)

# Tables of contents
- [Tables of contents](#Tables-of-contents)
  - [About The Project](#about-the-project)
  - [Concept](#concept)
  - [Built With](#built-with)
- [Getting Started](#getting-started)
  - [Prerequites frontend](#prerequites-frontend)
    - [Installation](#installation)
  - [Prerequitest backend](#Prerequites-backend)
    - [Installation](#installation)
- [Usage](#usage)
- [Roadmap](#roadmap)
- [Contributing](#contributing)
- [Lisence](#Lisence)
- [Authors](#Authors)
- [Acknowledgements](#Acknowledgements)

## About The Project
This repository is part of Haaga-Helia University of Applied Sciences' Software Project II course. The aim of the course is to create a new application using open data. 

The business partner of the course was YLE.

We ended up using Yle’s open developer API's, which provided information on the various materials available through Yle Areena. 

## Concept
We wanted to provide the user with an application that can utilize the content of Yle Areena. There is a need for the concept, as there is was no user-specific recommendation in the Arena. Our app gives recommendations about Yle Arena content to a user who can accept or reject recommended suggestions in a Tinder-like way, i.e. by “swiping” them to the right or left of the app screen. If a proposal from an app is "liked" (swipe right), the proposal goes to the "liked these" list. If the user opens the app for the first time then the app will briefly say that the user should swipe for a while for the programs and then go see what the app recommends. 

* The list component contains programs recommended for the user. Recommendations consists of recommendations from other users.
* List component works realtime so when user swipes the recommendations the choices reflect immediatly on the recommendations. 
* The list component also contains the top 10 most liked programs.

## Built With

* MongoDB
* React-Native
* NodeJS
* Expo

## Getting Started
This repository contains general information about the project and we have separate repositories for the frontend application, and for the backend server.  
These are available here:


## Prerequitest frontend
This is an example of how to list things you need to use the software and how to install them.

  * npm
    `npm install npm@latest -g`
  * expo CLI
    `expo start`
  * emulator or expo mobile app in your mobile device, See detailed Expo documentation from https://expo.io/

### Installation

Clone or download this project
git clone `https://github.com/laurahyvari/DataTinderiFront.git`

navigate to DataTinderiFront directory:

`cd / path_to / DataTinderiFront`

run

`npm install`

`expo start`

## Prerequitest backend
This is an example of how to list things you need to use the software and how to install them.

* mongoDB
* Nodejs.

### Installation
Clone or download this project
git clone `https://github.com/bgf122/dataTinderBack.git`

navigate to DataTinderiFront directory:

`cd / path_to / dataTinderBack`

run

`npm install`


## Usage
Use this space to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

## Roadmap
See the open issues for a list of proposed features (and known issues).

## Contributing

* Fork the Project
* Create your Feature Branch
* Commit your Changes
* Push to the Branch
* Open a Pull Request

## License
This is an open source project licensed under ??

## Authors
Hyvärinen Laura, Häyhä Jussi, Korhonen Pekka, Korhonen Sasu ja Sanden Marketta

## Acknowledgements
Thanks to YLE for api data.


