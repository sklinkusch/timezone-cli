# Timezone CLI

## Let's write our first CLI app

We want to create a simple app that let's the user print out timezone informations.

For this we will use "http://worldtimeapi.org/"
Node does not know `fetch` so we will use [axios](https://github.com/axios/axios)

- you need two arguments for your script
  - area
  - city
- you should print out a help text when the user starts the script with --help
- by default you should just print the current time of the city

## Extra

- if no city is provided print out possible cities
- --unix prints out the time as a unix timestamp
- --dayOfTheYear prints out the current day of the dayOfTheYear
- --currentWeek prints out the current week
