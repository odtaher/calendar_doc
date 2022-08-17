# Events Calendar

## Technology Stack

Database: MongoDB
API: Python 3.9 / Flask
Frontend: VueJS 3
Environment: Docker / Docker compose
Dependencies: Full Calendar, MomentJS
Styling Packages: Material Design, Tailwind

## To run

* create a directory 
* clone 3 repositories inside it
  > git clone https://github.com/odtaher/calendar_front
  > 
  > git clone https://github.com/odtaher/calendar_api
  > 
  > git clone https://github.com/odtaher/calendar_doc 

* Make sure there are 3 directories with the names:
  * api
  * frontend
  * doc
* copy docker-compose.yaml to the newly created directory:
  > cp calendar_doc/docker-compose.yaml .
* Run docker compose 
  > docker-compose build
  >
  > docker-compose up
* Visit http://127.0.0.1:8080/


## Features:
* Creating events
* Updating events 
* Deleting events
* Resizing events 
* Moving events
* View types: month, week, day, list
* Avoids event overlapping on create and on drag and drop
* Avoids past events
* Not forgetting your view type and date selections - thanks to browser local storage
* User timezone friendly

## Known Issues:
- None 

