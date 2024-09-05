# Hyper Rear DC Coax 15A Max with uSD Card and USB2.0 
This is Rear Panel PCB  for DC COAX up to 15A , microSD Card support with 0-3mm Metal thickness Panel, USB 2.0 Connector 
-Designed to Connect to Arduino ISP Directly but need to replace Reset Pin with I/O as SS Pin
-also working good with 3V Bus as ESP32 as 3.3V Pullup on Board
-This is easier for user to make production 


NOTES!!!: Can be your prototyping and include to your production but not for distribution

  SD card read/write

  This example shows how to read and write data to and from an SD card file
  The circuit:
   SD card attached to SPI bus as follows:
           MK-ZERO    UNO/MEGA328    MEGA2560     LSR-REAR    LSR-ONBOARD    ESP32
 ** MOSI - pin 11     11             51           51          51             IO23   
 ** MISO - pin 12     12             50           50          50             IO19
 ** CLK -  pin 13     13             52           52          52             IO18
 ** CS -   pin 4      10             53           53          24             IO5

Notes: 1. LSR BOARD Ensure J31 Set SS Pin Correctly
       2. Rear DC COAX 15A. Need to jump to 3VCC for ESP32/ 5VCC for Arduino 5V
