# README - Tilt Pi Monitor Stack Docker Guide

## Overview
This guide explains how to set up a monitoring stack using Docker, InfluxDB, Telegraf, and Grafana to track data from a Tilt Hydrometer. It provides step-by-step instructions for creating a complete data monitoring and visualization pipeline.

---

## Getting Started

### Prerequisites
- A functioning Tilt Hydrometer.
- A Raspberry Pi

### Installation Steps

Follow the instructions in **[tilt-pi-monitor-stack-docker-guide.md](./tilt-pi-monitor-stack-docker-guide.md)** to set up your monitoring stack. The required files, including `docker-compose.yaml`, the Telegraf configuration file, and `.env`, are provided for convenience. You can also copy and paste directly from the guide if preferred.

---

## Issues and Support
If you encounter issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

---

## Future Plans
- Dockerize the Node-RED aspect of the Tilt Pi for simplified deployment.
- Dockerize `aioblescan` to allow direct data capture from the Tilt Hydrometer as a light weight alterntive to Node-Red

---

## Acknowledgments

I would like to thank **Baron Brew Equipment**, the creators of the **Tilt Hydrometer**, for creating such a great product and for the support they’ve offered throughout this project. Their customer service and community-focused approach has been great. They have helped me with some details and been quick to respond. Their engagement has fueled me to make my own setup better and given me the opportunity to give back to the community of homebrewers and homelabbers.

[Learn more about their products](https://tilthydrometer.com).


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

By contributing to this project, you agree that your contributions will be licensed under the same license.

