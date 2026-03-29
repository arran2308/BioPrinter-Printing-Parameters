# BioPrinter Printing Parameters

A framework for developing and validating extrusion-based bioprinting parameters.

---

## Overview

The BioPrinter operates using extrusion of viscous hydrogels rather than conventional thermoplastic filament. As a result, print performance is hyper sensitive to printing parameters such as flow rate, pressure advance and speed.

This repository provides a platform for developing, documenting and refining these parameters in a structured manner.

---

## Purpose

This repository is intended to:

- Define and standardise printing parameters for the BioPrinter  
- Enable benchmarking and comparative testing  
- Document the evolution of process parameters over time  

By separating printing parameters from firmware configuration, this approach ensures clear traceability between **machine behaviour, process settings, and experimental outcomes**.

---

## Profile Philosophy

Profiles in this repository are treated as **controlled experimental configurations**, rather than static presets.

Each profile is expected to:
- have a clearly defined purpose  
- document key parameter changes  
- justify why those changes were introduced  
- describe expected or observed effects on print behaviour  

This enables a systematic approach to process development and validation.

---

## Materials

The BioPrinter is designed to operate with a range of extrusion materials, including:

- hydrogel-based systems (e.g. alginate)  
- proxy materials (e.g. hand cream for controlled testing)  

Material properties have a significant influence on:
- extrusion consistency  
- feature resolution  
- structural stability
  
---

## Related Repositories

- CAD Repository: https://github.com/arran2308/BioPrinter-CAD  
- Firmware Configuration: https://github.com/arran2308/BioPrinter-Firmware  

---

## Status

This repository is currently in an **active development stage**.

Profiles and documentation will continue to evolve as:
- new materials are introduced  
- extrusion behaviour is further characterised and refined 
- benchmarking studies are completed  

---

## Disclaimer

These profiles are developed for a custom syringe-based extrusion system.

---

## Author
Arran Arthur
Developed as part of the BioPrinter project.
