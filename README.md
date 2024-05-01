# apple superdrive udev rule

this udev rule sends a bit sequence to the apple superdrive to use the drive with other operating systems besides osx.
to use this rule, it is necessary to install `sg3-utils` if not already done so.

related projects:

- [fzf](https://github.com/mrdotx/fzf)

## install 99-superdrive.rules

- cp 99-superdrive.rules /etc/udev/rules.d/99-superdrive.rules
