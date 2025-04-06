# WLED Controller (ESP32) - 4 Channels - Current and power monitoring

### ❤️💰 Donation - Help a student pay rent

<a href="https://buymeacoffee.com/lostincompilation" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: 41px !important;width: 174px !important;box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;" ></a>

## You can buy the PCB in my shop
Buy the PCB here (available in 2 days): https://buymeacoffee.com/lostincompilation

## Features
- 4 Channels
    - Max 25A total
    - Max 10A per channel
- Every channel has _independent_ current, power and voltage monitoring (using INA219)
- Sending power monitoring data to HomeAssistant via MQTT
- Relay for cutting power to LED-strips
- Touch surface on PCB (next to LED) usable as custom button
- SMD-1206 parts for easy hand soldering
- Reverse polarity protection
- Seperate 3.3V low noise voltage regulator for audio section
- _**Optional:** INMP441 I2S Microphone with low noise power supply_
- _**Optional:** Line-In Audio with extension board (I2S ADC: PCM1808)_

## Usermod
This board requires a usermod for WLED for full support of all features including power monitoring.

_**NOTE:** The usermod is currently in development and will be uploaded to thtis repository._

## 3D Board view
<p align="center" width="100%">
<img src="/plots/3d_front.png" alt="3D PCB"/>
<img src="/plots/3d_back.png" alt="3D PCB"/>
</p>

## Board
<p align="center" width="100%">
<img src="/plots/board/board_front.png" alt="3D PCB"/>
</p>
