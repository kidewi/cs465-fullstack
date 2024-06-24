<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a name="readme-top"></a>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->


<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/kidewi/cs465-fullstack">
    <img src="images/logo.png" alt="Logo" width="210">
  </a>

  <h3 align="center">CS 465: Full Stack Development I</h3>

  <p align="center">
    Lawrence Artl III
    <br />
    <br />
    <a href="https://github.com/kidewi/cs465-fullstack/main/images/travlr_login.gif">View Demo</a>
    ·
    <a href="https://github.com/kidewi/cs465-fullstack/issues">Report Bug</a>
    ·
    <a href="https://github.com/kidewi/cs465-fullstack/issues">Request Feature</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>


<!-- ABOUT THE PROJECT -->
## About The Project
<div align = "center">
  <h3>"Travlr" Web Application</h3>
  <img src="https://github.com/kidewi/cs465-fullstack/main/images/user_facing_page.png" alt="Main" width=auto><p></p>
<!-- [![Product Name Screen Shot][product-screenshot]](https://example.com)-->
</div>

<p>
  This project focused on the development of a single web application using the MEAN stack process (MongoDB, express.js framework, Angular frontend framework, and node.js backend server framework). The entire project was designed as a travel website, "Travlr Getaways".
This was a very challenging, very interesting, and fun project for me to work on. I enjoy web development more than any other type of project, and this class is a major reason for that.
</p>


<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- BUILT WITH -->
### Built With

This project used the following frameworks, and will require them to run on your machine. See the <a href="#installation">installation</a> section for more information.


[![Node][Node.js]][Node-url]

[![Express][Express.js]][Express-url]

[![Mongodb][Mongodb]][Mongodb-url]

[![Angular][Angular.io]][Angular-url]


<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

To install and run this application on your own machine, you'll need to install the frameworks listed above, as well as be running an IDE such as Visual Studio Code or similar.

### Prerequisites

Start by ensuring you have npm installed on your machine.

  ```sh
  npm install npm@latest -g
  ```

### Installation

To install and run the application, follow the instructions below.

1. Clone the repo
   ```sh
   gh repo clone lorenarms/SNHU_CS_465_Full-Stack-Development-I
   ```
2. Open the folder in VS Code
3. Navigate to the "app_admin" folder
   ```sh
   cd app_admin
   ```  
4. Install NPM packages
   ```sh
   npm install
   ```
5. Navigate to the "app_server" folder
   ```sh
   cd ..
   cd app_server
   ```
6. Install NPM packages
   ```sh
   npm install
   ```
7. In the "app_server" folder, start the server
   ```sh
   npm run start:server
   ```
8. In the "app_admin" folder, start the Angular server
   ```sh
   ng serve
   ```
9. Open a web browser and navigate to "http://localhost:3000" to access the API
10. Open another browser tab and navigate to "http://localhost:4200" to access the backend

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

<h3>Front-end Customer Facing Website</h3>
<p>The main customer page uses standard HTML with javascript and handlebars to access the backend database (served by MongoDB local hosting) and displays available information to customers. </p>

<table>
    <tr>
        <th>Homepage</th>
        <th>Travel Page</th>    
    </tr>
    <tr>
        <td><img src="https://github.com/kidewi/cs465-fullstack/main/images/user_facing_page.png" alt="[main user page]" style="width=auto;"></td>
        <td><img src="https://github.com/kidewi/cs465-fullstack/main/images/travel_page_user.png" alt="[travel page]" style="width=auto;"></td>
    </tr>
        
</table>

<h3>Backend SPA (using Angular, Express, node.js, and MongoDB)</h3>
<p>The project incorporated an administrative backend that utilized the MongoDB, Express, Angular, and Node.js (MEAN) stack to deliver a single-page application to administrators. In this SPA a user could log-in, as well as add, edit, and delete trips.</p>
<table>
    <tr>
        <th>Homepage</th>
        <th>Login Screen</th>
        <th>Logged In</th>
    </tr>
    <tr>
        <td><img src="https://github.com/kidewi/cs465-fullstack/main/images/user_logged_out.png" alt="[homepage]" style="width=auto;"></td>
        <td><img src="https://github.com/kidewi/cs465-fullstack/main/images/login_page.png" alt="[login]" style="width=auto;"></td>
        <td><img src="https://github.com/kidewi/cs465-fullstack/main/images/main_page.png" alt="[logged in]" style="width=auto;"></td>
    </tr>
</table>

<table>
    <tr>
        <th>Editing a Trip</th>
        <th>Trip Succesfully Edited</th>
        <th>Trip Deleted</th
    </tr>
    <tr>
        <td><img src="https://github.com/kidewi/cs465-fullstack/main/images/editing_trip.png" alt="[edit]" style="width=auto;"></td>
        <td><img src="https://github.com/kidewi/cs465-fullstack/main/images/trip_edited_successfully.png" alt="[success]" style="width=auto;"></td>
        <td><img src="https://github.com/kidewi/cs465-fullstack/main/images/trip_deleted_successfully.png" alt="[deleted]" style="width=auto;"></td>
    </tr>
</table>



<p align="right">(<a href="#readme-top">back to top</a>)</p>




<!-- CONTRIBUTING -->
## Contributing

I'm always open to collaborate with other great coders! If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- LICENSE -->
## License

Currently there is no license for this application, it is free to use by anyone who needs it. Please consider letting me know if it was helpful at all, or any additions you can propose (see the <a href="#contributing">contributing</a> section)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

<p>Check out my <a href="https://www.linkedin.com/in/kirkdevinwilson/" target="_blank">LinkedIn</a> to see if I'd be a good fit for your team. </p>
<h3>Thanks for stopping by!</h3>
</p>


<p align="right">(<a href="#readme-top">back to top</a>)</p>


  

<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* [Choose an Open Source License](https://choosealicense.com)
* [GitHub Emoji Cheat Sheet](https://www.webpagefx.com/tools/emoji-cheat-sheet)
* [Malven's Flexbox Cheatsheet](https://flexbox.malven.co/)
* [Malven's Grid Cheatsheet](https://grid.malven.co/)
* [GitHub Pages](https://pages.github.com)
* [Font Awesome](https://fontawesome.com)
* [React Icons](https://react-icons.github.io/react-icons/search)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[product-screenshot]: images/main_page.png
[Node.js]: https://img.shields.io/badge/node.js-002200?style=for-the-badge&logo=nextdotjs&logoColor=green
[Node-url]: https://nodejs.org/en/
[Express.js]: https://img.shields.io/badge/Express-FFFFFF?style=for-the-badge&logo=express&logoColor=222222
[Express-url]: https://expressjs.com/
[Mongodb]: https://img.shields.io/badge/mongodb-003300?style=for-the-badge&logo=mongodb&logoColor=11FF11
[Mongodb-url]: https://www.mongodb.com/
[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
