# Hacky Home assistant support for Xiaomi vacuum STYJ02YM 

### Install:
- install it with HACS
- Add the configuration to configuration.yaml, example:

```yaml
vacuum:
  - platform: miio2
    host: 192.168.68.105
    token: !secret vacuum
    name: Mi hihi
```
