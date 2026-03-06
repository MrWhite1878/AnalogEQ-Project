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

### File Table of Contents
**Source Files**
* [PCB Files] - KiCad schematics and layouts
* [Simulation Files] - LTspice simulation files
**Manufacturing Package**
* [Gerber & Drill Files] - Or equivalent manufacturing files
* [Bill of Materials] - List of specific components and costs
**Engineering & Design Documentation**
* [Hardware Design] - Block diagrams, filter designs, and layout choices
**Validation & Specifications**
* [Hardware Verification and Results] - Testing methodology and measurements
* [Datasheet] - User-friendly format of test result
**Assembly & Use**
* [Assembly Guide] - How to recreate at home
* [User Manual] - How to operate it

# A Brief Project Timeline
- Preliminary research on project ideas
- Decision to pursue equilizer
- Learning frequency-domain circuit analysis
- Filter topolgy exploration
- Repo Creation
