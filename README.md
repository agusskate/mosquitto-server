### 1. Iniciar servidor

docker run -it --name mosquitto-test ^
 -p 1883:1883 ^
 -p 9001:9001 ^
 -v C:\mosquitto\config:/mosquitto/config ^
 -v C:\mosquitto\data:/mosquitto/data ^
 -v C:\mosquitto\log:/mosquitto/log ^
 eclipse-mosquitto
