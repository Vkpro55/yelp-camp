Live Website:-  https://yelpcamp-dwzt.onrender.com/




⚙️ Features
1.  Authentication:
2.  User login with username and password
3.  Admin sign-up with admin code
4.  Authorization:
5.  One cannot manage posts and view user profile without being authenticated
6.  One cannot edit or delete posts and comments created by other users
7.  Admin can manage all posts and comments
8.  Manage campground posts with basic functionalities:
9.  Create, edit and delete posts and comments
10. Upload campground photos
11. Display campground location on Google Maps
12. Search existing campgrounds
13. Manage user account with basic functionalities:
14. Password reset via email confirmation (disabled)
15. Profile page setup with sign-up
16. Flash messages responding to users' interaction with the app
17. Responsive web design


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
