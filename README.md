# **Portable device and mobile application for the detection of ultraviolet radiation in real-time with a low-cost Arduino sensor.**
   
**The UV READER mobile application is implemented with Bootstrap and Jquery as a framework, its main screen shows the status of the sensor whether or not it is connected to the application. It also has the last recorded connection and a speedometer that shows the UV radiation index in real-time, with a measurement every second and a delay of one second every three hours.**
**As for the design of the UV speedometer, a JavaScript library called “Gauge.min.js” is used.
The data processing is shown in the upper right in an option called reporting; it displays by date, the measurements that are made. The application table shows the last 100 records that have been entered in the mobile database. Likewise, the data is validated on a graph averaged every 30 minutes..**

![](https://github.com/nebelfvs/NeBla/blob/master/Interface-UvReader.PNG)

**In the present image the measurement is made with a UV lamp then the other images are the measurements made with the sun's UV rays. In the end the dimensions of NeBla.**

![](https://github.com/nebelfvs/NeBla/blob/master/Kit-UvReader-NeBla.PNG)

**The architecture device NeBla, utilizes an Arduino family model UNO card, a UV sensor, an RTC (Real-Time Clock), a Bluetooth module for communication and an SD module for data storage in plain text.**

![](https://github.com/nvieras/NeBla/blob/master/Conexiones-Nebla.PNG)

**Measurements made.**

**In order to obtain the results of the UV radiation index for this project, respectively; we place two prototypes in the north and south in the city of Guayaquil 2 ° 09'25.8 "S 79 ° 56'01.8" W and 2 ° 13'39.2 "S 79 ° 54'13.9" W. The data is collected in the date range from April 7, 2019, until July 28, 2019. The schedule is established for the measurement of UV rays in the period from April to July are from 07:00:00 to 19:00:00. The sensor results are measured in (mW/cm2) and the corresponding voltage for each UV unit.**

![](https://github.com/nebelfvs/NeBla/blob/master/comparacion-norte-sur.PNG)

**Download APK**
http://bit.ly/Apk-UvReader-Ingles

**Arduino IDE**
http://bit.ly/Arduino-IDE-Codigo

**Developed by:** nvieras@est.ups.educ.ec brodriguezm2@est.ups.edu.ec jllerena@ups.edu.ec
