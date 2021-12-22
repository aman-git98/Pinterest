# Pinterest
This is a Travel Map pinning web app developed using Node.js, MongoDB, React.js and Mapbox. In this application, a user can pin any location and share reviews with other users across the world. 

# How to run
1. Clone the repository or download the zip folder which contains two folders named backend and frontend.

2. Cd to backend folder and install the following dependencies:
   -> npm init
   -> yarn add express
   -> yarn add mongoose
   -> yarn add nodemon
   -> yarn add dotenv
   -> yarn add bcrypt
   
3. Add a new file in backend folder as ".env" and add the "MONGO_URL" of your mongodb.
   -> MONGO_URL = "your mongo url token"
   
4. In package.json (inside backend folder), under scripts tag, add:
   -> "start": "nodemon index.js"
   
5. To start backend server:
   -> yarn start
   
6. Now open another terminal and cd to frontend to create a react application.
   -> npx create-react-app .       (full stop at end means the directory)
   
7. Install following dependencies:
   -> yarn add react-map-gl
   -> yarn add @material-ui/core @material-ui/icons
   -> yarn add axios
   -> yarn add timeago.js
   
8. Add a new file in frontend as ".env" and add your Mapbox token:
   -> REACT_APP_MAPBOX = "your Mapbox token"
   
9. In package.json (inside the frontend directory), add proxy at the last:
   -> "proxy": "http://localhost:8800/api"
   
10. To run the application: 
   -> yarn start
   
11. Enjoy!   
