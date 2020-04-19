# ttgo_lora
lora module project

# Dependencies
* adafruit SSD1306 (v2.2.1)
* LoRa (by Sandeep Misty) (v0.7.2)

# Troubleshooting notes:
* Was getting this error on sketch upload "AttributeError: 'Serial' object has no attribute 'dtr'" in ubuntu.
* Resolved by running
  * sudo apt-get remove python-serial
  * sudo pip install pyserial
