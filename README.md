# weather-cardputer
Simple weather app for M5Stack Cardputer
![IMG_1148](https://github.com/qubiX00/weather-cardputer/assets/115372907/a81f905b-607e-4128-98f9-cd7eb826c8a3)

# requirements
- M5Stack Cardputer
- SD Card
- Arduino IDE and libraries: M5Cardputer, WiFi, HTTPClient, ArduinoJson
- M5Launcher firmware installed on M5Stack Cardputer
- OpenWeatherMap API Key

# installation
Download weather-cardputer.ino and open it in Arduino IDE. Go to Tools > Board and select M5Stack > M5StampS3. Fill in your WiFi SSID, password, OpenWeatherMap API Key and your city. Then Go to Sketch > Export Compiled Binary and wait until it finishes. After that go to Sketch > Show sketch folder, then go to build/m5stack.esp32.m5stack_stamp_s3 and there should be a file called weather-cardputer.ino.bin. Put it on your SD Card, then put the SD Card in your M5Stack Cardputer and launch it from the M5Launcher. That's pretty much it, enjoy!
