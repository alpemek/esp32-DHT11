# ESP32-DHT11
Esp-idf driver for DHT11 temperature and humidity sensor.

## Usage
1. `cd $YOUR_PROJECT_PATH/components/`
2. git clone https://github.com/alpemek/esp32-DHT11.git
3. Import dht11.h in your code 
4. Initialize the device with DHT11_init(gpio_num)
5. Call DHT11_read() to read from the DHT11 sensor<br/>


<b>WARNING</b>: DHT11_read() is a blocking function.
