##Connected barometer tutorial

This is the code used for the [connected barometer tutorial]() and the corresponding arduino shield.

![alt tag](http://digitaljunky.io/wp-content/uploads/2015/09/DSC_0152_small-788x443.jpg)

Data is collected from the following sensors : 
* DHT11 : humidity and temperature sensor,
* BMP180 : barometric pressure and temperature sensor,
* Photoresistor to measure the light intensity. 

An ESP8266-1 WiFi module is used to push the data online.

The home-made Esp8266 class is used to communicate with the module. The following public methods are available : 
* void begin()
* bool reset()
* bool isOk()
* bool isBusy()
* bool isConnected()
* bool connectWifi()
* bool openTCPConnection()
* bool closeTCPConnection()
* void send()
* void printDebug()
