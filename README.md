# SensorsDB-To-Web

Assuming sensor values are received and saved in DB.

Step One: Designing the DB

DB Chosen: MongoDB
npm used: mongoose
Sensor Models' Schema:  
Schema({
    value: Number
});
Simple structure, to simulate the actual values incoming from sensors

DB name: sm-sensor
Collections in DB: sensors


Step Two: Setting up the server
The server used: express (npm) 
For simplification, the data fetched from DB is set on the default route(‘/’).
Data is fetched from DB by the “GET” method.
Express route: app.get(“/”, …..)

Data is fetched from DB and passed to the rendered index page

Step Three:
Simulating DB data through seeding fake values. 

Step Four:
Display data on the index page by looping over the object returned by DB.
Dynamic pages is done through .ejs


 


 





