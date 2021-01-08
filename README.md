# CampAdvisor

A full-stack Node.js web application with user auth to post or find campground images, reviews, pricing and Location. 
Built using Express, MongoDB and RESTful API. Implemented geocoding and maps using Mapbox API to allow users to easily find or
set a campground location.


## Image Gallery
### Home:
![Home Page Image](https://github.com/JawadHossain/CampAdvisor/blob/main/gallery/Home.png)

### All Campgrounds:
![All Campgrounds Image](https://github.com/JawadHossain/CampAdvisor/blob/main/gallery/AllCampGrounds.png)

### Campground Detail View:
![Campground Detail View Image](https://github.com/JawadHossain/CampAdvisor/blob/main/gallery/CampGroundDetailView.png)

## Usage

### Install Dependencies
```
npm install
```

### Env Variables
Create a .env file in the root directory and add the following
```
CLOUDINARY_CLOUD_NAME= your cloudinary cloud name
CLOUDINARY_KEY= your cloudinary cloud key
CLOUDINARY_SECRET= your cloudinary cloud secret
MAPBOX_TOKEN= your Mapbox token
DB_URL= your MongoDB URL with username, password and dbname
```
Also, add 'https://res.cloudinary.com/yourUserName/' to app.js imgSrc, otherwise helmet.js will block your image URLs.

### Run
```
node app.js
```

### Sign up as a new User
Happy Camping!