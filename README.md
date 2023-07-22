# YelpCamp: The Ultimate Camping Resource

YelpCamp is the go-to place for campers to find, review, and share campsites. With YelpCamp, you can:

Browse campsites by location, amenities, and price.
Read reviews from other campers to get the inside scoop.
Upload your own photos and reviews to help others plan their trips.
Connect with other campers in your area.
YelpCamp is more than just a review site. It's a community for campers to connect, share advice, and find the perfect campsite for their next adventure.

# Features:

User authentication: Create an account to save your favorite campsites and leave reviews.
Posts management: Create, edit, and delete your own campsite posts.
Image uploading: Upload photos of your campsites to help others visualize your experiences.
Responsive design: YelpCamp looks great on any device, from desktop to mobile.
# Benefits:

Find the perfect campsite for your next trip.
Get the inside scoop from other campers.
Connect with other campers in your area.
Share your own photos and reviews to help others plan their trips.
Sign up for YelpCamp today and start planning your next camping adventure!

Preview website :   https://yelpcamp-ydsa.onrender.com/
you can also use 
## Implementation

### Languages

* JavaScript
* EJS
* CSS

### Tools

* Node.js
* Express
* Bootstrap v5.0
* MongoDB

### NPM Tools

* Mongoose
* Passport.js: handle authentication
* Joi: schema description & data validation
* helmet: helps secure the app by setting various HTTP headers
* express-mongo-sanitize: prevent MongoDB Operator Injection

### Services

* Cloudinary: store the images that users upload
* MongoDB Atlas: store the data of campground, reviews and users
* Mapbox: provide interactive maps to mark the locations of campgrounds
* Render: for deploying the website

#### Used many concepts like MVC architechture , cookie - parsing , sessions , authentication , authorization ,RESTful routing techniques , Apis and many more.....
#### U can also use Hoppscotch or postman for this website.
## How to Install and Run the Project Locally

1. Clone the repository from GitHub.
2. Install the dependencies using `npm install` or `npm i`.
3. Create a `.env` file and add the following environment variables:
   `MAPBOX_TOKEN`
   `CLOUDINARY_CLOUD_NAME`
   `CLOUDINARY_KEY`
   `CLOUDINARY_SECRET`
   `DB_URL`
   `CLOUDINARY_URL`
    you can also add custom PORT and session SECRET if u are intrested
4. Now run the app.js file by using commands `nodemon app.js` or `node app.js` or `npm run start`
## Credits
* This app is the capstone project of [Colt Steele](https://github.com/Colt)'s course: [The Web Developer Bootcamp 2021](https://github.com/Colt/YelpCamp). Thanks for his creation of such a great course with comprehensive knowledge and this wonderful project.
