# APOD

APOD is a website that show astronamical picture of the day.

Follows best production practice, build with consideration microservices in mind.

## Installation

Use the node package manager [npm] to install APOD.

```bash
npm install
```

## Usage

```SET Environments Variables
API_KEY = YOUR KEY
API_URL = https://api.nasa.gov/planetary/apod?api_key=
DB_USERNAME = MONGODB USERNAME
DB_PASSWORD = MONGODB PASSWORD
HOSTNAME = http://localhost:3000 or any
```
## FEATURE
Request logs -> logs/requestlogger.log

Error logs   -> logs/errorlogger.log

Follows MVC controller pattern

Easy to maintain

Server Side Rendering

Download images using streams
