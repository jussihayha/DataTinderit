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

## Introduction
This repository contains general information about the project and we have separate repositories for the frontend application, and for the backend server.  
These are available here:

Frontend: https://github.com/laurahyvari/DataTinderiFront.git
Backend: https://github.com/bgf122/dataTinderBack.git

## Roadmap
Our current situation is that we have a working proof of concept for a fullstack solution that offers an application with recommendations.
Next natural steps would be to make this as modular as possible so that you can change data sources and authentication methods fluently and with relative ease.

If we look at the history of this project we can see the following milestones that we went through

### Sprint 0
- defining this project 
- understanding the datastructure of YLE API
- creating possible user stories
- 
### Sprint 1
- creating a simple backend that offers data
- creating a tinderlike swipe mechanic
- adjusting our user stories to reflect knowledge acquired during sprint 0

### Sprint 2
- extending and developing our backend to offer better possibilities for frontend side
- developing functionalities needed for gathering data about users and adding authentication

### Sprint 3 



## Contributing

* Fork the Project
* Create your Feature Branch
* Commit your Changes
* Push to the Branch
* Open a Pull Request

## License
This is an open source project licensed under MIT

## Authors
Hyvärinen Laura, Häyhä Jussi, Korhonen Pekka, Korhonen Sasu ja Sanden Marketta

## Acknowledgements
Thanks to YLE for giving access to their data
Ohto Rainio for developing knn-recommender


