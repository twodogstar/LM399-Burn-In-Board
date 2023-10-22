# LM399 Voltage Reference Burn-In Board

This project is a board designed for burning in multiple LM399 voltage references simultaneously. The LM399 is a precision multi-junction temperature-compensated zener diode, providing a stable 6.9V reference voltage with exceptional accuracy and low drift. This burn-in board is an essential tool for ensuring the stability and reliability of the LM399 voltage references before deploying them into their reference baords.


# Introduction

This project aims to facilitate the burn-in process of LM399 voltage references to ensure their optimal performance over extended periods. The board provides a controlled environment for simultaneously testing multiple LM399 units, allowing users to monitor and analyze their stability and performance metrics.

# Features

Accommodates multiple LM399 voltage references for simultaneous burn-in.
Real-time monitoring of voltage output for each LM399 unit is possible with SENSE traces that have no current flowing through them

# Requirements

To utilize this burn-in board effectively, you will need the following:

-LM399 voltage references (the board is currently designed to burn in ten references at a time).
-A stable power supply with low ripple and noise or a battery that can supply 15-18 volts..
-A 6 1/2 digit meter or better to monitor the drift of the references over time. Most 6 1/2 digit meters use an LM399 voltage reference themselves so you may see drift from the reference in your meter. It is possible to use an ultra low drift reference such as those based on the LTZ1000 or ADR1000 and then measure your LM399's against that reference with a 6 1/2 digit meter with greater precision.

To use the burn-in board for testing LM399 voltage references, follow these steps:

NEED TO ADD THINGS HERE


Contributions to this project are welcome. If you find any issues or have suggestions for improvement, please feel free to submit a pull request. For major changes, please open an issue first to discuss the proposed updates.

License

This project is licensed under the MIT License.

