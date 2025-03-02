Software part for UART BMS (JBD, JK) to addressable RS485 Modbus protocol.

## Overview
Common JK or JBD BMS often offers RS485 port, which is just a different physical layer for proprietary protocol running on UART port, not a [Modbus](https://en.wikipedia.org/wiki/Modbus). Because of this, you can't simply connect multiple BMSes to a real addressable RS485 network.

## Hardware
Isolated adapter running ESP32-C3, with isolated power supply and galvanic UART isolation (ADUM1201). **ET69C02** RS485-ethernet gateway is used for a testing.

![HW](https://github.com/taHC81/BMS_to_MODBUS/blob/main/BMS-Modbus-adapater-HW.jpg?raw=true)
