# proj8
Snarf appointment data from a selection of a user's Google calendars

Author: Elijah Caluya 

## What is here

A web application that uses Google Calendar API to look through all google calendars
that a user may have and lists all the events for the specified range that the user
provided. The user can also set the parameters of time along with the date. Along with
showing the busy times in a range of dates and times, the program shows the free times
of a day below the list of events. All day events are also taken into account as there
will be no free time in the day if the event lasts the whole day.

To run:
-clone the repository
-then in the directory:
	bash ./configure
	source env/bin/activate
	python3 flask_main.py
-then open a web browser and open the page on localhost:50000




