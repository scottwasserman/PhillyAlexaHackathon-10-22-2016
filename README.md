# Philly Alexa Hackathon 10-22-2016
My hack (in every sense of the word) for the Philly Alexa Hackathon that took place on 10-22-2016. This Skill and Lambda won!
My buddy Marcus stood up a meteor-based end point on heroku to capture the data.  My other buddy Phil Moyer helped with the intents and utterances.

The goal was to easily collect systolic and diastolic blood pressure readings, store them remotely and give the user feedback on how the numbers rate according to the AHA and provide a chart of the readings. 

The details for these ratings can be found here:
http://www.heart.org/HEARTORG/Conditions/HighBloodPressure/AboutHighBloodPressure/Understanding-Blood-Pressure-Readings_UCM_301764_Article.jsp#.WBZaaeErKgQ
The blood pressure rating responses are hacked at the moment because of the time crunch and the Skill currently rates the readings. The meteor-based end point actually does the rating and gives the details in the response to data submission but it never got wired in.

I also wanted to tell the user to get to the E.R. after verifying their readings put them in the Hypertensive Crisis category.  Thanks for a recomendation from Phil Moyer to also ask if you'd like Alexa to call an ambulance if you're in Hypertensive Crisis.

We orginally wanted to do charting of the reading and have them show up on a Skill card but we ran out of time.

I'm going to keep this code as-is but I'm planning on building a more submission ready version in the near future.

Note: This was the first skill I ever built and loosely based off the spaceGeek sample code from here:
https://github.com/amzn/alexa-skills-kit-js
None of this is rocket science but hopefully you'll find it helpful.
