# arduino_proj

This is a quick DIY Arduino intruder alarm, based on the project by Wirebeings: 
(http://wirebeings.com/arduino-intruder-alarm.html)
 
 The code here is slightly modified from the version found on that site, because 
 the hardware this uses is slightly different.
 
 The hardware this project uses is listed below. The Wirebeings project lists 
 a different hardware set. You can feel free to experiment with your own. You
 will need wireless (to send the SMS via a Wireless network using something like
 Twilio with the Temboo wireless library), or a SIM and cellular account, and you
 will need some sensor to trigger the alarm. A few ideas in the ideas, below.
 
 # Parts used:
 Arduino MKR1000 (with headers) from Sparkfun (approx $36): 
 https://www.sparkfun.com/products/14393?gclid=EAIaIQobChMI2_2nx7Pe2QIVCbbACh3sQAQOEAAYASAAEgJB1vD_BwE
 Schematic: https://cdn.sparkfun.com/assets/2/7/0/7/4/MKR1000-schematic.pdf
 
 
 Ultrasonic Sensor - HC-SR04 from Sparkfun (approximately $4)
 https://www.sparkfun.com/products/13959
 Datasheet: https://cdn.sparkfun.com/datasheets/Sensors/Proximity/HCSR04.pdf
 
 A small breadboard (approximately $4)
 https://www.sparkfun.com/products/12045
 
 4 wires, 2 resistors (27k, 15k - any 1/1.9 ratio over 1k should work) (a few bucks)
 
 Total cost for this project, under $50
 This can be done more cheaply, it is only an example!
 
 # Resources
 I used this to calculate what resistors to use:
 http://www.ohmslawcalculator.com/voltage-divider-calculator
 (the source (the ultrasonic sensor) is 5 volts, the output needs to be around 3 volts (the MKR1000
 Circuit Operating Voltage is 3.3V))
 
 Here is the setup guide for the MKR1000:
 https://www.arduino.cc/en/Guide/MKR1000
 
 This is a nice getting started guide:
 https://create.arduino.cc/projecthub/charifmahmoudi/arduino-mkr1000-getting-started-08bb4a
 
 You CAN use the Arduino web IDE: https://create.arduino.cc/editor
 But, I used the software install: https://www.arduino.cc/en/Guide/HomePage
 
 # Ideas
 Here are some other projects that use Arduino:
 
 Greenhouse monitor:
 https://create.arduino.cc/projecthub/dasdata/dasfilisera-green-house-99b2df?ref=tag&ref_id=mkr1000&offset=2

 Smart "home" automation for your camp:
 https://www.hackster.io/cybermah/home-automation-system-for-a-camp-with-cellular-internet-14d229
 
 Weather monitor:
 https://www.hackster.io/officine/getting-weather-data-655720
 
 Remote controled people:
 https://www.hackster.io/PureCarbon/worlds-first-remote-control-human-ea6d0e
 (These are fun experiments in human/technology interactions)
 
 Water quality monitor:
 https://www.hackster.io/animo/water-quality-monitoring-using-mkr1000-and-artik-cloud-840fea
 
 The microclimate research:
 https://www.pubnub.com/blog/2016-06-29-wirelessly-tracking-temperature-data-with-the-arduino-mkr1000/
 
 # Other Arduino projects
 
 Enabling the disabled: Eye writer
 http://www.instructables.com/id/The-EyeWriter-20/
 
 Seeing eye (using the Ultrasonic range sensor):
 https://create.arduino.cc/projecthub/muhammedazhar/third-eye-for-the-blind-8c246d
 
 Prosthetics:
 https://digitalcommons.csbsju.edu/cgi/viewcontent.cgi?article=1052&context=honors_theses

 Space. Yes. Space.
 https://blog.arduino.cc/2013/08/12/ardusat-successfully-launched-in-space/
 
 Exploring our oceans:
 https://www.treehugger.com/gadgets/researchers-build-arduino-powered-robot-scanning-coral-reefs.html
 
 Earthquake monitoring:
 https://blog.arduino.cc/2011/08/02/chilean-teen-twitts-about-earthquakes/
 
 Clean water:
 https://www.wef.org/globalassets/assets-wef/3---resources/for-the-public/stockholm-junior-water-prize/winning-research/2.-u.s.-national-winners/2017-national-winner---rachel-chang-ryan-thorpe.pdf
 
 Air pollution monitoring:
 http://geojournalism.org/2014/04/dustduino-arduino-uno-edition/
 
 Aquaponics:
 https://faircompanies.com/videos/internet-of-food-arduino-based-urban-aquaponics-in-oakland/
 
 # Contact me
 unicornmonster@happypacket.net
