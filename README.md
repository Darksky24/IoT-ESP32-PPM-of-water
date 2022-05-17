
# IoT-ESP32-PPM-of-water
Measuring the ppm of liquid solution (salt water) using ESP32 and communitcate to the Thingspeak server
then display the information on an android app

## Acknowledgements

 - [Sample Demonstration](https://www.youtube.com/watch?v=b-bDwB62Qgw)


## Authors

- [@Darksky24](https://github.com/Darksky24)


## Deployment

- The system is built using ESP32 and the knowledge from Embeded course we have learnt
- The sensor measures will send the infomation on the Thingspeak server using POST Method
- The android display app will then retrieve the data through MQTT protocol

## Features

- The system will display the measure infomation on an LCD screen with GET calling Thingspeak API
- Debouncing the button
- The system has 4 modes control through a button mode:
The first is â€™waiting modeâ€™: the system do nothing and wait user change to the next mode
â€™measuringâ€™.

The second mode â€™measuring modeâ€™: the system do measurement of TDS value throw TDS
sensor and upload to thingspeak server in cyclical operation.

The third mode â€™review dataâ€™: the system get 10 most recent data which user can review it through left or right button.

The fourth mode â€™change measurement periodâ€™: the system allow user to change the period
of measurement in â€™measuring modeâ€™ . Set the period by pushing the enter button(Default period is 15 seconds) 

![alt text](https://user-images.githubusercontent.com/91105484/168829306-7d8530da-26d7-4c58-9b4f-4758cc0c51f6.jpg)
## Deployment

- The system is built using ESP32 and the knowledge from Embeded course we have learnt
- The sensor measures will send the infomation on the Thingspeak server using POST Method
- The android display app will then retrieve the data through MQTT protocol
