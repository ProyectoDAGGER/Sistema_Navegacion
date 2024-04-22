# Sistema_Navegacion


pasos a seguir 

Instalación Git
Abrir la consola y colocor los siguientes comandos

•	sudo apt-get update
•	sudo apt-get install git-all

Instalación Python
Abrir la consola y colocor los siguientes comandos

•	sudo apt install python3-pip





Ejecución Gazebo
Abrir la consola y colocor los siguientes comandos

•	$ cd ~/ src/Firmware
•	make px4_sitl_default gazebo



Instalación PX4
Revisar: https://dev.px4.io/v1.9.0/en/setup/dev_env_linux.html

Abrir la consola y colocor los siguientes comandos

•	$ git clone https://github.com/PX4/PX4-Autopilot.git --recursive
•	bash ./PX4-Autopilot/Tools/setup/ubuntu.sh
•	$ cd ~/

•	Wget https://raw.githubusercontent.com/PX4/Devguide/v1.9.0/build
_scripts/ubuntu_sim.sh

•	$ source ubuntu_sim.sh

•	Al finalizar el terminal nos dejara en la carpeta de instalación por defecto “src/Firmware/”




Instalación de librería MAVSDK
Abrir la consola y colocor los siguientes comandos

•	$ pip3 install mavsdk
•	$cd ~/
•	$ git clone https://github.com/mavlink/MAVSDK-Python.git


