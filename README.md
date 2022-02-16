
## What is it?
"Arduino GUI lamp" is a Python GUI created with QT Designer and programmed with arduino.

## How to use?
Download a "arduino_to_py" file and upload it on Your Arduino, then download "rgb2",and "gui" files in Python extension. Launch "gui" file

## Program is not working!
in notepad open "gui.py" file and check line 12,there are port where your arduino connected and bitraid,you also can see it in code.
```python
arduinoSerial = serial.Serial('COM4',9600) #instead of COM 4 you must write your port

```
## How to check? I can't open file in notepad!
video

## Screenshot of programm
<img src="https://raw.githubusercontent.com/Gafigaf/Images/master/SCREEN.png"></img>
<img src = "https://github.com/Gafigaf/Images/blob/master/gif.gif?raw=true"></img>

## Что это?
"Arduino GUI lamp" - это программа написаная на Python,графичиский интерфейс сделан с помощью QT Designer.

## Как использовать? 
Скачайте файл «arduino_to_py» и загрузите его на свой Arduino, затем загрузите файлы «rgb2» и «gui» в расширении Python. Запустите файл "gui".
