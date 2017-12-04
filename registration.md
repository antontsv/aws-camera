Camera Registration
===================

* Sign in at https://concole.aws.amazon.com

* Start device registration at  https://concole.aws.amazon.com/deeplens

* Register new IAM for the camera
![IAM Roles](images/setup/DL-Registration-1.png "Define new roles")

* Download certificates for the camera/device
![Device certificates](images/setup/DL-Registration-2.png "These certificates will need to be added to device later")

* Connect device to network via Wifi or USB-Ethernet
![Network connectivity](images/setup/DL-Registration-3.png)

## Local setup on device:


<p style="color: #8a6d3b; background-color: #fcf8e3;">
❗Please make sure you are on <b>trusted WiFi</b> or local network where all devices are known and trusted. Otherwise any unknown or compromised device may sniff your device password setup and security certificates.
</p>

* Upload certificate zip
![Certificated to device/camera](images/setup/DL-Registration-On-Device-1.png)

* Password/SSH setup
![Access](images/setup/DL-Registration-On-Device-2.png)

* Final confirmation
![Confirmation](images/setup/DL-Registration-On-Device-3.png)

Back in AWS console you should see newly registered deeplens device:

![Device list](images/setup/DL-Registered-Device.png)

