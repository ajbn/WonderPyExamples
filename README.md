# Extending WonderPyExamples by AJBN
This project extends the original examples and tutorials for the [WonderPy Python API](https://github.com/playi/WonderPy) for working with [Wonder Workshop](https://www.makewonder.com) robots in two ways:
1. track the robot on a floor mat or map. and
2. issuing commands using tangibles blocks with NFC tags

# Project Status
They are at an "Alpha" release and were tested with the Dash robot.

## Tracking the Dash robot on a mat or map
### Setup
#### Prerequisites
1. MacOS
2. [reacTVIsion 1.5.1](http://reactivision.sourceforge.net)
3. Python 2.7
4. [pyTUIO](https://code.google.com/archive/p/pytuio/)
5. [Processing](http://processing.org)


## Issuing commands to Dash using tangibles blocks with NFC tags
### Setup
#### Prerequisites
1. MacOS
2. Python 2.7
3. [pySerial](https://pyserial.readthedocs.io/en/latest/index.html)
4. [Arduino IDE](https://www.arduino.cc/en/Main/Software)
5. [Arduino RFID Library for MFRC522](https://github.com/miguelbalboa/rfid)
6. an Arduino board with Serial Peripheral Interface (SPI) interface. I have been using an Arduino Mega 2560 board
7. a MF RC522 RFID based reader. I have been using a model from [Velleman bought at Mauser.pt](https://mauser.pt/catalog/product_info.php?cPath=1667_2604_2607&products_id=096-4672)
8. a Bluetooth serial communication module. I have been using a [HC-06 model bought at BoxEletronica](https://www.boxelectronica.com/pt/bluetooth/135-hc-06-bluetooth.html)
