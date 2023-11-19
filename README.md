# Official Devices

This is our repo where all stuff related to official devices is stored.

You also need to use this to apply for official maintainership for your device.

## `devices.json` Structure

This file should contain every device supported by **HorizonDroid** in the given format:

```json
{
  "devices": [
    {
      "codename": "marble",
      "codename_alt": "marble",
      "vendor": "Xiaomi",
      "model": "Xiaomi Poco F5",
      "maintainer_name": "Ryzenforce and JYR_RC",
      "active": true
    },
    {
      "codename": "sweet",
      "vendor": "Xiaomi",
      "model": "Xiaomi Redmi Note 10 Pro",
      "maintainer_name": "Unmoved",
      "active": true
    }
  ]
}
```

> **Warning**
>
> Fields marked as required should not be empty!

| Fields            | Notes                                               | Required   |
| ----------------- | --------------------------------------------------- | ---------- |
| `codename`        | Primary codename of the device                      | `true`     |
| `codename_alt`    | Alternate codename of the device if any             | `optional` |
| `vendor`          | Device manufacturer name                            | `true`     |
| `model`           | Device name                                         | `true`     |
| `maintainer_name` | Maintainer name                                     | `true`     |
| `active`          | Whether this device is in active development or not | `true`     |

## `team.json` Structure

This file should contain every team member working on **Awaken OS** in the given format:

```json
{
  "team": [
    {
      "name": "Ryzenforce",
      "role": "Founder & Lead Developer",
      "socials": {
        "github": "ryzenforce990",
        "telegram": "ryzenforce",
        "xda": "ryzenforce"
      }
    },
    {
      "name": "Isaiah",
      "role": "Manager",
      "socials": {
        "github": "isaiahscape",
        "telegram": "isaiahscape",
        "xda": "sevitches"
      }
    }
  ]
}
```

> **Warning**
>
> Fields marked as required should not be empty!

| Fields     | Notes                     | Required   |
| ---------- | ------------------------- | ---------- |
| `name`     | Member name               | `true`     |
| `role`     | Role of the member        | `true`     |
| `github`   | Member's github username  | `true`     |
| `telegram` | Member's telegram profile | `optional` |
| `xda`      | Member's XDA profile      | `optional` |

1. [Device stability requirements](requirements.md)
2. [Maintainer requirements](maintainerreq.md)
3. [Maintainership form](https://github.com/Project-Awaken/official_devices/issues/new/choose)
