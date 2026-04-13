# Field-Following Robot

UBC ELEC 291 Project 2 — a two-microcontroller autonomous robot that follows a magnetic guide wire, executes pre-programmed paths through intersections, and is controlled over an infrared link by a custom handheld remote. The robot runs on an STM32L051 (ARM) using tuned inductors for field sensing and a VL53L0X time-of-flight sensor for obstacle detection; the remote runs on an EFM8LB1 (8051) and transmits ASCII commands over a 38 kHz IR carrier.

All firmware is written in C. The robot follows three pre-programmed paths through a figure-8 guide-wire course, detects intersections through spike detection on a center inductor, and stops automatically when an obstacle is detected within 100 mm.

## Demo

📺 **[Video demonstration — coming soon]**

## Team

Group project completed with **James Kerr, Retter Ma, Helia Ahmadzadeh, Chloe Lam, and Jaskaran Singh**.

## Acknowledgements

Completed as Project 2 for **ELEC 291/292** at the University of British Columbia, taught by **Dr. Jesús Calviño-Fraga**. The project specification, CV-8052 materials, VL53L0X reference code, and supporting course materials are his work (© 2006–2026) and all rights remain with Dr. Calviño-Fraga and UBC.
