## What is this?
This is the aci endpoint search tool python 3.6.

## Installation and Run
#### 1. Clone the repo
	git clone https://github.com/ComtecSystem-dev/cisco_aci_endpoint.git

#### 2. change into directory
	cd sico_aci_end_point

#### 3. Create the virtual environment in a sub dir in the same directory
	python3 -m venv venv

#### 4. Start the virtual environment and install requirements.txt from the 
	pip install -r requirements.txt 

## Run

#### change of the config
file : endpint.py
	
	# Setting
	APIC_IP = "<YOU_IP>"
	APIC_ID = "<YOU_ID>"
	APIC_PWD = "<YOU_PASSWORD>"

<img src="./image/config.png">

#### cli example
	python3 endpoint.py

<img src="./image/run.png">

## License
This project is licensed under the Apache License 2.0 - see the [LICENSE.md](./LICENSE.md).   file for details.
