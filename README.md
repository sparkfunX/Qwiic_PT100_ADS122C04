# Qwiic PT100 ADS122C04

The Qwiic PT100 is based on the TI ADS122C04 and allows you to measure temperature accurately from
100 Ohm Platinum Resistance Thermometers using 2, 3 or 4-wire connections

![Qwiic_Instrument_ADC_-_PT100-01.jpg](https://cdn.sparkfun.com//assets/parts/1/5/6/6/2/16770-Qwiic_Instrument_ADC_-_PT100-01.jpg)

[Qwiic PT100 - ADS122C04 (SPX-16770)](https://www.sparkfun.com/products/16770)

The ADS122C04 is a precision 24-bit delta-sigma analog to digital converter. It can measure voltage very
accurately through two differential or four single-ended inputs. It has a flexible input multiplexer,
a low-noise programmable gain amplifier, two programmable current sources, a voltage reference
and an in-built precision temperature sensor. In summary, it contains everything you need to measure
temperature accurately from remote sensors.

The Qwiic PT100 is dedicated to reading the temperature of 100 Ohm Platinum Resistance Thermometers
using 2, 3 or 4-wire connections. Using a 3 or 4-wire connection allows the ADS122C04 to automatically
compensate for the cable resistance. The differential input provides noise rejection for industrial
applications.

The ADS122C04 features a 2-wire I2C-compatible interface. The chip address can be changed by
reconfiguring the two jumpers A0 and A1. Please see the schematic for further details.

## Repository Contents
- **/Hardware** - Eagle schematic and PCB design files
- **/Documents** - contains the TI datasheet and application reports
- **LICENSE.md** contains the licence information

## Library

- **[Arduino Library](https://github.com/sparkfun/SparkFun_ADS122C04_ADC_Arduino_Library)** - Library to support the ADS122C04

## Probe Disconnection

If you need to test if the PT100 probe has been connected correctly to the ADS122C04, you may find [this discussion](https://forum.sparkfun.com/viewtopic.php?p=231735#p231735) useful.
