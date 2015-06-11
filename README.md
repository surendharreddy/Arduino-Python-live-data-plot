#Arduino TMP36 temperature sensor live data ploting using Python Matplatlib library.

###Follow the steps and use the code to plot live data from Arduino.
* Connect TMP36 sensor to Arduino  as shown below.

![Alt text](https://learn.adafruit.com/system/assets/assets/000/000/476/medium640/temperature_tmp36fritz.gif?1396763381)

* Upload TEMP36.ino code to you Arduino UNO R3 board using Arduino IDE (version 1.6.4 is preffered)
* After uplading code check the connections and check serial moniter for data.
* Now, donwload and run TMP36.py, this will give a figure ploting live data which is retrived from serial port of your Arduino UNO board.

![Alt text](http://i.imgur.com/BlT9dJM.png?1)

* This ploting is done using Python [Matplotlib](http://matplotlib.org/) and [drawnow](https://pypi.python.org/pypi/drawnow/0.44) libraries.


#Updates are appreciated. Thanks.
