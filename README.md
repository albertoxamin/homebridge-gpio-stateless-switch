# homebridge-gpio-relay-lock
Homebridge plugin to control stateless lock relay via Raspberry Pi GPIO pins

## Example config
```json
{
  "bridge": {
    "name": "Homebridge",
    "username": "CC:22:3D:E3:CE:30",
    "port": 51826,
    "pin": "031-45-154"
  },
  "description": "This is an example configuration for the Homebridge GPIO Stateless Switch plugin",
  "accessories": [
    {
      "accessory": "ElectromagneticLock",
      "name": "Entrance Lock",
      "pin": 5,
      "activeLow": true
    }
  ]
}

```