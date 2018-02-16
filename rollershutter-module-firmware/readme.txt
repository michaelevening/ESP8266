SUPLA WIFI ROLLER SHUTTER MODULE
v2.5.3

boot_v1.5.bin--------->0x00000
rs_module_user1.2048.new.2.bin---->0x01000
esp_init_data_default.bin---->0xfc000

BAUDRATE: 115200
Flash Size: 2MByte (16Mbit-C1)
Flash speed: 40Mhz
SPI Mode: DIO

PORT SETTINGS:

  RELAY1 GPIO4
  RELAY2 GPIO5
  BTN1 GPIO13
  BTN2 GPIO14
  CFG BUTTON GPIO0
  LED GPIO16 
  SENSOR GPIO 12

// CFG MODE ----------------------------------------

To bring the device into configuration
mode, press and hold button for at least 5 sec. When in configuration mode,
the device goes into Access Point mode.

In order to enter or change the settings, you need to:

- Sign in at https://cloud.supla.org (registration is free of charge)
- Connect to WiFi called „SUPLA-ESP8266” from any computer with a wireless network card and Internet browser.
- Open access page: http://192.168.4.1
- Enter user name and password to the WiFi through which the device will get Internet access.
- Enter Server and e-mail address, which will be provided once you sign in at cloud.supla.org

