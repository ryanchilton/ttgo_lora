# ttgo_lora
lora module project

Troubleshooting notes:
* Was getting this error on sketch upload "AttributeError: 'Serial' object has no attribute 'dtr'" in ubuntu.
* Resolved by running
** sudo apt-get remove python-serial
** sudo pip install pyserial
