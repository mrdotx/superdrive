# apple superdrive udev rule

this udev rule sends a bit sequence to the apple superdrive to use the drive with other operating systems besides osx.
to use this rule, it is necessary to install `sg3-utils` if not already done so.

## install 99-superdrive.rules

- copy file 99-superdrive.rules to /etc/udev/rules.d
