# KLH-FED-2026-Section-14-Batch-2
Design and simulation of an automatic street light control system using combinational logic with LDR, motion detection, and manual override control.
# Design and Simulation of an Automatic Street Light Control System Using Combinational Logic

## Project Overview

This project presents the design and simulation of an Automatic Street Light Control System using combinational logic. The system uses daylight detection, motion detection, and an override switch to automatically control the street light.

## Objective

To design and simulate a combinational logic circuit using basic digital logic gates such as AND, OR, and NOT gates for automated street light control.

## Inputs

- **D — Daylight Sensor (LDR)**
  - 0 = Night
  - 1 = Day

- **M — Motion Sensor**
  - 0 = No motion
  - 1 = Motion detected

- **O — Override Switch**
  - 0 = Normal operation
  - 1 = Manual override

## Logic Function

The street light output is defined by:

**L = O + (¬D · M)**

The light turns ON when:
- The override switch is active, OR
- It is nighttime and motion is detected.

## Logic Gates Used

- NOT Gate
- AND Gate
- OR Gate

## Simulation

The circuit is designed and simulated as a combinational logic system. The simulation verifies the output for all possible input combinations.

## Project Documentation

The complete project presentation and documentation are available in the PDF included in this repository.

## Team Details

**Section:** 14  
**Batch:** 2
