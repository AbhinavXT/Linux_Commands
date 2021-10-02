reboot [OPTIONS...] [ARG]

Reboot the system.

Options:
     --help      Show this help
     --halt      Halt the machine
  -p --poweroff  Switch off the machine
     --reboot    Reboot the machine
  -f --force     Force immediate halt/power-off/reboot
  -w --wtmp-only Don't halt/power-off/reboot, just write wtmp record
  -d --no-wtmp   Don't write wtmp record
     --no-wall   Don't send wall message before halt/power-off/reboot

See the halt(8) man page for details.
