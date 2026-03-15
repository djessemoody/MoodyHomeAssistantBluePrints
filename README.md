# Moody Home Assistant Blueprints

A collection of Home Assistant automation blueprints.

## Blueprints

### Dimmer Brightness Caster

When a dimmer switch changes brightness, cast that brightness level to one or more target lights. Includes configurable transition time.

[![Open your Home Assistant instance and show the blueprint import dialog with this blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fdjessemoody%2FMoodyHomeAssistantBluePrints%2Fblob%2Fmain%2FBlueprints%2Fdimmer_brightness_caster.yaml)

### Trigger Fan On High Humidity

Turns a fan on in high humidity situations, envisioned as a bathroom fan switch.

[![Open your Home Assistant instance and show the blueprint import dialog with this blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fdjessemoody%2FMoodyHomeAssistantBluePrints%2Fblob%2Fmain%2FBlueprints%2Ftrigger_fan_on_high_humidity.yaml)

### Auto Off Timer

Automatically turns off a light or switch after a configurable number of seconds. If the entity is turned on again while the timer is running, the timer restarts — great for bathroom lights, closet lights, or any switch that should turn itself off.

[![Open your Home Assistant instance and show the blueprint import dialog with this blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fdjessemoody%2FMoodyHomeAssistantBluePrints%2Fblob%2Fmain%2FBlueprints%2Fauto_off_timer.yaml)

### Z-Wave Scene Controller / Remote Switch

Map actions to button presses on any Z-Wave device that supports Central Scene (Scene 001 / Scene 002). Originally built around the Zooz ZEN34 remote switch, but should work with any compatible Z-Wave device including:

- Zooz ZEN34 Remote Switch
- Zooz ZEN32 Scene Controller (main paddle)
- Zooz ZEN71/ZEN72/ZEN76/ZEN77 wall switches/dimmers (scene control must be enabled)
- Inovelli Red/Blue series switches
- GE/Jasco in-wall switches
- Aeotec NanoMote and other Z-Wave remotes

Supports single tap through 5x tap, hold, and release for both the upper and lower buttons (up to 14 actions total).

[![Open your Home Assistant instance and show the blueprint import dialog with this blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fdjessemoody%2FMoodyHomeAssistantBluePrints%2Fblob%2Fmain%2FBlueprints%2Fzwave_scene_controller_remote.yaml)
