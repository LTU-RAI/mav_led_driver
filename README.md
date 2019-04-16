# Constant current LED driver with camera flash sync and over-current protection

A simple LED driver intended for use on Micro Aerial Vehicles (MAV), where the minimum LED forward voltage should be 20V, and max 50V, by having multiple panels in series. The PCB design is made so it can be used as a module to be soldered on another PCB.

Design specifications:

* Simple 2-layer, 0.3mm vias, 0.2mm trace/space rules
* 11-18V input (3-4S)
* 20-50V output (2-4 12V LED panels in series)
* 350/700mA output current (settable with solder jumper / max 450mA when running 4 LED panels)
* Sync pin which can be used to sync the LED panels to a camera flash

---

## Contributors

List of contributors in alphabetical order:

* Emil Fresk ([@korken89](https://github.com/korken89))

---

## License

The hardware is OSHW using the Cern-OHL license.
