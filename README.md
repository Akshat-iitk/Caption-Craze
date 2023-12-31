# CaptionCraze

## Table of Contents

1. [Introduction](#introduction)
2. [Features](#features)
3. [Technologies Used](#technologies-used)
4. [Installation](#installation)
5. [Overview](#overview)
5. [Website view](#screenshots)

## Introduction

Welcome to CaptionCraze, A full-stack web application built with Node.js, Express, and MongoDB for the backend, and EJS, CSS, and JavaScript and libraries like Tailwind and Bootstrap for the front end. This platform provides users with a seamless and responsive experience, featuring key functionalities such as user authentication, profile management, and a dynamic post feed.

## Features

- **User Authentication:** Securely sign up and log in to access personalized profiles and features.

- **Profile Management:** Edit your profile details and upload a profile picture.

- **Post Creation:** Create and share posts with detailed descriptions, allowing you to express yourself.

- **Commenting:** Engage with other users by leaving comments on their posts.
- ....
## Technologies Used

- **Backend:**
  - [Node.js](https://nodejs.org/): JavaScript runtime for server-side development.
  - [Express](https://expressjs.com/): Web framework for building APIs and web applications.
  - [MongoDB](https://www.mongodb.com/): NoSQL database for data storage.
  - [Mongoose](https://mongoosejs.com/): MongoDB object modeling for Node.js.
  - [Passport](https://www.npmjs.com/package/passport): Passport is Express-compatible authentication middleware for Node.js.
- **Frontend:**
  - [EJS](https://ejs.co/): Embedded JavaScript templating for dynamic content.
  - [Tailwind](https://tailwindcss.com/): A utility-first CSS framework that can be composed to build any design, directly in your markup.
  - [Bootstap](https://getbootstrap.com/): Powerful, extensible, and feature-packed frontend toolkit
  - CSS: Cascading Style Sheets for styling the frontend.
  - JavaScript: A programming language for dynamic frontend elements.
  - ... (Include other libraries for icons, animations, etc.)
## Installation

To get started with CarrerCraft, follow these steps:

```bash
git clone https://github.com/Akshat-iitk/Caption-Craze.git
cd Caption-Craze
npm install
nodemon run
```


### Overview

- **`public/`:** Contains the main HTML file (`index.html`) and other static assets that don't require processing by Webpack.

- **`Routes/`:** The main backend source code directory.

  - **`index.js/`:** Handles project-wide routes and user authentication using passport.

  - **`multer.js/`:** Manages image upload functionality using the Multer library for storing post images and profile pictures.

  - **`post.js/`:** Manages the Mongoose database schema for the post model, handling post-related data.

  - **`user.js/`:** Manages the Mongoose database schema for the user model, handling user-related data.

- **`views/`:** Contains EJS files for each different page in the Routes directory.

  - **`add.ejs/`:** EJS file for the page route dedicated to adding a post in CaptionCraze.

  - **`login.ejs/`:** EJS file for the Login page connected through user authentication in index.js.

  - ... (Include other EJS files for different pages)

- **`.gitignore`:** Specifies files and directories that should be ignored by version control.

- **`package.json`:** Metadata about the project, including dependencies and scripts.

- **`README.md`:** Documentation file providing information about the project.

## Screenshots
### Login Page

![Login Page](https://github.com/Akshat-iitk/Caption-Craze/assets/96899544/f593a082-0879-4f98-91e4-3c69c656369e)

Access your account seamlessly with our intuitive and secure responsive login page.

### SignUp Page

![SignUp Page](https://github.com/Akshat-iitk/Caption-Craze/assets/96899544/dbd7e8f9-331d-4914-a241-fd7934103fa6)

Join us and create your account with the same level of intuitiveness and security on our responsive SignUp page.
### Profile page
![Screenshot (112)](https://github.com/Akshat-iitk/Caption-Craze/assets/96899544/ace0cc3b-be99-4d7c-95aa-789bfbd0f407)
Profile Page where you can see your post and edit profile pic is implemented using Multer
### Feed page
![Screenshot (113)](https://github.com/Akshat-iitk/Caption-Craze/assets/96899544/81018573-3746-42f5-8607-f5fe06321577)

View other's posts with captions along with their username
### Upload post page
![Screenshot (114)](https://github.com/Akshat-iitk/Caption-Craze/assets/96899544/fb12bffe-6178-4cd9-be46-0b6d52845c0b)

This is upload post page


