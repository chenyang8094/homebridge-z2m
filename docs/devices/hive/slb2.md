---
title: "Hive SLB2 Homebridge/HomeKit integration"
description: "Add HomeKit support to your Hive SLB2, using Homebridge, Zigbee2MQTT and homebridge-z2m."
---
<!---
This file has been GENERATED using src/docgen/docgen.ts
DO NOT EDIT THIS FILE MANUALLY!
-->
# Hive SLB2
> Signal booster


# Unsupported
This device is currently *UNSUPPORTED*.
Want to have this device supported? Please check the [GitHub issue section](https://github.com/itavero/homebridge-z2m/issues?q=SLB2) to see if a request already exists for this device.
If it doesn't exist yet, you can [open a new request](https://github.com/itavero/homebridge-z2m/issues/new?assignees=&labels=enhancement&template=device_support.md&title=%5BDevice%5D+Hive+SLB2) by filling in the _Device support_ issue template.

## Exposes
```json
[
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
* [Other devices from Hive](../index.md#hive)
* [Zigbee2MQTT documentation for this device](https://www.zigbee2mqtt.io/devices/SLB2.html)