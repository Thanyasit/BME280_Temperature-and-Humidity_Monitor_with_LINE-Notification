# BME280_Temperature-and-Humidity_Monitor_with_LINE-Notification
<h2>Description</h2>
This program monitors the temperature and humidity using a BME280 sensor and sends notifications to your LINE account using the LINE Notify API.
<h2>Prerequisites</h2>

- Arduino IDE<br>
- ESP8266WiFi library<br>
- WiFiClientSecureAxTLS library<br>
- DNSServer library<br>
- ESP8266WebServer library<br>
- WiFiManager library<br>
- TimeLib library<br>
- Wire library<br>
- SPI library<br>
- Adafruit_Sensor library<br>
- Adafruit_BME280 library<br>
- A LINE Notify API access token<br>
<h2>Installation</h2>

1. Clone this repository or download the source code.<br>
2. Open the Arduino IDE and navigate to <b>Sketch > Include Library > Manage Libraries.</b><br>
3. Search for and install all of the required libraries listed above.<br>
4. Open the <b>BME280_Temp_Humid_Monitor_with_LINE_Notification.ino</b> file in the Arduino IDE.<br>
5. Replace <b>LINE_TOKEN</b> with your LINE Notify API access token.<br>
6. Connect your ESP8266 board to your computer via USB and select the appropriate board and port in the Arduino IDE.<br>
7. Upload the sketch to your ESP8266 board.<br>
<h2>Usage</h2>

1. Connect your BME280 sensor to the ESP8266 board according to the wiring diagram in the source code.<br>
2. Power on the ESP8266 board.<br>
3. Wait for the ESP8266 board to connect to your Wi-Fi network.<br>
4. Wait for the ESP8266 board to synchronize the time with an NTP server.<br>
5. Wait for the notification to be sent to your LINE account at the specified time interval (default is every 30 minutes).<br>
<h2>License</h2>
This code is licensed under the MIT License. See the LICENSE file for details.
