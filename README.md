# README - Tilt Pi Monitor Stack Docker Guide

## Overview
This guide provides step-by-step instructions for setting up a monitoring stack with Docker to extract data from a Tilt Hydrometer and display it in Grafana. It covers using InfluxDB, Telegraf, and Docker Compose to create a complete data monitoring and visualization pipeline.

---

## Getting Started

### Prerequisites
- A functioning Tilt Hydrometer.
- A Raspberry Pi

### Installation Steps

Simply follow the instructions in the file called `tilt-pi-monitor-stack-docker-guide.md`

The `docker-compse.yaml`, configuration file for telegraf and `.env` file are in this repository, although you can copy and paste from the guide.md 

---


## Issues and Support
If you encounter issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

---

##Plans for the Future

I would like to dockerize the Node-RED aspect of the Tilt Pi
I would like to dockerize the aioblescan to allow capturing data directly from the Tilt Hydrometer

---

## License

### Creative Commons Attribution 4.0 International (CC BY 4.0)

Copyright (c) 2024 Stian Jøsok

You are free to:

- **Share**: Copy and redistribute the material in any medium or format.
- **Adapt**: Remix, transform, and build upon the material for any purpose, even commercially.

Under the following terms:

- **Attribution**: You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.

- **No additional restrictions**: You may not apply legal terms or technological measures that legally restrict others from doing anything the license permits.

[Read the full license here](https://creativecommons.org/licenses/by/4.0/).

---

By contributing to this project, you agree that your contributions will be licensed under the same Creative Commons license.

---

## Acknowledgments

I would like to thank Baron Brew, the creators of the Tilt Hydrometer, for creating such a cool product and for the support they’ve offered throughout this project. Their customer service and community-focused approach is great. They have helped me with some details and been quick to respond. Their engagement has fueled me to make my own setup better and given me the opportunity to give back to the community of homebrewers and homelabbers.

[Learn more about their products](https://tilthydrometer.com).


