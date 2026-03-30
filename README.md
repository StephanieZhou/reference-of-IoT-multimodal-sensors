# Sensors Reference

This document provides a comprehensive reference for sensors used in this work, including their key specifications and datasheet links.

---

## Voltage Output Sensors

| Sensor | Application | Output Impedance | Datasheet Link |
|--------|-------------|------------------|----------------|
| E-201-C (Used in this work) | pH | ≤ 10 Ω* | [INESA Product Center](https://www.inesarex.com/products_Detail/52.html) |
| TSC1021 | Current | ≤ 10 Ω* | [STMicroelectronics Datasheet](https://www.st.com/resource/en/datasheet/tsc1021.pdf) |
| EX-501 | Vibration | ≤ 100 Ω* | [KEYENCE Product Page](https://www.keyence.com/products/sensor/proximity/ex-500/) |
| 5TC-GG-K-20-36 | Temperature | ≤ 50 Ω | [OMEGA Datasheet](https://www.omega.com/en-us/temperature-measurement/thermocouple-wire/p/5TC-GG-K-20-36) |
| Zemic L6D | Force | 350 Ω | [Zemic Datasheet](https://www.zemic.com.cn/en/product/load-cells/single-point/l6d/) |
| MPM160 | Pressure | 4 kΩ | [MicroSensor Datasheet](https://www.microsensorcorp.com/Product/MPM160.html) |
| GZP193-201GF01 | Pressure | 5 kΩ | [Genuine Datasheet](https://www.genuine.com.cn/product/87.html) |

*\*: add output buffer.*

---

## Current Output Sensors

| Sensor | Application | Output Impedance | Datasheet Link |
|--------|-------------|------------------|----------------|
| BH1620FVC-TR (Used in this work) | Light | > 1 MΩ | [ROHM Datasheet](https://www.rohm.com/products/sensors-mems/ambient-light-sensor-ics/analog-current-output/bh1620fvc-product) |
| APDS-9005 | Light | > 1 MΩ | [Broadcom Datasheet](https://www.broadcom.com/products/optical-sensors/ambient-light-sensors/apds-9005) |
| VEMD5525FX02 | Light | > 10 MΩ | [Vishay Datasheet](https://www.vishay.com/en/product/80560/) |
| BPW34 | Light | 10-100 MΩ | [Vishay Datasheet](https://www.vishay.com/en/product/81566/) |
| Alpha Sense CO-A4 | Gas | 1-100 MΩ | [Alphasense Datasheet](https://www.alphasense.com/product/co-a4/) |
| GUVA-S12SD | UV | > 1 GΩ | [Genicom Datasheet](https://www.genicom.com/product/guva-s12sd/) |

---

## Resistive Output Sensors (NTC Thermistors)

| Type | Application | Resistance@0°C | Resistance@25°C | Resistance@85°C | Datasheet Link |
|------|-------------|----------------|-----------------|-----------------|----------------|
| MF58-105-4250 (Used in this work) | NTC | 3,700 kΩ | 1,000 kΩ | 91 kΩ | [MF58 Series Datasheet](https://www.lcsc.com/product-detail/NTC-Thermistors_Nanjing-Shiheng-Elec-MF58-104F3950_C123399.html) |
| NTCS0805E3684HXT | NTC | 1,680 kΩ | 680 kΩ | 72 kΩ | [Vishay NTCS0805 Datasheet](https://www.vishay.com/en/product/thermistors/ntcs0805e3/) |
| 105NT-4-R025H46G | NTC | 3,420 kΩ | 1,000 kΩ | 82 kΩ | [SEMITEC NT Series Datasheet](https://www.semitec.co.jp/english/products/thermistor/nt/) |
| GP105V8J | NTC | 2,880 kΩ | 1,000 kΩ | 80 kΩ | [Littelfuse GP Series Datasheet](https://www.littelfuse.com/products/temperature-sensors/ntc-thermistors/glass-encapsulated/gp-series.aspx) |
| NTCG104QH105HT1 | NTC | 4,330 kΩ | 1,000 kΩ | 65 kΩ | [TDK NTCG Series Datasheet](https://product.tdk.com/en/products/sensor/ntc/chip-ntc-thermistor/index.html) |
| MF58-504-4050 | NTC | 1,840 kΩ | 500 kΩ | 53 kΩ | [MF58 Series Datasheet](https://www.digikey.hk/en/products/detail/cantherm/MF58104F3950/1840608) |

---

## Summary

| Category | Sensors |
|----------|--------|
| **Voltage Output** | E-201-C, TSC1021, EX-501, 5TC-GG-K-20-36, Zemic L6D, MPM160, GZP193-201GF01 |
| **Current Output** | BH1620FVC-TR, APDS-9005, VEMD5525FX02, BPW34, Alpha Sense CO-A4, GUVA-S12SD |
| **Resistive Output** | MF58-105-4250, NTCS0805E3684HXT, 105NT-4-R025H46G, GP105V8J, NTCG104QH105HT1, MF58-504-4050 |

---

## Notes

- **Output Impedance Values**: Based on manufacturer specifications
- **Access Dates**: All links accessed March 30, 2026
- **MF58 Series**: Manufactured by multiple suppliers including Nanjing Shiheng, Cantherm, and Xingxiang Electronics
- **\* Output Buffer**: Indicates sensors requiring an output buffer for proper signal conditioning
