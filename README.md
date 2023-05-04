# ESP32-Starterkit
This is a package for getting started with the ESP32/Arduino.

It contains a basic project structure and includes everything to configure, store and update the network settings of your ESP32 via browser.
After the initial setup the ESP32 is also ready to receive OTA uploads through platform.io
for wt32 eth :
#define ETH_ADDR 1		 // I²C-address of Ethernet PHY (0 or 1 for LAN8720, 31 for TLK110)
#define ETH_POWER_PIN 16 // Pin# of the enable signal for the external crystal oscillator (-1 to disable for internal APLL source)
#define ETH_MDC_PIN 23	 // Pin# of the I²C clock signal for the Ethernet PHY
#define ETH_MDIO_PIN 18	 // Pin# of the I²C IO signal for the Ethernet PHY
