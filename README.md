Device yang dapat mengukur Suhu, Kelembaban, dan Jarak dengan protokol komunikasi Modbus RTU

Komponen yang digunakan adalah:
   * ESP32
   * DHT 22 / DHT 11
   * HC-SR04
   * RS-485 to UART Converter
     
Library yang digunakan:
   * DHT-sensor-library by Adafruit https://github.com/adafruit/DHT-sensor-library
   * modbus-esp8266 by emelianov https://github.com/emelianov/modbus-esp8266

FUNCTION MODBUS : 
   * INPUT REGISTER (0x04)
  
ADDRESS MODBUS:
   * 1 = Temperature
   * 2 = Humidity
   * 3 = Distance (Cm)
