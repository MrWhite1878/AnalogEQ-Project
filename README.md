# AnalogEQ-Project
This repo serves to document relevant information on the design of an analog audio equalizer, whose goal is to serve as a learning tool and correctional component for my desktop speakers.
<!-- Photo -->
> WARNING: This project is a work in progress.
> Nothing is finalized, and this repo mainly serves to document and catalog my journey.

### Target Specifications
*	RCA audio input/output (adapters included)
*	9VAC Wall Wart power input
* ±18VDC rails powering NE5532 and TL072 op amps
* Smooth knobs for all controls
* High input impedance and low output impedance
* Audio bypass switch
* Input and Output Amplification
* 3rd order butterworth BPF for frequencies outside 20Hz-20kHz
* Sharp (Q = 10) -15dB Notch filter with adjustable target frequency (35-85Hz)
* LF and HF shelving with adjustable gain (±16dB) and proportional break/corner frequency
* 2 fully parametric middle controls: ±15dB gain, 70Hz-1.5kHz range 1 and 700-15kHz range 2, 0.5 < Q < 5
* Diagnostic board LEDs and testing pads