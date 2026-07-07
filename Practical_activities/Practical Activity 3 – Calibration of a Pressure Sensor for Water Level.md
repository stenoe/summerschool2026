# Practical Activity 3 – Calibration of a Pressure Sensor for Water Level Monitoring in Lake Selgjärv and Forest Ditches

## Title

Calibration and Field Deployment of a Pressure Sensor for Water Level Monitoring

---

## Learning Objectives

By the end of this activity, participants will be able to:

* Understand the basic principle of water level measurement using pressure sensors.
* Calibrate a low-cost pressure sensor using known water column heights.
* Convert pressure measurements into water level data.
* Install a pressure sensor in a lake or forest ditch for continuous monitoring.
* Compare automatic sensor measurements with manual reference measurements.
* Discuss the role of water level monitoring in forest hydrology and ecosystem studies.

---

## Background

Water level is an important hydrological variable for understanding the interaction between lakes, drainage ditches, soils, and forest ecosystems. In forested catchments, small variations in water level can influence soil moisture, groundwater dynamics, carbon cycling, and vegetation processes.

Pressure sensors can be used to estimate water level because the pressure exerted by a water column increases with depth. After calibration, the measured pressure can be converted into water height using a linear relationship or the hydrostatic pressure equation:

[
h = \frac{P - P_{atm}}{\rho g}
]

where:

* (h) is the water level or water column height;
* (P) is the measured pressure;
* (P_{atm}) is atmospheric pressure, if an absolute pressure sensor is used;
* (\rho) is water density;
* (g) is gravitational acceleration.

In this practical activity, students will calibrate a pressure sensor and use it to monitor water level in Lake Selgjärv and/or in drainage ditches located within the forest.

---

# Experimental Setup

Each student group will work with:

* One pressure sensor for water level measurement.
* A data logger or microcontroller system.
* A power supply or battery.
* A ruler or measuring tape for manual reference measurements.
* A calibration tube or container with known water heights.
* Waterproof cables and connectors.
* A stilling well or protective perforated tube for field installation.
* A notebook or digital spreadsheet for recording calibration data.

The activity will be divided into two parts:

1. **Sensor calibration under controlled conditions.**
2. **Field deployment in Lake Selgjärv or forest ditches.**

---

# Part 1 – Sensor Calibration

## Calibration Procedure

Students will calibrate the pressure sensor by exposing it to known water column heights.

Recommended steps:

1. Connect the pressure sensor to the data logger or microcontroller.

2. Check if the sensor output is stable when exposed to air.

3. Place the sensor at the bottom of a calibration tube or container.

4. Add water gradually to create known water column heights.

5. Record the sensor output for each known water height.

6. Repeat measurements at several water levels, for example:

   * 0 cm
   * 10 cm
   * 20 cm
   * 30 cm
   * 40 cm
   * 50 cm

7. For each level, wait until the sensor reading stabilizes before recording the value.

8. Repeat the calibration sequence if time allows.

---

## Calibration Data Table

Students should record the following information:

| Step | Known water height, cm | Sensor pressure reading | Temperature, °C | Notes         |
| ---- | ---------------------: | ----------------------: | --------------: | ------------- |
| 1    |                      0 |                         |                 | Sensor in air |
| 2    |                     10 |                         |                 |               |
| 3    |                     20 |                         |                 |               |
| 4    |                     30 |                         |                 |               |
| 5    |                     40 |                         |                 |               |
| 6    |                     50 |                         |                 |               |

---

## Calibration Analysis

Participants will:

1. Plot sensor pressure reading versus known water height.
2. Fit a linear regression model:

[
h = aP + b
]

where:

* (h) is the water height;
* (P) is the pressure sensor reading;
* (a) is the calibration slope;
* (b) is the calibration offset.

3. Evaluate the calibration quality using:

* coefficient of determination, (R^2);
* bias;
* root mean square error, RMSE;
* residual plots.

4. Discuss possible sources of uncertainty, such as:

* sensor noise;
* unstable water level during calibration;
* temperature effects;
* sensor positioning;
* atmospheric pressure variation;
* cable or electronic noise.

---

# Part 2 – Field Deployment

## Field Site

The calibrated sensor will be installed in Lake Selgjärv and/or in forest drainage ditches. The purpose is to obtain continuous water level measurements and compare them with manual observations.

Possible installation locations:

* Lake Selgjärv shoreline.
* A forest ditch connected to local drainage pathways.
* A shallow ditch inside the forest.
* A reference point where manual water level measurements can be easily repeated.

---

## Installation Procedure

Students will:

1. Select a safe and accessible monitoring point.
2. Install a stilling well or protective perforated tube.
3. Place the pressure sensor inside the tube, below the expected minimum water level.
4. Fix the sensor position to avoid movement during the experiment.
5. Install the data logger above the water surface in a protected box.
6. Record the exact installation depth and reference elevation.
7. Measure the water level manually using a ruler or staff gauge.
8. Start automatic data acquisition.

Recommended sampling interval:

* Every 10–60 seconds during the practical activity.

Recommended monitoring duration:

* 60–120 minutes during the Summer School activity.
* Longer deployment is possible if the equipment remains installed.

---

# Measurements

The monitoring system will record:

* pressure sensor output;
* estimated water level;
* timestamp;
* water temperature, if available;
* manual reference water level measurements.

Manual measurements should be taken:

* at the beginning of the experiment;
* after sensor installation;
* during the monitoring period;
* at the end of the experiment.

---

# Data Processing

Students will process the field data using the calibration equation obtained in Part 1.

The main steps are:

1. Import the raw sensor data.
2. Apply the calibration equation.
3. Convert pressure readings into water level.
4. Correct for atmospheric pressure if required.
5. Compare automatic water level data with manual measurements.
6. Plot water level variation over time.
7. Identify short-term fluctuations or sensor drift.
8. Discuss whether the sensor is suitable for long-term monitoring.

---

# Expected Results

Students should obtain:

* A linear calibration curve relating pressure readings to water column height.
* A calibrated equation for converting sensor output into water level.
* A time series of water level in Lake Selgjärv or a forest ditch.
* A comparison between automatic sensor data and manual reference measurements.
* An estimate of sensor uncertainty.

In the lake, water level is expected to be relatively stable during short monitoring periods.

In forest ditches, water level may show stronger variability depending on local flow, drainage conditions, rainfall, and connectivity with the surrounding soil and groundwater system.

---

# Discussion Questions

* Why can pressure be used to estimate water level?
* What is the difference between absolute and gauge pressure sensors?
* Why is calibration necessary before field deployment?
* What are the main sources of error in water level measurements?
* How could atmospheric pressure influence the measurements?
* Why are drainage ditches important in forest hydrology?
* How can water level data help us understand soil moisture and forest ecosystem processes?
* What would be required for long-term autonomous monitoring?

---

# Skills Acquired

Participants will gain practical experience in:

* Hydrological monitoring.
* Sensor calibration.
* Low-cost environmental instrumentation.
* IoT-based data acquisition.
* Field installation of environmental sensors.
* Water level data processing.
* Time-series analysis.
* Evaluation of sensor uncertainty.
* Forest hydrology and lake–ditch interactions.

---

# Expected Outputs

At the end of the activity, each group will produce:

* A calibration dataset.
* A calibration curve.
* A calibrated equation for converting pressure into water level.
* A field water level time series.
* A comparison between manual and automatic measurements.
* A short presentation discussing sensor performance and hydrological interpretation.

---

## Summary

This practical activity introduces participants to water level monitoring using pressure sensors. Students will calibrate a sensor under controlled conditions, install it in Lake Selgjärv or forest drainage ditches, and process the data to obtain calibrated water level measurements. The activity connects sensor technology, IoT monitoring, and forest hydrology, providing hands-on experience with environmental data acquisition in field conditions.
