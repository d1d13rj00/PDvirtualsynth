## Building a virtual synthesizer with Puredata

---

### Oscillators
* fm : basic FM generator
* oscy

---

### Filters
* filter : vcf
* adsr : simple ASDR control
* distort : Distort input signal
* lowpass : low pass (lop x2)

---

### Envelope generators and control
* vibrato : 1-20 Hz vibrato
* pitch_ctl
* porta : Portamento


---


### Volume control
* crossfader
* vol : can be piped to other modules
* master_vol : has dac~ output

---


### Sequencers
* beat_seq : Basic beat machine
* counter : count to specified number beginning with 0. Essential when working with sequencers
* metronome : send bang on specified bpm. Also ouputs multipliers greater control on sequencers

---


### Misc

* Octave transpose
* Oscilloscope


---


A patch example 

![My sample patch image](patch_example.PNG)




