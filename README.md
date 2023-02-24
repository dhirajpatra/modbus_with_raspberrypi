## How to quick test modbus TCP with raspberrypi

This a template application for quick setup and test modbus with raspberry pi and python to read and write the register

### Installation

* Run following commands: 

`sudo apt-get update`

`sudo apt-get install python-dev`

`sudo apt-get install python-pip`

`pip install -r requirements.txt`

* Open this link https://www.modbusdriver.com/diagslave.html and
install this modbus slave into your raspberrypi
* Now keep running the relay service for modbus in raspberrypi
* Update both read and write register python files in repo with your raspberry IP address. keep the port as it is.
* Open one terminal tab in your laptop and run `python write_register_modbus.py`
* Open another terminal tab in your laptop and run `python read_register_modbus.py`

You can see that writing and reading into raspberrypi register continue until you inturrupt 


### References 

https://www.youtube.com/watch?v=nelI0ErgYuk