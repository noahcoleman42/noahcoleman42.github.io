---
title: "Web-Controlled Thermostat"
excerpt: "Leverages cloud technology using a Raspberry Pi hosting a Flask web server to make heating your home more convenient"
collection: projects
---
This project was inspired by a wish to save money on natural gas bills. The web-controlled thermostat allows users to control their home's heating from anywhere they have an internet connection. With this freedom, users can lower the heat while away from home, reducing energy consumption and their bill.

Overview
-----
The device houses a Raspberry Pi running a web server. Trusted users can interface with the website to toggle the heating system in their home. When users turn on the heat, the device makes "calls for heat" to keep the temperature within a user-specified range. Turning off the heat lowers the ambient temperature to 50-55 &deg;F, a safe range to prevent pipes from freezing during the winter. The device uses a digital temperature sensor to measure the room's temperature, a relay to switch the thermostat wires to make calls for heat, and an LED that turns red for on and blue for off to provide additional feedback to users.

This project is comparable to Google's Nest Thermostat, but it is better for my application because, as a renter, I would rather have a cheaper portable solution. It also serves as a great learning experience.

Design Process
-----
* define project goals
* step through process
* explain circuit diagram & components & 24 volt two-wire thermostat
* explain web server & include image of webpage
* explain thermostat code

See my GitHub repository here.

Results
-----
* Rough quantitative analysis of improvements after installation.
It made heating my home more convenient.
