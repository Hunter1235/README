Hunter Stiles

Project 1

https://github.com/Hunter1235/Project-1

This program reads GDP data for the US and China.  It figures out the
average yearly growth for each country and use it to predict the growth.
until 2030.  It creates a graph showing the GDP for the US and China, that
includes the predicted years until 2030. This was the first project which
was done a few weeks into the python course.




Project 2

https://github.com/Hunter1235/Project-2

phone.py

This is the main application,  
I decided to make a softphone  and  found that twilio was a library that
could create a client and place calls from a python application.  So I
started building my app.  I found that twilio is built for people that
want voice enabled applications to interact with people.  After placing a
call, it seams that it is the application that is meant to interact with
who ever answers the phone. There appears to be no simple way to have the
call get an audio stream from the microphone or send audio to the computer
speakers. Twilio does allow another call to be placed  which ties another
person into the original phone call.  So this softphone will connect you to
the number you dialed by first  calling you on your phone and then ringing
the number dialed.  Your phone number can be configured by setting the
environmental variable MYPHONE.  The default is my cell phone.  Of course,
you could change the code to have the default be your phone number for testing.
The softphone also lets you to send an SMS text message or if you need to get
the message to a number that isn't a cell phone,, you can send the message
via voice. The softphone will call the number and read it after the phone is
answered using text to speech.




Project 3

https://github.com/Hunter1235/Project-3

This application will scan the CVS website for locations in New Jersey
that have vaccine appointments available. When new appointments become
available, it will be recorded in a database. Then, if the newly recorded
availability is at a location that is within a specified radius of the
user's location, it will notify them by text message, phone call, and/or
email. The user will be able to choose to be notified in any combination
of these 3 ways.
