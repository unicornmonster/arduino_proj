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
 
 Parts used:
 Arduino MKR1000 (with headers) from Sparkfun (approx $36): 
 https://www.sparkfun.com/products/14393?gclid=EAIaIQobChMI2_2nx7Pe2QIVCbbACh3sQAQOEAAYASAAEgJB1vD_BwE
 
 Ultrasonic Sensor - HC-SR04 from Sparkfun (approximately $4)
 https://www.sparkfun.com/products/13959
 
 A small breadboard (approximately $4)
 https://www.sparkfun.com/products/12045
 
 4 wires, 2 resistors (27k, 15k - any 1/1.9 ratio over 1k should work) (a few bucks)
 
 Total cost for this project, under $50
 This can be done more cheaply, it is only an example!
 
 Here is the setup guide for the MKR1000:
 https://www.arduino.cc/en/Guide/MKR1000
 
 You CAN use the Arduino web IDE: https://create.arduino.cc/editor
 But, I used the software install: https://www.arduino.cc/en/Guide/HomePage
 
 
