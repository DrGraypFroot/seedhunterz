# seedhunterz
A project with the aim of creating a web-based monitoring tool using adafruit temp/hum. sensors and a webcam.

Functions:
- python-script reads the temperature and humidity values using the adafruit library
- the data will then be injected into a database (mysql or mongo, not sure yet)
- using php and html (probably with the bootstrap framework) a webpage will be hosted on a webserver
- the webpage will be accessible via secure authentication
- the webpage will contain current humidity and temperature values, as well as a live-stream (webcam) and a graph for both values over a modifyable timeperiod
- also every hour a picture will be saved for later use (timelapse etc.)
