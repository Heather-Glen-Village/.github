## HGV Codebase
This is the HGV Codebase where the whole project can be found here. This Project is split into a few Repositories with all major Parts and System Listed Below in the Flowchart. extra info for each can be found in each of the dedicated repositories.

### 1. HGB-Arduino 
- Is the First part of the Projects
- Gather Sensor data and Sends it off to other systems
- Controls The Rooms Tempature with request from the Website 
### 2. HGV-Middleware
- Contains the Docker Compose files and other Conf Used to Setup the middleware thats used to connect the Arduino to other Systems
- Currently All Middleware is Running off of REMS006 in Docker Container 

### 3. HGV-Website
- Is the user interface that people interact with and display the Arduino data in a Readable Format
- Sends messages Back to the Arduino to Change the Room Tempature like a Digital thermostat
- Has other pages which display activities taking place in the village
- has a page that create reports that are send to a support Email 
- Currently have the whole website running on REMS007

### HGV-Test-Code (Extra)
- Stores many of the test code for Arduino, Python and other programs to make sure the hardware is working
- Isn't used in the final project but is useful to for test problems

![image](https://github.com/user-attachments/assets/a9d14921-8f8d-4488-ada5-d5ea3c2b6ea3)

## Contributing
for more information on Contributing to the Codebase, please read the How to use Github Document found in the HGV Wiki
