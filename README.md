# APOD

APOD is a website that show astronomical picture of the day.

Follows best production practice, build with consideration *microservices* in mind.

Live Demo - https://quantiply.herokuapp.com
## Installation

Use the node package manager [npm] to install APOD.

```bash
npm install
```

## Database configuration

Go to database/db.js

Here you should paste you connection string

## Environmental Variables

```
API_KEY = YOUR KEY
API_URL = https://api.nasa.gov/planetary/apod?api_key=
DB_USERNAME = YOUR MONGODB USERNAME
DB_PASSWORD = YOUR MONGODB PASSWORD
HOSTNAME = http://localhost:3000 or any
```
*API_URL IS SAME AS MENTION ABOVE*


## FEATURE
Request logs -> logs/requestlogger.log

Error logs   -> logs/errorlogger.log

Follows MVC controller pattern

Easy to maintain

Server Side Rendering

Download images using streams

## Important

To acheive full utilization of cpu you can enable all process by installing pm2 as  global package and after installing hit below command


```
pm2 start app.js -i max
```

*Redis cache has not integrated because mongodb automatically fetch data from RAM for this use case*
