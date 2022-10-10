# Disable Pi Internal Audio

Disables the internal audio of a raspberry pi by setting the relevant flags in `/boot/config.txt`.

For the changes to take effect, a reboot of the device is required.
This is not performed by the role.


## Requirements

- raspbian / Raspberry Pi OS

## Role Variables

| Name                                            |                     Required/Default                     | Description                              |
| ----------------------------------------------- | :------------------------------------------------------: | ---------------------------------------- |
| `disable_pi_internal_audio_skip_hdmi`           |                         `False`                          | Whether to skip disabling the hdmi audio |
| `disable_pi_internal_audio_skip_analog` | `False` | Whether to skip disabling the analog (via bcm2835) audio |


## License

This work is licensed under the [MIT License](./LICENSE).


## Author Information

- [Tim Neumann (neumantm)](https://github.com/neumantm) _tim.neumann at stuvus.uni-stuttgart.de_
