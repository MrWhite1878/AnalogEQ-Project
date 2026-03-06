# AnalogEQ-Project
This repo serves to document relevant information on the design of an analog audio equalizer, whose goal is to serve as a learning tool and correctional component for my desktop speakers.
<!-- Photo -->
> WARNING: This project is a work in progress.
> Nothing is finalized, and this repo mainly serves to document and catalog my journey.

### Target Specifications
*	3.5mm TS audio input and output
*	±15V DC input
*	Rotary switches for frequency adjustments, potentiometers for gain and Q
*	2nd-order Butterworth HPF with adjustable cutoff (approx. 20Hz-120Hz)
*	4th-order Butterworth LPF with fixed cutoff (approx. 20kHz)
*	LF shelving with adjustable corner (approx. 35Hz-220Hz) and adjustable gain (approx. ±8dB)
*	HF shelving with adjustable corner (approx. 8kHz-10kHz) and adjustable gain (approx. ±8dB)
*	Low-mid peaking filter with adjustable center frequency (approx. 100Hz – 1kHz), adjustable Q (approx. 0.5 – 5), and adjustable gain (approx. ±8dB)
*	High-mid peaking filter with adjustable center frequency (approx. 1kHz – 10kHz), adjustable Q (approx. 0.5 – 5), and adjustable gain (approx. ±8dB)
*	Audio pass switch



---

### Repo Table of Contents
* [PCB Files](./pcb) - KiCad schematics and layouts
* [Simulation Files](./sim) - LTspice simulation files
* [Manufacturing Files](./fab) - Gerber/Drill files and BOM
* [Hardware Design](./doc) - Block diagrams, filter designs, and layout choices
* [Hardware Verification and Results](./sim) - Testing methodology, measurements, and datasheet
* [Assembly and Use](./assembly) - How to create and use this at home

### A Brief Project Timeline
* Preliminary research on project ideas
* Decision to pursue equilizer
* Learning frequency-domain circuit analysis
* Filter topolgy exploration
* Repo Creation
