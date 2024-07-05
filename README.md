Device yang dapat mengukur suhu, Kelembaban, dan jarak

Sensor yang digunakan adalah:
   * DHT 22
   * HCSR-04
Library yang digunakan:
   * DHT-sensor-library by Adafruit https://github.com/adafruit/DHT-sensor-library
   * modbus-esp8266 by emelianov https://github.com/emelianov/modbus-esp8266

FUNCTION MODBUS : INPUT REGISTER (0x04)
  
ADDRESS MODBUS:
   1 = Temperature
   2 = Humidity
   3 = Distance (Cm)
