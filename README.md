# dc_dc_controller
A logic controlled DC-DC step up converter PCB

Have you needed to power a small sensor with 12 or 24V but only had 3.3V or 5V available?
Maybe you need to really reduce your power consumption and running the sensor all the time will consume too much power?
Then this simple logic-controller DC-DC step-up converter might be useful for you!

The step-up converter is an off-the-shelf DC-DC converter board using the MT3608. This can take an input voltage of 2-24V DC and supply an output voltage up to 28V DC. Up to 2A can be supplied (but not recommended for any length of time).

While this converter is useful, what if you only want to check your sensor every 10 mins or hour? Keeping the sensor powered up with a DC-DC converter will just waste energy, which might be in short supply from a battery-based system. So, we added a MOSFET based logic-controlled switch. You apply 3.3V - 5V to the control input and it will switch on the DC-DC converter. Your device can wake up, check your sensor, then go back to sleep and save lots of energy.

We have used this circuit for a weather monitoring station.

This is a reasonably simple kit which requires a small amount of soldering.
It should take under 1 hour to build.
Not suitable for under 12 years old.

