**DC-AC Converter PCB:**
Power supply unit for the simple transformer model
It converts the DC voltage (9v) to AC voltage at 50Hz to drive the transformer's primary. 
It is stepped up at the secondary based on the turns ratio of the transformer.
ATtiny85 chip generates PWM signals to switch ON/OFF the MOSFETs (2 N-channel).
Switching of the MOSFETs creates square waveform, hence converting DC to AC signals.
Same schematic diagram with two variants of PCB i.e. SMD-version1 and PTH-version2.

