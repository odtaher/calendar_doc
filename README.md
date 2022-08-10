# Events Calendar

## Technology Stack

Database: MongoDB
API: Python 3.9 / Flask
Frontend: VueJS 3
Environment: Docker / Docker compose

## To run

* create a directory 
* clone 3 repositories inside it
  > git clone https://github.com/odtaher/calendar_front
  > 
  > git clone https://github.com/odtaher/calendar_api
  > 
  > git clone https://github.com/odtaher/calendar_doc 
* copy docker-compose.yaml to the newly created directory:
  > cp calendar_doc/docker-compose.yaml .
* Run docker compose 
  > docker-compose build
  >
  > docker-compose up
* Visit http://127.0.0.1:8080/


## Features:
* Adding an event: by clicking on the button that appears in a time slot
* Viewing event info: by clicking on an event
* Deleting an event: by clicking on an event and then ‘delete’
* View types: month, week, day
* Update events by Dragging and dropping ( supported only in week view )
* Next / previous period (day, week, month)
* Avoids event overlapping on create and on drag and drop
* Not forgetting your view type and date selections - thanks to browser local storage

## Known Issues:
- The calendar works only in GMT time zone
- Week view: switching dates leaves flex-basis left overs, making drag and drop buggy
- List view is missing
- Only ‘Week-View’ supports Drag and Drop
- Quirky on mobile and small screens
- Browser back/forward button are not supported


