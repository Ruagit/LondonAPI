This is an API endpoint which returns users with within a distance of 50 miles of London or who are registered as living in London. Additionally you can request all users with and view their distance from London.

##  Heroku - https://jbuserapi.herokuapp.com/api/users

# Getting Started

- Clone the repo - https://github.com/Jlbos24/API-DWP.git
- cd into the project file
- npm install
- npm start
- open Postman or Nodemon on port 8080, see Endpoints.json for details on all availble endpoints.

# Testing

- "npm test"
- "npm test-utils"

# Technologies

- Node.js
- Express.js
- Axios
- Mocha Chai
- Supertest

# API Returns

{
"users": [
{
"id": 135,
"first_name": "Mechelle",
"last_name": "Boam",
"email": "mboam3q@thetimes.co.uk",
"ip_address": "113.71.242.187",
"latitude": -6.5115909,
"longitude": 105.652983,
"london": 7246.65
},
{
"id": 396,
"first_name": "Terry",
"last_name": "Stowgill",
"email": "tstowgillaz@webeden.co.uk",
"ip_address": "143.190.50.240",
"latitude": -6.7098551,
"longitude": 111.3479498,
"london": 7498.08
},
{
"id": 520,
"first_name": "Andrew",
"last_name": "Seabrocke",
"email": "aseabrockeef@indiegogo.com",
"ip_address": "28.146.197.176",
"latitude": "27.69417",
"longitude": "109.73583",
"london": 5515.56
},
{
"id": 658,
"first_name": "Stephen",
"last_name": "Mapstone",
"email": "smapstonei9@bandcamp.com",
"ip_address": "187.79.141.124",
"latitude": -8.1844859,
"longitude": 113.6680747,
"london": 7675.83
},
{
"id": 688,
"first_name": "Tiffi",
"last_name": "Colbertson",
"email": "tcolbertsonj3@vimeo.com",
"ip_address": "141.49.93.0",
"latitude": 37.13,
"longitude": -84.08,
"london": 4031.9
},
{
"id": 794,
"first_name": "Katee",
"last_name": "Gopsall",
"email": "kgopsallm1@cam.ac.uk",
"ip_address": "203.138.133.164",
"latitude": 5.7204203,
"longitude": 10.901604,
"london": 3226.33
},
{
"id": 266,
"first_name": "Ancell",
"last_name": "Garnsworthy",
"email": "agarnsworthy7d@seattletimes.com",
"ip_address": "67.4.69.137",
"latitude": 51.6553959,
"longitude": 0.0572553,
"london": 12.56
},
{
"id": 322,
"first_name": "Hugo",
"last_name": "Lynd",
"email": "hlynd8x@merriam-webster.com",
"ip_address": "109.0.153.166",
"latitude": 51.6710832,
"longitude": 0.8078532,
"london": 41.28
},
{
"id": 554,
"first_name": "Phyllys",
"last_name": "Hebbs",
"email": "phebbsfd@umn.edu",
"ip_address": "100.89.186.13",
"latitude": 51.5489435,
"longitude": 0.3860497,
"london": 21.84
}
]
}

# Author

Justin Bosman
