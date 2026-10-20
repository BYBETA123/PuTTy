# PuTTy in python

This project is an attempt to implement the PuTTy terminal in python with a few extra quality of life upgrades

## Features
- serial port connections

## Requirements
- This has been tested and works on both Windows and Linux, MAC is untested

## Run
- Navigate to the python file directory and type `python PuTTy.py`
- Enter the port number of the intended device
- Enter the baud rate of the intended device
- Cliick enter and begin communicating with the connected device through serial commands

## Future Endeavours
- Fix the inability to reconnect after losing connection: This would greatly help users who frequently need to connect and disconnect the same device multiple times in quick succession.
- Improve usability, Copying and pasting does not currently work with the terminal (Ctrl + C being an obvious outlier) but pasting commands and from the clipboard would vastly improve the usability especially considering long commands or strings which have no particular order
- Other features can be requested
