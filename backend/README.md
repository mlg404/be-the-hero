<h1 align="center">
  <img alt="Be The Hero" title="Be The Hero" src="../.github/logo.svg" width="300px" />
</h1>

<h3 align="center">
  Be The Hero: Application back-end
</h3>

<p>This is the back-end for "Semana OmniStack 11", where i developed an entire application (Back-end, Front-end and Mobile) for help ONG's to get financial suport their registered incidents!</p>

<p align="center">
  <a href="#rocket-info">Info</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#computer-technologies">Technologies</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#information_source-how-to">How to</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#mag_right-functionalities">Functionalities</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-license">License</a>
</p>

<p align="center">
  <img alt="Web Gif" src="https://i.imgur.com/K8KPft4.png">
  <img alt="Web Gif" src="https://i.imgur.com/bl9sGSN.png">
  <img alt="Web Gif" src="https://i.imgur.com/Z4ORLsf.png">
  <img alt="Web Gif" src="https://i.imgur.com/zPQID5D.png">
</p>

## :rocket: Info

This is a ONG (Non Governamental Organization) application, where people can give financial support to incidents. ONG's can register their incidents and people can choose a incident to support, by sending e-mail or whatsapp.

## :computer: Technologies

This project was developed following this technologies:

-  [cors](https://github.com/expressjs/cors)
-  [jest](https://jestjs.io/)
-  [knex](http://knexjs.org/)
-  [express](https://expressjs.com/)
-  [node.js](https://nodejs.org/)
-  [sqlite3](https://github.com/mapbox/node-sqlite3)
-  [nodemon](https://nodemon.io/)
-  [VS Code][vc] 
-  [celebrate](https://github.com/arb/celebrate)
-  [supertest](https://github.com/visionmedia/supertest)
-  [cross-env](https://github.com/kentcdodds/cross-env)

## :information_source: How To

To clone this application you will need [Git](https://git-scm.com), [Node.js v12.15.0][nodejs] or higher + [Yarn v1.22.4][yarn] or higher installed in your computer. Run in terminal:

```bash
# Clone this repo
$ git clone https://github.com/mlg404/be-the-hero.git be-the-hero

# Access this repo
$ cd be-the-hero/backend

# Install dependencies
$ yarn install

# Run the application
$ yarn start
```

The Insomnia requests can easily be imported clicking this button:
[![Run in Insomnia}](https://insomnia.rest/images/run.svg)](https://insomnia.rest/run/?label=BeTheHero&uri=https%3A%2F%2Fraw.githubusercontent.com%2Fmlg404%2Fbe-the-hero%2Fmaster%2Fbackend%2FInsomnia.json)

## :mag_right: Funcionalities

See the current features!

### **1. ONG's**

ONG's funcionalities:

- Register a ong;
- List all ong's;
- Login with the ong ID;
- List all own incidents.

### **2. Incidents**

Incidents funcionalities:

- Create a new incident;
- Delete an incident;
- List all incident's.

## :memo: License
This project is under MIT license. See [LICENSE](https://github.com/mlg404/be-the-hero/blob/master/LICENSE) for more information.

---

Made with 💙 by Victor Eyer :wave: [Get in touch!](https://www.linkedin.com/in/victoreyer/)

[nodejs]: https://nodejs.org/
[yarn]: https://yarnpkg.com/
[vc]: https://code.visualstudio.com/