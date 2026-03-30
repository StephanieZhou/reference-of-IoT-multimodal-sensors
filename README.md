# reference-of-IoT-multimodal-sensors
References of multimodal sensors used in IoT applications
# Sensors Reference

This document provides a comprehensive reference for sensors used in this work, including their key specifications and datasheet links.

---

## Voltage Output Sensors

| Sensor | Application | Output Impedance | Supply Voltage | Output Range | Datasheet Link |
|--------|-------------|------------------|----------------|--------------|----------------|
| E-201-C (Used in this work) | pH | ≤ 10 Ω* | AC 220V ±22V (with pH meter) | ±1999 mV / 0-14 pH | [INESA Product Center](https://www.inesarex.com/products_Detail/52.html) |
| TSC1021 | Current | ≤ 10 Ω* | 2.8V to 30V (common-mode) / 5V supply | Ground-referenced output, internally fixed gain 20/50 V/V | [STMicroelectronics Datasheet](https://www.st.com/resource/en/datasheet/tsc1021.pdf) |
| EX-501 | Vibration | ≤ 100 Ω* | 12 to 24 VDC ±10% | 0 to 5 V (voltage output) / 4 to 20 mA (current output) | [KEYENCE Product Page](https://www.keyence.com/products/sensor/proximity/ex-500/) |
| 5TC-GG-K-20-36 | Temperature | ≤ 50 Ω* | Passive (thermocouple, no external supply) | Type K: 0 to 482°C measurement range, output voltage ~40 µV/°C | [OMEGA Datasheet](https://www.omega.com/en-us/temperature-measurement/thermocouple-wire/p/5TC-GG-K-20-36) |
| Zemic L6D | Force | 350 Ω | 5 to 12 VDC (recommended), max 18 VDC | 2.0 ±0.2 mV/V (rated output) | [Zemic Datasheet](https://www.zemic.com.cn/en/product/load-cells/single-point/l6d/) |
| MPM160 | Pressure | 4 kΩ | ≤10 VDC or ≤3.0 mADC | mV output (Wheatstone bridge) | [MicroSensor Datasheet](https://www.microsensorcorp.com/Product/MPM160.html) |
| GZP193-201GF01 | Pressure | 5 kΩ | ≤16 V (constant voltage) / ≤0.94 mA (constant current) | Temperature-compensated voltage output (ratio metric to supply) | [Genuine Datasheet](https://www.genuine.com.cn/product/87.html) |

*\*: add output buffer.*

---

## Current Output Sensors

| Sensor | Application | Output Impedance | Supply Voltage | Output Range | Datasheet Link |
|--------|-------------|------------------|----------------|--------------|----------------|
| BH1620FVC-TR (Used in this work) | Light | > 1 MΩ | 2.4V to 5.5V | Analog current output, 7.5 mA max photo current | [ROHM Datasheet](https://www.rohm.com/products/sensors-mems/ambient-light-sensor-ics/analog-current-output/bh1620fvc-product) |
| APDS-9005 | Light | > 1 MΩ | 1.8V to 5.5V | Analog current output, 40 µA max output current | [Broadcom Datasheet](https://www.broadcom.com/products/optical-sensors/ambient-light-sensors/apds-9005) |
| VEMD5525FX02 | Light | > 10 MΩ | No external supply (photodiode) | Reverse light current: 0.11 µA at 100 lux | [Vishay Datasheet](https://www.vishay.com/en/product/80560/) |
| BPW34 | Light | 10-100 MΩ | No external supply (photodiode) | Reverse light current: typical 50 µA at 1000 lux | [Vishay Datasheet](https://www.vishay.com/en/product/81566/) |
| Alpha Sense CO-A4 | Gas | 1-100 MΩ | No external supply (electrochemical) | Current output: nA to µA range proportional to CO concentration | [Alphasense Datasheet](https://www.alphasense.com/product/co-a4/) |
| GUVA-S12SD | UV | > 1 GΩ | No external supply (photodiode) | Photocurrent output: nA level, typical 4.3 V per 1 µA with external op-amp | [Genicom Datasheet](https://www.genicom.com/product/guva-s12sd/) |

---

## Resistive Output Sensors (NTC Thermistors)

| Type | Application | Resistance@0°C | Resistance@25°C | Resistance@85°C | Supply / Excitation | Output (Voltage Divider) | Datasheet Link |
|------|-------------|----------------|-----------------|-----------------|---------------------|--------------------------|----------------|
| MF58-105-4250 (Used in this work) | NTC | 3,700 kΩ | 1,000 kΩ | 91 kΩ | Passive (voltage divider with series resistor) | Voltage divider output varies with temperature | [MF58 Series Datasheet](https://www.lcsc.com/product-detail/NTC-Thermistors_Nanjing-Shiheng-Elec-MF58-104F3950_C123399.html) |
| NTCS0805E3684HXT | NTC | 1,680 kΩ | 680 kΩ | 72 kΩ | Passive (voltage divider) | Voltage divider output varies with temperature | [Vishay NTCS0805 Datasheet](https://www.vishay.com/en/product/thermistors/ntcs0805e3/) |
| 105NT-4-R025H46G | NTC | 3,420 kΩ | 1,000 kΩ | 82 kΩ | Passive (voltage divider) | Voltage divider output varies with temperature | [SEMITEC NT Series Datasheet](https://www.semitec.co.jp/english/products/thermistor/nt/) |
| GP105V8J | NTC | 2,880 kΩ | 1,000 kΩ | 80 kΩ | Passive (voltage divider) | Voltage divider output varies with temperature | [Littelfuse GP Series Datasheet](https://www.littelfuse.com/products/temperature-sensors/ntc-thermistors/glass-encapsulated/gp-series.aspx) |
| NTCG104QH105HT1 | NTC | 4,330 kΩ | 1,000 kΩ | 65 kΩ | Passive (voltage divider) | Voltage divider output varies with temperature | [TDK NTCG Series Datasheet](https://product.tdk.com/en/products/sensor/ntc/chip-ntc-thermistor/index.html) |
| MF58-504-4050 | NTC | 1,840 kΩ | 500 kΩ | 53 kΩ | Passive (voltage divider) | Voltage divider output varies with temperature | [MF58 Series Datasheet](https://www.digikey.hk/en/products/detail/cantherm/MF58104F3950/1840608) |

---

## Summary Tables

### Voltage Output Sensors - Quick Reference

| Category | Sensors | Supply Voltage Summary | Output Summary |
|----------|--------|------------------------|----------------|
| pH Sensor | E-201-C | 220V AC (with meter) | ±1999 mV, 0-14 pH |
| Current Sense | TSC1021 | 2.8-30V (common-mode), 5V supply | Fixed gain 20/50 V/V |
| Vibration | EX-501 | 12-24V DC | 0-5V or 4-20mA |
| Temperature | 5TC-GG-K-20-36 | Passive | ~40 µV/°C |
| Force | Zemic L6D | 5-12V DC (recommended) | 2.0 mV/V |
| Pressure | MPM160 | ≤10V DC or ≤3mA | mV output (bridge) |
| Pressure | GZP193-201GF01 | ≤16V or ≤0.94mA | Ratio metric voltage output |

### Current Output Sensors - Quick Reference

| Category | Sensors | Supply Voltage Summary | Output Summary |
|----------|--------|------------------------|----------------|
| Ambient Light | BH1620FVC-TR | 2.4-5.5V | Analog current, 7.5mA max |
| Ambient Light | APDS-9005 | 1.8-5.5V | Analog current, 40µA max |
| Ambient Light | VEMD5525FX02 | Passive | 0.11µA @ 100 lux |
| Ambient Light | BPW34 | Passive | 50µA @ 1000 lux |
| Gas (CO) | Alpha Sense CO-A4 | Passive | nA-µA (electrochemical) |
| UV | GUVA-S12SD | Passive | nA level photocurrent |

---

## Notes

- **Output Impedance Values**: Based on manufacturer specifications
- **Access Dates**: All links accessed March 30, 2026
- **MF58 Series**: Manufactured by multiple suppliers including Nanjing Shiheng, Cantherm, and Xingxiang Electronics
- **\* Output Buffer**: Indicates sensors requiring an output buffer for proper signal conditioning
- **NTC Thermistors**: Resistive output sensors require an external voltage divider circuit to convert resistance change to voltage output. Typical excitation uses a series resistor (e.g., 10 kΩ to 1 MΩ) with a reference voltage (e.g., 3.3V or 5V)
- **Passive Sensors**: Sensors marked "passive" generate their own output signal and do not require an external power supply for operation (thermocouples, photodiodes, electrochemical sensors)
