![Header](https://i.imgur.com/wd8F14S.png)

<h1 align='center'> Hiya <img src="https://raw.githubusercontent.com/rulep/rulep/master/wave.gif" width="30px"> I'm Rouan</h1>

<h3 align="center"><em>Software Engineering Apprentice at <a href="https://www.thinkful.com/">Thinkful</a></em></h3>

### About me...
```javascript
const rouan = {
    programmingLanguages: ["JavaScript"],
    library: ["React"],
    webDevelopment: ["HTML5", "CSS3", "REST APIs"],
    technologies: ["Node", "Express"],
    misc: {
        tools: ["git", "command line", "Visual Studio Code"],
        deployment: ["Heroku", "Vercel"],
        database: ["PostgreSQL"]
    }, 
    developmentMethodologies: ["Pair-Programming", "Test-Driven Development"]
};
```

I'm always looking for new friends to build cool things. If you're interested in working on a project together, don't hesitate to contact me 
[![Linkedin: rulep](https://img.shields.io/badge/-rulep-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/rulep/)](https://www.linkedin.com/in/rulep/)
[![ymail: mrxmemo](https://img.shields.io/badge/-mail-blueviolet?style=flat-square&logo=yahoo&logoColor=white&link=mailto:mrxmemo@yahoo.com)](mailto:mrxmemo@yahoo.com) 👉👈

---

Avatar designed by the Amazingly, Gifted [Dave Roldez](https://www.instagram.com/i_scream.jpg/) 😄



<div align='center'>
<img src='https://i.imgur.com/abLiXF0.png' width="300">
</div>

<br />

<!--
<p align="center">
<table>
<tr>
<td>
<img align="left" src="https://i.imgur.com/NOSdKgw.gif" width="190">
<h3>What are people using it for?</h3>
<ul>
    <li>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod</li>
    <li>Lorem ipsum dolor sit amet, consectetur adipiscing elit</li>
    <li>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod</li>
    <li>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor</li>
</ul>
<img width="1000" height="0">
</td>
</tr>
</table>
</p>
-->

<h2 id="table-of-contents"> :book: Table of Contents</h2>

<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-project"> ➤ About The Project</a></li>
    <li><a href="#prerequisites"> ➤ Prerequisites</a></li>
    <li><a href="#getting-started"> ➤ Getting Started</a></li>
    <li><a href="#demo"> ➤ Demo</a></li>
    <li><a href="#mobile-support"> ➤ Mobile Support</a></li>
    <li><a href="#api-paths"> ➤ API Documentation</a></li>
    <li><a href="#running-tests"> ➤ Running Tests</a></li>
    <li><a href="#user-stories"> ➤ User Stories</a></li>
    <li>
      <a href="#mobile-support"> ➤ Pre-processing</a>
      <ul>
        <li><a href="#preprocessed-data">Pre-processed data</a></li>
        <li><a href="#statistical-feature">Statistical feature</a></li>
        <li><a href="#topological-feature">Topological feature</a></li>
      </ul>
    </li>
    <!--<li><a href="#experiments">Experiments</a></li>-->
    <li><a href="#source"> ➤ Source</a></li>
  </ol>
</details>


<img src='https://i.imgur.com/DwCJ72P.png'>

<!-- ABOUT THE PROJECT -->
<h2 id="about-the-project"> :pencil: About The Project</h2>

<!--
<p align="justify"> 
  This application was built as the capstone project for the Thinkful Software Engineering Flex Program. It was designed to be used by restaurant personnel to keep track of reservations and table seating, when a request is made by a customer.
</p>
-->

<table>
<tr>
<td>
    This application was built as the capstone project for the Thinkful Software Engineering Flex Program. It was designed to be used by restaurant personnel to keep track of reservations and table seating, when a request is made by a customer.
</td>
</tr>
</table>

<img src='https://i.imgur.com/DwCJ72P.png'>

<!-- PREREQUISITES -->
<h2 id="prerequisites"> :fork_and_knife: Prerequisites</h2>

The following tech stack was used in this project:
* React
* Node
* Express
* PostgreSQL
* Knex

<img src='https://i.imgur.com/DwCJ72P.png'>

<!-- GETTING STARTED -->
<h2 id="getting-started"> :book: Getting Started</h2>

1. Fork and clone this repository.
1. Run `cp ./back-end/.env.sample ./back-end/.env`.
1. Update the `./back-end/.env` file with the connection URL's to your ElephantSQL database instance.
1. Run `cp ./front-end/.env.sample ./front-end/.env`.
1. You should not need to make changes to the `./front-end/.env` file unless you want to connect to a backend at a location other than `http://localhost:5000`.
1. Run `npm install` to install project dependencies.
1. Run `npm run start:dev` to start your server in development mode.

<img src='https://i.imgur.com/DwCJ72P.png'>

<!-- DEMO -->
<h2 id="demo"> :cloud: Demo</h2>

Here is a live demo:  [...]

<div>
<img src='https://i.imgur.com/q6EeYKQ.gifg'>
</div>

<img src='https://i.imgur.com/DwCJ72P.png'>

<!-- MOBILE SUPPORT -->
<h2 id="mobile-support"> :iphone: Mobile Support</h2>

<div align='center'>
<img src='https://i.imgur.com/R2N2jUD.png'>
</div>
    
<img src='https://i.imgur.com/DwCJ72P.png'>

<!-- API DOCUMENTATION -->
<h2 id="api-paths"> :newspaper: API DOCUMENTATION</h2>

The table displays the API endpoints and its use:

| API Endpoint                                             | Description                                                                                                         
| -------------------------------------------------------- | ---------------------------------------------------------------------------
| `/reservations`                                          | GET: List all Reservations. POST: Create a new reservation                                      
| `/reservations/:reservationId`                           | GET: Single reservation by ReservationId, PUT: Update a reservation by ReservationId 
| `/reservations/:reservationId/status`                    | PUT: Update a reservation status as either "Booked", "Seated", "Finished", or "Canceled"
| `/tables`                                                | GET: List all Tables, POST: Create a new table
| `/tables/:tablesID`                                      | GET: List a single table
| `/tables:tableId/seat`                                   | PUT: Updates a single table's status to "Occupied", Delete: Updates a single table's status to "Free"                
    
<img src='https://i.imgur.com/DwCJ72P.png'>

<!-- RUNNING TESTS -->
<h2 id="running-tests"> :grey_exclamation: Running Tests</h2>

This project has unit, integration, and end-to-end (e2e) tests. You have seen unit and integration tests in previous projects.
End-to-end tests use browser automation to interact with the application just like the user does.
Once the tests are passing for a given user story, you have implemented the necessary functionality.

Test are split up by user story. You can run the tests for a given user story by running:

`npm run test:X` where `X` is the user story number.

Have a look at the following examples:

- `npm run test:1` runs all the tests for user story 1 (both frontend and backend).
- `npm run test:3:backend` runs only the backend tests for user story 3.
- `npm run test:3:frontend` runs only the frontend tests for user story 3.

Whenever possible, frontend tests will run before backend tests to help you follow outside-in development.

> **Note** When running `npm run test:X` If the frontend tests fail, the tests will stop before running the backend tests. Remember, you can always run `npm run test:X:backend` or `npm run test:X:frontend` to target a specific part of the application.

Since tests take time to run, you might want to consider running only the tests for the user story you're working on at any given time.

Once you have all user stories complete, you can run all the tests using the following commands:

- `npm test` runs _all_ tests.
- `npm run test:backend` runs _all_ backend tests.
- `npm run test:frontend` runs _all_ frontend tests.
- `npm run test:e2e` runs only the end-to-end tests.

If you would like a reminder of which npm scripts are available, run `npm run` to see a list of available commands.

Note that the logging level for the backend is set to `warn` when running tests and `info` otherwise.

> **Note**: After running `npm test`, `npm run test:X`, or `npm run test:e2e` you might see something like the following in the output: `[start:frontend] Assertion failed:`. This is not a failure, it is just the frontend project getting shutdown automatically.

> **Note**: If you are getting a `unable to resolve dependency tree` error when running the frontend tests, run the following command: `npm install --force --prefix front-end`. This will allow you to run the frontend tests.

> **Hint**: If you stop the tests before they finish, it can leave the test database in an unusual state causing the tests to fail unexpectedly the next time you run them. If this happens, delete all tables in the test database, including the `knex_*` tables, and try the tests again.

### Frontend test timeout failure

Running the frontend tests on a resource constrained computer may result in timeout failures.

If you believe your implementation is correct, but needs a bit more time to finish, you can update the `testTimeout` value in `front-end/e2e/jest.config.js`. A value of 10000 or even 12000 will give each test a few more seconds to complete.

#### Screenshots

To help you better understand what might be happening during the end-to-end tests, screenshots are taken at various points in the test.

The screenshots are saved in `front-end/.screenshots` and you can review them after running the end-to-end tests.

You can use the screenshots to debug your code by rendering additional information on the screen.

<img src='https://i.imgur.com/DwCJ72P.png'>







<img src='https://i.imgur.com/DwCJ72P.png'>

<!-- SOURCE -->
<h2 id="source"> :scroll: Source</h2>

Project's source code: <a href="https://github.com/Thinkful-Ed/starter-restaurant-reservation">https://github.com/Thinkful-Ed/starter-restaurant-reservation</a>


<!--
My name is Rouan, and I come from a non-technical background having studied Computerized Accounting. I took up Wed Development as a hobby. During my studies, I came across the <em><a href="https://www.thinkful.com/">Thinkful</a></em> platform, where I learned more about the program. As my interests aligned with it's offerings, I signed on to take this hobby to the next level by making a social impact through programming. I'm always looking for new friends to build cool things. If you're interested in working on a project together, don't hesitate to contact me 
[![Linkedin: rulep](https://img.shields.io/badge/-rulep-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/rulep/)](https://www.linkedin.com/in/rulep/)
[![ymail: mrxmemo](https://img.shields.io/badge/-email-blueviolet?style=flat-square&logo=yahoo&logoColor=white&link=mailto:mrxmemo@yahoo.com)](mailto:mrxmemo@yahoo.com) 👉👈
-->

<!--
**rulep/rulep** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
👉👈
-->
