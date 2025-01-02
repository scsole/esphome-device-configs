# ESPHome Device Configs

ESPHome configurations for various devices.

## Notes

This repository contains opinionated configurations for ESP based devices. Common components (e.g.
diagnostic sensors) are packaged inside the modules directory. Device specific features are
contained in their respective device config. This helps unify devices with set of baseline controls
and allows each device config file to focus on the hardware features at hand.

## Additional Device Notes

### Athom

Main changes from stock firmware

- Simplify config by using native components where relevant
- Use Home Assistant for time (no need to set timezone)
- Disable most sensors by default in Home Assistant
- Improve uptime sensor efficiency
- Remove superfluous diagnostic sensors

## Sonoff

TODO: Refactor using modules
