Meant for testing how uploading images to Cloudinary works so that we can create our own logic later
https://www.youtube.com/watch?v=3o1Z5N9TeuQ Link to YT video


Create a cloudinary account first!! https://cloudinary.com/ 

Add following line in the beginning of uploadimage.js if you want to use a .env file:
- require("dotenv").config();

 Create .env file (make sure that it is in the server folder) and check the information from Cloudinary 


CLOUD_NAME = 
API_KEY= ""

API_SECRET = ""

CLOUDINARY_URL=

Run these in the server repository
- npm install dotenv
- npm install cloudinary
- npm install express

After running these commands run "node app" in the server repository

Open another terminal

Run "npm run build" in the client repository if this is your first time using the app

Run "npm run dev" in the client repository to open the app in browser
