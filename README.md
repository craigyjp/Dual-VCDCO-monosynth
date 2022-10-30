# Dual-VCDCO-monosynth
- A monosynth based on the Hagiwo $9 VCO and the AS3372 Matrix 12 filter
Having purchased some Seeed XIAO RP2040 boards to build a polysynth and not using them, I decided to give the HAGIWO $9 VCO a try on its own.
Once I got it stable and nice sounding I decided it would make a good base for a dual oscillator monosynth and this was created.

I modified the Hagiwo code to add an FM/Pitchbend input seperate from the CV so when a CV of 0V or 5V are used the Pitchbend and FM still work with negative voltages. This meant I lost the MOD CV input, but I've mixed the MOD pot and CV together onto the MOD input.

I also added the modifications from clarionut on Look Mum No Computer to add the NeoPixel LED for the wave selection display and PWM for the square wave.

https://www.youtube.com/watch?v=fpNUdnT3NE0

- Specifications

- Dual Wavetable VCDCO with 24 waveforms, AM, FM, etc
- FM Modulation, wavetable modulation, LED wave indicator
- Octave Up, Down, Normal per DCO
- AS3372E pole mixing filter with 16 configurations
- Envelope inversion for filter
- Electric Druid LFO with 16 waveforms
- Electric Druid EnvGen8c envelopes for filter and amp.
- Electric Druid Noise 2 for Pink & White Noise
- Elkyam MIDI to CV converter for MIDI compatability
- Master Tune
- Pitchbend Range control
- MIDI and CV/gate control

# Contributors

- Elkyam MIDI to CV converter, slightly modified for different CV outputs and channel changes

https://github.com/elkayem/midi2cv

- Hagiwo $9 VCO

https://note.com/solder_state/n/nca6a1dec3921

https://www.youtube.com/watch?v=HBtc5oQffu8

- Clarionut for his mods to the VCO for LED display and PWM

https://lookmumnocomputer.discourse.group/t/hagiwo-9-raspberry-pi-vco-with-seeed-xiao-rp2040-eurorack-modular-synthesizer/5290


