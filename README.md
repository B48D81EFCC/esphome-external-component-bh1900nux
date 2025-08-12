# ROHM Semiconductor BH1900NUX – Digital Temperature Sensor (ESPHome External Component)
[ESPHome External Component](https://esphome.io/components/external_components.html) for the **BH1900NUX** temperature sensor IC, enabling its use with ESPHome via I²C.

## Usage
To use this component, include the following in your ESPHome configuration:

```yaml
external_components:
  - source: github://B48D81EFCC/esphome-external-component-bh1900nux@main
    components: [ bh1900nux ]
    refresh: 1h

```
For more details on the External Component feature, refer to the official [ESPHome documentation](https://esphome.io/components/external_components.html)

# ESPHome built-in component vs. ESPHome External Component
Since version XXX, ESPHome already includes a built-in component for the BH1900NUX sensor.  
The built-in version is based on this external component.  
  
The purpose of this external component is to allow changes, new features, and bug fixes to be implemented, tested, and used more quickly.  
Once these changes have been validated, the code may be incorporated into the official ESPHome codebase via the [official contributing workflow](https://developers.esphome.io/contributing/code/).

# Requirements
- ESPHome (tested with ESPHome 2025.7.0)
- ESP32 board

# Reference
[BH1900NUX Product Page – ROHM Semiconductor](https://www.rohm.com/products/sensors-mems/temperature-sensor-ics/bh1900nux-product)
