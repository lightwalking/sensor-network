# sensor-network

Create a network of sensors and monitors around the home. The collected data will be used for general monitoring and possibly future AI experimentation. Server infrastructure will initially make use of existing Raspberry Pi cluster. May possibly expand server capabilities with the NVIDIA Jetson Nano. At least 1 node/floor but optionally expanded up to 1 node/room for a total of 3-10 nodes.

## Plan

### Possible Sensors, Monitors & other node components:
* Environmental sensors (i.e. temp, humidity)
* Light sensor (e.g. detect lights on/off)
* Motion sensor (e.g. detect movement)
* Sound dB sensor (e.g. detect noise levels)
* Camera 
* Microphone 
* Small Display (e.g. node identity, node status, display environment sensor data)

### Basic Requirements:
* Server
  * api server collecting node data
  * containerized running on sbc cluster
* Nodes
  * self contained (i.e. single unit plugged directly into a wall socket)
  * look presentable (i.e. no wired up frankenstein)
  * managed over private network

### Phase 1
* API server running on existing Raspberry Pi cluster
* 3 Raspberry Pi Zero W nodes (1 node/floor)
  * Required: Environmental sensors
  * Optional: Light, Motion, Sound dB sensors


## Resources and Component Ideas
EasyIoT
https://iot-playground.com/

Zero Stem for Pi Zero 1.3 and Pi Zero W 1.1
https://www.adafruit.com/product/3945

Block Adapter Charging Cube Box
https://www.amazon.com/Charger-Dodoli-Adapter-Charging-Compatible/dp/B07JHZXCQD/ref=pd_sim_107_4/134-6892326-4609555?_encoding=UTF8&pd_rd_i=B07JHZXCQD&pd_rd_r=9db82097-8858-11e9-ab7a-a558679371f6&pd_rd_w=2WHRa&pd_rd_wg=5mtbe&pf_rd_p=90485860-83e9-4fd9-b838-b28a9b7fda30&pf_rd_r=GZGG12R83AX9CY2QQ0E7&refRID=GZGG12R83AX9CY2QQ0E7&th=1

Home temperature monitoring
https://www.raspberrypi.org/forums/viewtopic.php?t=201333

Zero Lipo
https://www.amazon.com/Pimoroni-PIM181-Zero-Lipo/dp/B01JO2UK3Q

Battery Charger
https://www.amazon.com/Adafruit-PowerBoost-1000-Charger-Rechargeable/dp/B01BMRBTH2/ref=pd_bxgy_86_3/134-6892326-4609555?_encoding=UTF8&pd_rd_i=B01BMRBTH2&pd_rd_r=7351fbb1-8873-11e9-bb9f-d92b5009aa7b&pd_rd_w=7OHkM&pd_rd_wg=2AeZI&pf_rd_p=a2006322-0bc0-4db9-a08e-d168c18ce6f0&pf_rd_r=YQ8FFYHCMWFFWSB4599S&psc=1&refRID=YQ8FFYHCMWFFWSB4599S

NVIDIA Jetson Nano
https://www.nvidia.com/en-us/autonomous-machines/embedded-systems/jetson-nano/

ESP8266 Websockets
https://tttapa.github.io/ESP8266/Chap14%20-%20WebSocket.html
