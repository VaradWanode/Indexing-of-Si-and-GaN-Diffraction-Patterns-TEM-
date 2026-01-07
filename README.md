# Indexing-of-Si-and-GaN-Diffraction-Patterns-TEM-
Python-based tool for indexing Si and GaN TEM diffraction patterns using experimentally measured spot distances and angles, developed during a summer research internship at IIT Bombay.
Indexing of Si and GaN Diffraction Patterns using TEM

Perfect — below is a **detailed, well-structured, research-grade README** that still remains **clear, honest, and technically strong**.
This is **ideal for GitHub, professors, and recruiters** reviewing serious research work.

You can copy-paste this directly as `README.md`.

---

# Indexing of Si and GaN Diffraction Patterns using TEM

## Overview

This repository contains a **Python-based diffraction pattern indexing tool** developed during my **Summer Research Internship at IIT Bombay**.
The code is designed to index **Selected Area Electron Diffraction (SAED) / nanobeam diffraction patterns** of **Silicon (Si)** and **Gallium Nitride (GaN)** obtained using **Transmission Electron Microscopy (TEM)**.

The primary objective of this tool is to assist in identifying the **crystallographic planes and zone axes** corresponding to experimentally observed diffraction spots, along with an **error estimate** for each possible indexing solution.

---

## Research Background

Diffraction pattern indexing is a critical step in:

* Determining crystal orientation
* Identifying phase and structure
* Studying defects such as dislocations, stacking faults, and strain fields

Manual indexing of diffraction patterns is **time-consuming and prone to error**, especially for nanostructures such as **GaN and InGaN nanowires**.
This script was developed to provide a **systematic and reproducible approach** to diffraction pattern indexing using experimentally measurable parameters.

---

## Project Context

This work was carried out as part of the research project:

**“Characterization of defects in GaN and InGaN nanowires using Transmission Electron Microscopy (TEM)”**

The project involved analyzing diffraction patterns to understand:

* Crystallographic orientation of nanowires
* Presence and nature of crystallographic defects
* Structural differences between GaN and InGaN regions

---

## Methodology

The indexing approach implemented in this code is based on the following experimentally measurable inputs:

### 1. Inter-Spot Distance

* Distance between diffraction spots measured from the diffraction pattern
* Extracted using image analysis software such as **ImageJ**

### 2. Angle Between Diffraction Spots

* Angular separation between selected diffraction spots
* Measured directly from the diffraction image

### 3. Material-Specific Crystallographic Parameters

* Lattice parameters corresponding to **Si** or **GaN**
* Appropriate crystallographic relationships incorporated into the model

---

## Core Idea

The script uses **custom-curated mathematical relations** (developed in consultation with my research mentor) that relate:

* Reciprocal lattice geometry
* Interplanar spacings
* Angular relationships between diffraction spots

Using these relations, the code:

1. Generates **possible crystallographic plane combinations**
2. Compares theoretical values with experimental inputs
3. Calculates **error metrics**
4. Outputs **probable indexing solutions ranked by accuracy**

---

## Features

* Indexing of **Si and GaN diffraction patterns**
* Uses **experimentally measurable inputs** (distance & angle)
* Outputs **possible (h k l) plane indices**
* Provides **error estimation** for each solution
* Reduces manual effort and subjectivity in diffraction analysis
* Suitable for **nanobeam diffraction and SAED patterns**

---

## Input Requirements

The user must provide:

* Measured distance between diffraction spots
* Angle between diffraction spots
* Material system (Si or GaN)

These values can be obtained using tools such as:

* ImageJ
* DigitalMicrograph
* Other TEM image analysis software

---

## Output

The script outputs:

* Possible crystallographic plane indices `(h k l)`
* Corresponding theoretical vs experimental match
* Error associated with each indexing solution

This allows the user to:

* Identify the **most probable indexing**
* Quantify confidence in the indexing result

---

## Applications

* Crystallographic analysis of **semiconductors**
* Defect characterization in **GaN / InGaN nanowires**
* Orientation determination in TEM studies
* Academic research and materials characterization workflows

---

## Tools & Technologies

* Python
* NumPy
* Scientific computing libraries
* TEM diffraction analysis concepts

---

## Acknowledgements

This work was carried out during my **Summer Research Internship at IIT Bombay** under the guidance of my research mentor.
The indexing relations and methodology were developed collaboratively to ensure physically accurate and experimentally relevant results.

---


