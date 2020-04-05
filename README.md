# mb'Lifter 

![pcb image](IMG_3603.png "Logo Title Text 1")
![pcb image](IMG_0307.png "Logo Title Text 1")

## What is it

It's a amplifier and attenuator, both coupled and controlled by one knob.

Input -> Amplify -> Attenuate -> Output

or

Input -> Attenuate -> Amplify -> Output.

the middle connection (gained or attenuated signal) can be routed anywhere.

Gain range: -18...+18 dB

It has 2 channels doing this.

Clip indicator - lights up when one of the channels opamps runs into clipping, that is signal level above +-10V peak to peak.

Other features Reverse voltage protection, requires +-12V and needs +-25mA.

### But Why ?

Original idea was to drive an overdrive/distortion unit, so it gains the signal, passes it to the distortion stuff, and then it attenuates to the original levels. In this way the distorted signal does not get louder only distorteder.

### Usecases

* Drive signal into distortion.

### Misuseable as

* InOut - Input an Aux signal (gain Line level to Rack level) AND Output Rack signals with Line level.
* Effect Adapter - Use Guitar effects in your rack - Attenuate to FX(line) level -> FX -> Gain back into Rack Level. Or other way around - use your rack as guitar FX unit.
* Instrument interface - cascade both channels to achive max gain of 36dB, sufficient for Mics and Guitars.
* ...


## Files in repo...

### /pcb

* Lifter01 is the beta version, left here as reference. Had a view minor bugs.
  * Missing feedback caps.
  * 2 wrongly flipped opamp gates.
* Lifter02 - current production version, labeled as "version1.0"
* FrontPCB - as name says.
