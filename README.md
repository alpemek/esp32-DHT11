# ESP32-DHT11
Esp-idf driver for DHT11 temperature and humidity sensor.

## Install
Clone this repository inside PROJECT_PATH/components folder

## Usage
1. Import dht11.h inside your program 
2. Initialize the device with DHT11_init(gpio_num)
3. Call DHT11_read() to read from the DHT11 sensor<br/>


<b>WARNING</b>: DHT11_read() is a blocking function.
