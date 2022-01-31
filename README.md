<h1 align="center">circuitexpress-ducky</h1>

<div align="center">
  <strong>Make a cheap but powerful USB Rubber Ducky with an Adafruit Circuit Playground Express</strong>
</div>
<h2>Forked from dbisu/pico-ducky</h2>

[Buy a Circuit Playground Express here](https://www.adafruit.com/product/3333)
<br />

<div align="center">
  <img alt="GitHub code size in bytes" src="https://img.shields.io/github/languages/code-size/cjplaysdev/circuitexpress-ducky">
  <img alt="GitHub license" src="https://img.shields.io/github/license/cjplaysdev/circuitexpress-ducky">
  <a href="https://github.com/dbisu/pico-ducky/graphs/contributors"><img alt="GitHub contributors" src="https://img.shields.io/github/contributors/cjplaysdev/circuitexpress-ducky"></a>
  <img alt="GitHub commit activity" src="https://img.shields.io/github/commit-activity/m/cjplaysdev/circuitexpress-ducky">
  <img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/cjplaysdev/circuitexpress-ducky">
</div>

<br />

## Install

Install and have your USB Rubber Ducky working in less than 5 minutes.

1. Download [CircuitPython for the Adafruit Circuit Playground Express](https://circuitpython.org/board/circuitplayground_express/). *Updated to 7.1.1

2. Plug the device into a USB port while holding the boot button. It will show up as a removable media device named `CPLAYBOOT`.

3. Copy the downloaded `.uf2` file to the root of the board (`CPLAYBOOT`). The device will reboot and after a second or so, it will reconnect as `CIRCUITPY`.

4. Download `adafruit-circuitpython-bundle-7.x-mpy-YYYYMMDD.zip` [here](https://github.com/adafruit/Adafruit_CircuitPython_Bundle/releases/latest) and extract it outside the device.

5. Navigate to `lib` in the recently extracted folder and copy `adafruit_hid` to the `lib` folder in your Circuit Playground.

6. Click [here](https://raw.githubusercontent.com/cjplaysdev/circuitexpress-ducky/main/duckyinpython.py), press CTRL + S and save the file as `code.py` in the root of the Circuit Playground, overwriting the previous file.

7. Find a script [here](https://github.com/hak5darren/USB-Rubber-Ducky/wiki/Payloads) or [create your own one using Ducky Script](https://github.com/hak5darren/USB-Rubber-Ducky/wiki/Duckyscript) and save it as `payload.dd` in the board.



### Setup mode

To edit the payload, enter setup mode by holding down Button A on the board when it is plugged in, this will stop the circuit playground from injecting the payload in your own machine.






## Useful links and resources

### Docs

[CircuitPython](https://circuitpython.readthedocs.io/en/6.3.x/README.html)

[CircuitPython HID](https://learn.adafruit.com/circuitpython-essentials/circuitpython-hid-keyboard-and-mouse)

[Ducky Script](https://github.com/hak5darren/USB-Rubber-Ducky/wiki/Duckyscript)


