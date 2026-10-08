# Changelog

## v1.9.1

Initial development branch.

Added project documentation.

Engineering Measurement framework planned.

## 2026-10-07

### Water Pressure MQTT Device

- Added `WaterPressure` device type to MQTT Device Creator.
- Added the `mqttwaterpressure.v1` profile.
- Added the `displayvalue` capability for custom value/unit display.
- Added Water Pressure support to MQTT message processing.
- Water Pressure displays the numeric value together with its unit.

### Aranet Rn One / Numeric Display

- Added the `displayvalue` capability to the Numeric device profile.
- Numeric devices now display values to two decimal places on the tile.
- Numeric display includes the configured unit.
- Example: `0.78 pCi/L`.
- Existing Water Pressure display behavior is preserved.

### Aranet MQTT Format

Aranet Rn One data is published to:

`aranet/radon_one/radon`

The payload uses JSON:

```json
{"value":0.783,"Units":"pCi/L"}

