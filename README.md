
## What is it?
"Arduino GUI lamp" is a Python GUI created with QT Designer and programmed with arduino.

## How to use?
Download a "arduino_to_py" file and upload it on Your arduino,then download "rgb2",and "gui" files in Python extension. Launch "gui" file

## Program is not working!
in notepad open "gui.py" file and check line 12,there are port where your arduino connected and bitraid,you also can see it in code.
```python
arduinoSerial = serial.Serial('COM4',9600) #instead of COM 4 you must write your port
