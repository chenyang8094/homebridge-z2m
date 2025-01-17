---
title: "Climax SRAC-23B-ZBSR Homebridge/HomeKit integration"
description: "Add HomeKit support to your Climax SRAC-23B-ZBSR, using Homebridge, Zigbee2MQTT and homebridge-z2m."
---
<!---
This file has been GENERATED using src/docgen/docgen.ts
DO NOT EDIT THIS FILE MANUALLY!
-->
# Climax SRAC-23B-ZBSR
> Smart siren


# Services and characteristics
The following HomeKit Services and Characteristics are exposed by
the Climax SRAC-23B-ZBSR

* [Battery](../../battery.md)
  * BatteryLevel
  * ChargingState
  * StatusLowBattery



## Exposes

```json
[
  {
    "type": "composite",
    "property": "warning",
    "name": "warning",
    "features": [
      {
        "type": "enum",
        "name": "mode",
        "property": "mode",
        "access": 2,
        "values": [
          "stop",
          "burglar",
          "fire",
          "emergency",
          "police_panic",
          "fire_panic",
          "emergency_panic"
        ],
        "description": "Mode of the warning (sound effect)"
      },
      {
        "type": "enum",
        "name": "level",
        "property": "level",
        "access": 2,
        "values": [
          "low",
          "medium",
          "high",
          "very_high"
        ],
        "description": "Sound level"
      },
      {
        "type": "binary",
        "name": "strobe",
        "property": "strobe",
        "access": 2,
        "value_on": true,
        "value_off": false,
        "description": "Turn on/off the strobe (light) during warning"
      },
      {
        "type": "numeric",
        "name": "duration",
        "property": "duration",
        "access": 2,
        "unit": "s",
        "description": "Duration in seconds of the alarm"
      }
    ]
  },
  {
    "type": "binary",
    "name": "battery_low",
    "property": "battery_low",
    "access": 1,
    "value_on": true,
    "value_off": false,
    "description": "Indicates if the battery of this device is almost empty"
  },
  {
    "type": "binary",
    "name": "tamper",
    "property": "tamper",
    "access": 1,
    "value_on": true,
    "value_off": false,
    "description": "Indicates whether the device is tampered"
  },
  {
    "type": "numeric",
    "name": "battery",
    "property": "battery",
    "access": 1,
    "unit": "%",
    "description": "Remaining battery in %",
    "value_min": 0,
    "value_max": 100
  },
  {
    "type": "numeric",
    "name": "linkquality",
    "property": "linkquality",
    "access": 1,
    "unit": "lqi",
    "description": "Link quality (signal strength)",
    "value_min": 0,
    "value_max": 255
  }
]
```

# Related
* [Other devices from Climax](../index.md#climax)
* [Zigbee2MQTT documentation for this device](https://www.zigbee2mqtt.io/devices/SRAC-23B-ZBSR.html)