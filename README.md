# BSat_TNC
TNC for Balloonsat suite
For use with W8LID's Feather HamWing Board and an Adafruit BLE Feather.
Has several purposes:

## APRS Transmitter

Uses Handiko's APRS Script and 4-pin digital GPS to transmit moving HAB GPS data with elevation.

## nRF24L01 Receiver

Receives 2.4 GHz GFSK ASCII strings via an nRF24L01. Parses the fields into telemetry APRS fields. Works with the following software currently:
1. BSat Data Logger
2. BSat Release

## Bluetooth Transmitter

The (Adafruit Bluetooth Feather)[https://www.adafruit.com/product/2829] transmits data to the Bluefruit App. It wil relay all telemetry fields and statuses to a phone prior to takeoff.
