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
    <li>
      <a href="#mobile-support"> ➤ Pre-processing</a>
      <ul>
        <li><a href="#preprocessed-data">Pre-processed data</a></li>
        <li><a href="#statistical-feature">Statistical feature</a></li>
        <li><a href="#topological-feature">Topological feature</a></li>
      </ul>
    </li>
    <!--<li><a href="#experiments">Experiments</a></li>-->
    <li><a href="#results-and-discussion"> ➤ Results and Discussion</a></li>
    <li><a href="#references"> ➤ References</a></li>
    <li><a href="#contributors"> ➤ Contributors</a></li>
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
<h2 id="mobile-support"> :newspaper: API DOCUMENTATION</h2>

The table displays the API endpoints and its use:

| API Endpoint                                             | Description                                                                                                         
| -------------------------------------------------------- | ---------------------------------------------------------------------------
| `/reservations`                                          | GET: List all Reservations. POST: Create a new reservation                                      
| `/reservations/:reservationId`                           | GET: Single reservation by Reservation_Id, PUT: Update a reservation by ReservationId 
| `/reservations/:reservationId/status`                    | PUT: Update a reservation status as either "Booked", "Seated", "Finished", or "Canceled"
| `/tables`                                                | GET: List all Tables, POST: Create a new table
| `/tables/:tablesID`                                      | GET: List a single table
| `/tables:tableId/seat`                                   | PUT: Updates a single table's status to "Occupied", Delete: Updates a single table's status to "Free"                

    
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
