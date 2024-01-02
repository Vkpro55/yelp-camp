Live Website:-  https://yelpcamp-dwzt.onrender.com/




⚙️ Features
Authentication:

User login with username and password

Admin sign-up with admin code

Authorization:

One cannot manage posts and view user profile without being authenticated

One cannot edit or delete posts and comments created by other users

Admin can manage all posts and comments

Manage campground posts with basic functionalities:

Create, edit and delete posts and comments

Upload campground photos

Display campground location on Google Maps

Search existing campgrounds

Manage user account with basic functionalities:

Password reset via email confirmation (disabled)

Profile page setup with sign-up

Flash messages responding to users' interaction with the app

Responsive web design


💡 Lessons Learned / Technologies Used


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
