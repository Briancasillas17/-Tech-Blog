

Tech Blog is a developer blog app where users can signup for an account, login with their username and password, publish blog posts, comment on others' posts, and update or delete their own posts. This is a RESTful API app following MVC development using MySQL with Sequelize as an ORM and Handlebars for the front-end. Express was used for routing along with Sequelize for accessing the API data, and Express-Session and bcrypt were used for user authentication.

#### User Signup Page:


## Table of Contents

- [Installation](#installation)
- [Tech Used](#tech-used)
- [Questions](#questions)
- [Links](#links)
- [License](#license)

## Installation

- Both Node.js and MySQL must be installed on your computer.
- Clone the repo by copying and pasting in your command line:
  - `git@github.com:Briancasillas17/-Tech-Blog.git`
- Navigate to the root directory and run:
  - `npm install`
- To start the server, run the following in your command line:
  - `npm start`
- Navigate to `localhost:3001` in your browser to open the app locally.

## Tech Used

- JavaScript
- [Handlebars.js](https://handlebarsjs.com/)
- [Node.js](https://nodejs.org/en/)
- [Express.js](https://www.npmjs.com/package/express)
- [Express-session](https://www.npmjs.com/package/express-session)
- [bcrypt](https://www.npmjs.com/package/bcrypt)
- [MySQL](https://dev.mysql.com/doc/)
- [MySQL2](https://www.npmjs.com/package/mysql2)
- [Sequelize](https://www.npmjs.com/package/sequelize)
- [dotenv](https://www.npmjs.com/package/dotenv)
- [Bulma](https://bulma.io/documentation/)


### Acceptance Criteria

```
GIVEN a CMS-style blog site
WHEN I visit the site for the first time
THEN I am presented with the homepage, which includes existing blog posts if any have been posted; navigation links for the homepage and the dashboard; and the option to log in
WHEN I click on the homepage option
THEN I am taken to the homepage
WHEN I click on any other links in the navigation
THEN I am prompted to either sign up or sign in
WHEN I choose to sign up
THEN I am prompted to create a username and password
WHEN I click on the sign-up button
THEN my user credentials are saved and I am logged into the site
WHEN I revisit the site at a later time and choose to sign in
THEN I am prompted to enter my username and password
WHEN I am signed in to the site
THEN I see navigation links for the homepage, the dashboard, and the option to log out
WHEN I click on the homepage option in the navigation
THEN I am taken to the homepage and presented with existing blog posts that include the post title and the date created
WHEN I click on an existing blog post
THEN I am presented with the post title, contents, post creator???s username, and date created for that post and have the option to leave a comment
WHEN I enter a comment and click on the submit button while signed in
THEN the comment is saved and the post is updated to display the comment, the comment creator???s username, and the date created
WHEN I click on the dashboard option in the navigation
THEN I am taken to the dashboard and presented with any blog posts I have already created and the option to add a new blog post
WHEN I click on the button to add a new blog post
THEN I am prompted to enter both a title and contents for my blog post
WHEN I click on the button to create a new blog post
THEN the title and contents of my post are saved and I am taken back to an updated dashboard with my new blog post
WHEN I click on one of my existing posts in the dashboard
THEN I am able to delete or update my post and taken back to an updated dashboard
WHEN I click on the logout option in the navigation
THEN I am signed out of the site
WHEN I am idle on the page for more than a set time
THEN I am automatically signed out of the site
```
## Questions

Please visit my **[GitHub profile](https://github.com/Briancasillas17)** to check out this and other projects I've created and contributed to.
If you have any specific questions about this project, please contact me at Briancasillas67@yahoo.com

## Links
deploy https://sleepy-beyond-56583.herokuapp.com/
## License

![License](https://img.shields.io/badge/License%3A-MIT-green.svg)  
 This app is licensed under the MIT license.
