# CB-radio-Cybernet-platform-FM-demodulator-modulator
CB radio Cybernet platform FM demodulator modulator add-on module

I was involved in CB radio since the late 1970's, in the early 80's FM (Frequency Modulation) CB radios started to appear, i designed a FM demodulator and modulator board for the radio i had then (a Rystl).
I recently acquired an old CB from that period and did a redesign of the module.
It's targeted for Cybernet chassis as used in many models including my Super Panther.

Disclaimer: additional to the standard license, no commercial usage is allowed, otherwise feel free to use the design to build your own version. Provided as-is, no warranty or liability, use at your own risk. There is not really a risk voiding the warranty on your radio since this is intended for radios of the 70s and 80's. You might want to check if modifying the radio is within the legal bounds of your country's laws on CB radio. A decent level of knowledge on electronics and/or CB radios is assumed, do not attempt to build this if you do not have the proper skills. You can ask me for info but i can't provide details for use in other CB radios, I have no commercial interests, I do not sell kits.

Schematics and gerber files are provided.

The FM demodulator uses a classic TBA120S, obsolete but still available, my local electronics store had some on stock.
The coil used can be a red core (oscillator coil) like what i used or a yellow core (IF amplifier coil), basically a 455KHz coil is what you need.
The red coil does not have a parallel capacitor therefor C6 is required, can be omitted if you use a yellow coil. You might need to tweak C6 depending on the coverage.

The modulator part is basically a gating (or suppression) of the microphone signal after it passes through the modulation amplifier IC to the varicap on an oscillator crystal.
The level can be adjusted. Modulation is disabled in TX mode.
A 4 pole switch is used to switch between AM and FM modulation, a lot of the connection points for this are in the back of the radio hence the placement of the switch there.

Installation instructions are provided but only for a specific but common Cybernet chassis.
