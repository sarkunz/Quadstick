# QMP-4

## Quadstick Desktop Application

## Setup instructions

After installing Vocola python runtime libraries (wxpython, etc)... (? just installing python?)

Install the following pip packages by running

`pip install requirements.txt`

or

`pip install wxPython pyinstall pyserial pywinusb openpyxl rfc6266 pyrfc6266 vgamepad`

### To run:

`cd src`

`python Quadstick.py `

(TODO change this to main.py and move outside of src)

## To build a release

run `pyinstall QuadStick.spec`
The generated exe will be in dist folder
