# Mini-Project-Python-for-Mpu6050-Servo-Motor
This is a mini project for using MPU 6050 sensor to get Pitch and roll angles and apply them on Servo motor using Raspberry pi.

Embeddded systems mini project.
Abdelrahman Bedier. ID:201400473
Abdelrahman Nasser. ID:201500899
Ahmed Hassan. ID:201501642

# Programs used:
VScode in raspberry pi.
python3.

# Libraries used:
python-pip.
GPIO.
smbus.
MPU6050.

# How to Reproduce:
First Enable I2C communication by writing this command in terminal:
"sudo raspi-config".
then choose Interfacing options then choose I2C then Enable it then reboot by this command:"sudo reboot".

Second you install the libraries mentioned above by these commands in teminal:
"sudo apt-get install build-essential python-dev python-pip".
"sudo pip installs RPi.GPIO".
"sudo apt-get install python-smbus".
"sudo pip install mpu6050".
if these libraries are installed,there is no need to reinstall them.

Third clone the code from github by this command in terminal:
"git clone https://github.com/Abdelrahman-bedier/Mini-Project-Python-for-Mpu6050-Servo-Motor"

Forth open folder UninterruptedAngleMeter and run the file AngleOMeter.py by command : "python AngleOMeter.py" into the terminal of vscode.

The Schematic is in the folder Images with a LCD if needed.

# Hardware Used:
Raspberry Pi.
MPU-6050 sensor.
Jumper wires. 
Breadboard.
Servo Motor.
Keyboard and Mouse.
Screen or LCD.

# Link to trial Video : https://drive.google.com/file/d/1NxxhI4pp12hGVc7G-3QvEobcQ61rng17/view?usp=sharing
