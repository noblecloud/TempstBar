# TempestBar
A very simple proof of concept for displaying UDP data on a desktop using Python3 and PySide6/Qt.  Will hopefully live in the system tray/menu bar.

## Requirements
 - [Python 3.9](https://www.python.org/downloads/)
 - [PySide6](https://pypi.org/project/PySide6/)
 - [WeatherUnits](https://pypi.org/project/WeatherUnits/)
 - [websockets](https://pypi.org/project/websockets/)
 - [pytz](https://pypi.org/project/pytz/)
 - WeatherFlow Station (only tested with [Tempest](https://weatherflow.com/tempest-weather-system/))

## Usage
Install PySide6 with

	pip install PySide6

Run with

	python main.py

## TODO
- [x] Display incoming UDP data
- [x] Add support for websocket subscription
- [ ] Implement minimize to tray/status bar usage to display temperature or selected measurement
- [ ] Add derived measurements (Already added some)
- [ ] GUI configuration editor
- [x] Auto hide irrelevant sections
- [ ] Add display of UDP datagram history
- [ ] Plot data over time
- [ ] Add support for multiple devices and hubs
- [ ] BLE Subscription?
