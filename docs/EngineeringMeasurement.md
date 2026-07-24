\# Engineering Measurement Framework



\## Purpose



The Engineering Measurement framework extends MQTT Devices with support for engineering measurements that consist of a numeric value and engineering units.



Examples:



\- 73.8 PSI

\- 12.54 V

\- 3.11 A

\- 1525 RPM

\- 18.7 GPM



\## Goals



\- Preserve numeric values for SmartThings automations.

\- Display engineering units on the device tile.

\- Provide a reusable framework for future sensor types.



\## Planned Device Types



\- Water Pressure

\- Voltage

\- Current

\- Power

\- Flow

\- Tank Level

\- RPM



\## MQTT Payload



Example JSON payload:



```json

{

&#x20;   "value": 73.8,

&#x20;   "unit": "PSI"

}

```



\## Version



MQTT Devices Extended v1.9.1

