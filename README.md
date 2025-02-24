# YI Smart Dash Camera
CVE-2024–56897

## Vulnerable Model
 - YI Smart Dash Camera
 - Firmware v3.88
 - Reference: https://yitechnology.com.sg/products/dash-camera/

## Unrestricted HTTP server for file downloads, uploads, and API commands
Once connected to a YI Car Dashcam using default/weak credentials, the http server is open for direct access without further authentication. API commands can also be made to make unauthorized modifications to the device settings, such as disabling recording, disabling sounds, factory reset.

![image](https://github.com/user-attachments/assets/14b96933-7316-403d-b729-5f4880d8aacd)

*http server with unrestricted downloads*


![image](https://github.com/user-attachments/assets/03070c7e-cbb4-4821-a965-aaa82e4e5521)

*scripted dump of all recordings*


![image](https://github.com/user-attachments/assets/b610ac7b-dcef-4065-9531-a3c27f7106cd)

*scripted change of camera settings*


![image](https://github.com/user-attachments/assets/37e8d6ef-6d0a-4a1c-b572-fee2b0faf509)

*upload function open*
