
CAMP-TODAYCAMP-TODAY
Camp-Today Project 🏕️ | Node.js, Express, Mongoose, MongoDB, Rest API, Authentication

As the driving force behind the Camp-Today project, I architected a dynamic campground-sharing platform equipped with essential user authentication, search, and secure payment functionalities.

Project Highlights:
🚀 Engineered a feature-rich web application empowering users to discover and share campgrounds seamlessly.
💡 Leveraged a tech stack of HTML, CSS, EJS for front-end, and Node.js, Express, Passport for back-end, bolstered by MongoDB for robust data management.
💳 Integrated Stripe API to facilitate seamless and secure payment transactions, enabling user interactions like liking, commenting, and rating.
🔒 Implemented admin preferences and a secure email-based password reset mechanism to enhance user security and account management.

This project was a pivotal opportunity for me to combine my technical skills with creative problem-solving, delivering an exceptional user experience in the process."


💡 Lessons Learned / Technologies Used
MVC (Model-View-Controller) architecture to achieve seperation of concerns and maintain independence in relation to backend/frontend services.
Express.js minimal, unopinionated backend framework to keep serverside boilerplate as low as possible. Especially useful for learning how to piece different technologies together to develop a complete backend.
Express-Session to learn how cookies work to deliver a rich user experience through client and serverside cookies.
Passport.js for authentication and authorization.
MongoDB as the primary NoSQL database to store campgrounds, users, reviews and session details.
Mongoose as an ORM(Object relation mapping) library to interact with MongoDB.
Cloudinary to store images of campgrounds when users create new campgrounds, and to optimize them for when client-side requests them.
Mapbox to deliver an interactive map for users to visually see the location of campgrounds through a cluster map and a zoomed in map for each campground.
EJS (Embedded JavaScript Templates) as a templating language to create dynamic user experices.
Bootstrap as the driving CSS framework to create visually appealing user experiences.
Render to host the complete application
🚀 Getting Started
To run this project on your system:
Create an .env file and add values to the following variables:

CLOUDINARY_CLOUD_NAME=<Your Cloudinary cloud name>
CLOUDINARY_KEY=<Your Cloudinary key>
CLOUDINARY_SECRET=<Your Cloudinary secret>
MAPBOX_TOKEN=<Your Mapbox token>
DB_URL=<Your MongoDB atlas URL or local MongoDB URL>
Make sure you have MongoDB installed on your system In a terminal window, initialize a MongoDB Database

$ ./mongod
In a second terminal window, access the MongoDB Database with Mongoose

$ mongoose
In a third terminal window, install dependencies using npm:

$ npm install
And then run the application with

$ npm start
or for hot reloading (recommended)

$ nodemon app.js
🚗 Roadmap
Refactor backend to use Typescript instead of JavaScript to ensure code type safety

Replace EJS with Next.js to take advantage of the scalability and modularity of React while still maintaining the performance of server rendered applications

Overhaul the UI to create a more interactive experience. Three.js 👀👀
