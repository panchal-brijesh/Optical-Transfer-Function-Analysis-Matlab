# Project - Measuring the Transfer Function of a Camera and Its Lens

## 📌 Project Overview
This project investigates the **optical performance** of a camera system by analyzing the **Transfer Function** of both the camera and its lens. Through theoretical exploration, simulation, and experimental evaluation, we aim to understand the behavior of **Optical Transfer Function (OTF)**, **Modulation Transfer Function (MTF)**, and **Spatial Frequency Response (SFR)** in real imaging conditions.

---

## Project Metadata

- **Matriculation Number:** 221607  
- **Course:** Master of Mechatronics and Robotics  
- **Semester:** Sommersemester 2024  
- **Subject:** Optical Sensor

---

## 🎯 Objectives
- Measure and analyze the **Transfer Function** of a camera system.
- Simulate lens behavior for various field angles.
- Evaluate the impact of pixel size on system performance.
- Extract experimental SFR using BMP image analysis.

---

## 📚 Theoretical Background

### 1. Optical Transfer Function (OTF)
- Describes how spatial frequencies are handled by an optical system.
- Includes phase and magnitude components.

### 2. Modulation Transfer Function (MTF)
- Measures contrast reduction for different spatial frequencies.
- Derived from the magnitude of the OTF.

### 3. Spatial Frequency Response (SFR)
- Describes system response to edge features.
- Important for evaluating imaging sharpness.

## 🧪 Experimental Setup
- Test chart: **USAF resolution target**
- Camera with known sensor characteristics
- Evaluation via **MATLAB**

---

## 🛠️ Simulation Tasks

### 📌 Projection Lens
- Evaluate OTF profiles at **0° and 20° field angles**.
- Calculate the **System Transfer Function** for a **4.65 μm pixel size**.
- Identify the spatial frequency corresponding to **50% contrast** in OTF.

## 🔍 Evaluation

### 🔹 Magnification Analysis
- BMP images are used to estimate system magnification.

### 🔹 e-SFR (Edge Spatial Frequency Response)
- Computed from captured edge images.
- Compared with simulation results.

---

## 📁 Project Files Overview

| File Name | Description |
|----------|-------------|
| `e-SFR.mlx` | Computes and evaluates the edge-based Spatial Frequency Response (eSFR). |
| `esfr_measurement_and_simulation_with_microscope.mlx` | Performs eSFR measurement and simulation using a microscope. |
| `esfr_measurement_and_simulation_without_microscope.mlx` | Performs eSFR measurement and simulation without using a microscope. |
| `Evaluate the profile of the system transfer function for a pixel size of 4,65 μm.mlx` | Simulates the system transfer function considering the sensor’s pixel size. |
| `Evaluate the profile of the system transfer function for field angle 0°.mlx` | Calculates the system transfer function at 0° field angle. |
| `Evaluate the profile of the system transfer function for field angle 20°.mlx` | Calculates the system transfer function at 20° field angle. |
| `Evaluate the profiles of the OTF for field angle 0°.mlx` | Analyzes the Optical Transfer Function (OTF) at 0° field angle. |
| `Evaluate the profiles of the OTF for field angle 20°.mlx` | Analyzes the OTF at 20° field angle. |
| `Evaluate the profiles of the OTF for field angles 0° and 20°.mlx` | Compares OTF profiles at 0° and 20° field angles. |
| `Evaluation of the eSFR.mlx` | Final evaluation and visualization of the computed eSFR results. |

---

## Summary
This project combines theoretical modeling and practical image analysis to assess the spatial resolution of optical systems. The results confirm the dependency of image sharpness on both lens characteristics and sensor resolution. A careful selection of pixel size and lens configuration is essential to optimize image quality in real-world optical systems.

---

## Tools Used
- **MATLAB** (for simulations, image processing, and plotting)
- **BMP test images** for real-world evaluation
- **USAF resolution chart** for system evaluation

---

## 📌 Note
This project is part of academic coursework at Heilbronn University and aims to apply digital image processing and optical theory to real measurement scenarios.
