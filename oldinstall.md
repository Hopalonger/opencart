## Install Instructions for LoRa Client
1. Donwload and Install the Arduino IDE for you Computer Platform and Down Load the Repository. 
2. Plug Arduino Of Choice into Computer (Arduino Pro Mini Recommened)
3. Open The Code That is in the in the CLient Code folder of LoRa. 
4. Install the used Libarys Which include `Arduino-LoRa` and `Adafruit_NeoPixel`.
5 Change Any of The Varibles that Are in the top Or Middle of the Code.
6 Select The COM port that the Arduino Corresponds to in the Tools Tab.
7 Hit the Upload Button in the top left. (The Arrow to the Left).
8 Attach the LoRa Module to the Arduino Based off Diagram Below.

| Semtech SX1276/77/78/79 | Arduino |
| :---------------------: | :------:|
| VCC | 3.3V |
| GND | GND |
| SCK | SCK |
| MISO | MISO |
| MOSI | MOSI |
| NSS | 10 |
| NRESET | 9 |
| DIO0 | 2 |

9.Connect Your Choice of Addressable LEDS to the Arduino on the Pins Selected in the Code.
10. Power Up the Device on a 3.3v Power Source. Do Not use 5v, LoRa Boards Do Not Use 5v.
## Install Instructions for the LoRa Repeater
1. Follow this Guide For Wiring. Instuctions where Obtainted from [AdaFruit](https://learn.adafruit.com/neopixels-on-raspberry-pi/wiring)

2. Once finshed Clone the Repository to your computer with the `git clone https://github.com/Hopalonger/Simple-Organization.git` Command
3. Navigate to the LoRa Repeater Folder With `cd Simple-Organization/LoRa/Repeater-Code/RaspberryPi`
4. Run the Install.sh Script with `sudo bash install.sh`
5. Edit The Script.py File LED and Large Tray Settings at the Top of the Page to correspond with the Installation you are running
6. Reboot Device 
7. The Device Should be Working
