## Building a virtual synthesizer with Puredata

---
## Building a virtual synthesizer with Puredata
### Oscillators
* fm : basic FM generator
* oscy

---
## Building a virtual synthesizer with Puredata
### Filters
* filter : vcf
* adsr : simple ASDR control
* distort : Distort input signal
* lowpass : low pass (lop x2)

---
## Building a virtual synthesizer with Puredata
### Envelope generators and control
* vibrato : 1-20 Hz vibrato
* pitch_ctl
* porta : Portamento


---

## Building a virtual synthesizer with Puredata
### Volume control
* crossfader
* vol : can be piped to other modules
* master_vol : has dac~ output

---

## Building a virtual synthesizer with Puredata
### Sequencers
* beat_seq : Basic beat machine
* counter : count to specified number beginning with 0. Essential when working with sequencers
* metronome : send bang on specified bpm. Also ouputs multipliers greater control on sequencers

---

## Building a virtual synthesizer with Puredata
### Misc

* Octave transpose
* Oscilloscope


---


A patch example 

![My sample patch image](patch_example.PNG)




