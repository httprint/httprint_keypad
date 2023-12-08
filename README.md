# HTTPrint_keypad

A very simple script to pull files from HTTPrint and send them to printer

Can run on cheap hardware like Raspberry Pi 1 B+

## Requirements

* CUPS
* Python3

* LCD Display HD44780 16x2 with is2 interface
* 4x4 Keypad
* Speakers

## Install

![Console](/console.png)

Connect LCD display using i2c (you should enable it using on raspi-config)

Connect keypad to GPIO

Connect speaker

Install cups and python on raspberry py

Connect a printer, configure cups and set the printer as default

Clone this repo

Copy keypad.conf.sample to keypad.conf and change settings (pay attentention to i2c port and address)

To have sounds, copy all [files](https://cloud.cristo.re/s/jfRFeHYKM3pcLPi) into "sounds" folder and install mpg123

Run keypad.py, or create a service to run it at startup



# License and copyright

Copyright 2023 itec <itec@ventuordici.org>, Davide Alberani <da@mimante.net>

Forked from: https://github.com/alberanid/httprint


Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

Printer icon created by Good Ware - Flaticon
