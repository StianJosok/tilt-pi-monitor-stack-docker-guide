# README - Tilt Pi Monitor Stack Docker Guide

## Overview
This guide explains how to set up a monitoring stack using Docker, InfluxDB, Telegraf, and Grafana to track data from a Tilt Hydrometer. It provides step-by-step instructions for creating a complete data monitoring and visualization pipeline.

[Step-by-Step Guide for Setting Up Tilt Pi Monitoring](tilt-pi-monitor-stack-docker-guide.md)


![Example Dashboard](/blog-post-images/img_8.png)

---

## Prerequisites
- A Raspberry Pi running a **64-bit OS** (I have tested with 3b+ but not lower spec)
- A functioning Tilt Hydrometer with a functioning UI
    - [Install Tilt Pi on Raspbian Bookworm](https://tilthydrometer.com/blogs/news/install-tilt-pi-on-raspbian-buster-compatible-with-all-rpi-models-including-rpi-4) (for a clean or existing Raspberry Pi installation).
    - [Set Up Tilt Pi (Pre-installed Image)](https://tilthydrometer.com/blogs/news/how-to-set-up-tilt-pi-part-1) (for using a pre-installed image).
    - [Using RPi Imager](https://www.youtube.com/watch?v=9xwI5jm2fsY)
    - [How to Set Up Your Tilt Pi app (for Raspberry Pi)](https://www.youtube.com/watch?v=lapJqK-IeiA)

---

## Acknowledgments

I would like to thank [the creators](https://tilthydrometer.com/pages/about-us) of the **Tilt Hydrometer** for creating such a great product and for the support they’ve offered throughout this project. Their customer service and community-focused approach has been great. They have helped me with some details and been quick to respond. Their engagement has fueled me to make my own setup better and given me the opportunity to give back to the community of homebrewers and homelabbers.

[Learn more about their products](https://tilthydrometer.com).

---

## Plans for the Future

- Dockerize the Node-RED aspect of the Tilt Pi.
- Dockerize the aioblescan to allow capturing data directly from the Tilt Hydrometer.

---

## Issues and Support
If you encounter issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

---
## License

This project is licensed under the [Creative Commons Attribution-ShareAlike 4.0 International License](LICENSE.md).


[Read the full license here](https://creativecommons.org/licenses/by-sa/4.0/).

---

By contributing to this project, you agree that your contributions will be licensed under the same license.

